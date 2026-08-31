<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1788169985" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-0158FF?style=for-the-badge&labelColor=0B1220" alt="Website"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Tracked-719,960-0158FF?style=for-the-badge&labelColor=0B1220" alt="Tracked"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Live-59,874-0158FF?style=for-the-badge&labelColor=0B1220" alt="Live"></a>
  <a href="https://github.com/hproxy-com/free-proxy-list/commits/main"><img src="https://img.shields.io/badge/Updated-continuously-0158FF?style=for-the-badge&labelColor=0B1220" alt="Updated"></a>
  <a href="https://apify.com/hproxy-owner/hproxy-free-proxy-list"><img src="https://img.shields.io/badge/Free_API-on_Apify-0158FF?style=for-the-badge&labelColor=0B1220" alt="Free API"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-0158FF?style=for-the-badge&labelColor=0B1220" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.44_per_GB-0158FF?style=for-the-badge&labelColor=0B1220" alt="Premium Proxies"></a>
</p>

<p align="center"><b>The biggest free proxy list on the internet, continuously verified 24/7.</b></p>
<p align="center"><sub>HTTP, HTTPS, SOCKS4 and SOCKS5 &middot; country, anonymity, latency and uptime on every IP &middot; updated 31.08.2026</sub></p>

HProxy publishes the largest continuously verified list of free public proxies. We aggregate **100+ public sources** every few minutes, test every proxy through **HTTP, HTTPS, SOCKS4 and SOCKS5** around the clock, and enrich each working one with **country, anonymity grade, latency and uptime**. Over **719,960 proxies tracked all-time**, with **59,874** live and working in the pool right now. It is completely free, updated continuously, and needs no signup and no API key.

If you have been copying proxies from a dozen different repos and sites, you do not need to any more: this list is their verified superset. See [Sources we aggregate](#sources-we-aggregate).

## Quick facts

- **719,960** proxies tracked all-time, **59,874** live right now
- **4 protocols**: HTTP, HTTPS, SOCKS4, SOCKS5
- Aggregated from **100+ public sources**, deduplicated and format-validated
- **Verified around the clock**, list refreshed every few minutes
- Every live proxy carries **country, city, anonymity, latency and uptime**
- **Free**, no signup, no API key, no rate limits on the raw files
- Filtered lists: per protocol, per country, and by anonymity tier (elite / anonymous / fast)
- Formats: **txt, json, csv**

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| **All** | 59,874 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 7,761 | [txt](http.txt) |
| HTTPS | 3,546 | [txt](https.txt) |
| SOCKS4 | 2,937 | [txt](socks4.txt) |
| SOCKS5 | 5,270 | [txt](socks5.txt) |
| Elite (high-anonymity) | 10,449 | [txt](elite.txt) |
| Anonymous | 657 | [txt](anonymous.txt) |
| Fast (under 2s) | 5,719 | [txt](fast.txt) |
| United States (US) | 24,649 | [txt](by-country/US.txt) &middot; [all &raquo;](by-country) |

Text files are one `ip:port` per line. `all.json` and `all.csv` add protocol, anonymity, country, city, latency and uptime for every proxy.

<details>
<summary><b>Free proxies by country</b> (132 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| United States (US) | 24,649 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 3,528 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 3,112 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 2,328 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 2,283 | [by-country/JP.txt](by-country/JP.txt) |
| Australia (AU) | 2,103 | [by-country/AU.txt](by-country/AU.txt) |
| Canada (CA) | 1,580 | [by-country/CA.txt](by-country/CA.txt) |
| Hong Kong (HK) | 1,552 | [by-country/HK.txt](by-country/HK.txt) |
| France (FR) | 1,384 | [by-country/FR.txt](by-country/FR.txt) |
| South Korea (KR) | 1,370 | [by-country/KR.txt](by-country/KR.txt) |
| Thailand (TH) | 1,251 | [by-country/TH.txt](by-country/TH.txt) |
| South Africa (ZA) | 1,216 | [by-country/ZA.txt](by-country/ZA.txt) |
| _+120 more countries_ | | [full by-country/ folder &raquo;](by-country) |

</details>

## Every proxy is enriched

Most free proxy lists hand you a bare `ip:port` and nothing else. We verify each proxy and attach the data that tells you whether it is actually worth using:

| Field | What it tells you |
|-------|-------------------|
| `protocols` | Which of HTTP / HTTPS / SOCKS4 / SOCKS5 it actually speaks |
| `anonymity` | transparent, anonymous, or elite (does it leak your IP) |
| `country` / `city` | Where the exit is |
| `latency_ms` | Real measured response time |
| `uptime_24h` / `uptime_7d` | How reliable it has been, not just alive once |

All of it lives in [all.json](all.json) and [all.csv](all.csv).

## Use it in your code

**Python (requests):**

```python
import random, requests

proxies = requests.get(
    "https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.txt"
).text.split()

proxy = random.choice(proxies)
r = requests.get("https://api.ipify.org",
                 proxies={"http": f"http://{proxy}", "https": f"http://{proxy}"},
                 timeout=10)
print(r.text)
```

**curl:**

```bash
curl -x http://$(curl -s https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/http.txt | head -1) https://api.ipify.org
```

**Node.js:**

```js
const list = await fetch("https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.txt")
  .then(r => r.text());
const proxies = list.trim().split("\n");
```

## Use as an API

Every file is a raw endpoint, refreshed continuously (also mirrored on the jsDelivr CDN so there are no rate limits):

```bash
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.txt            # every proxy, ip:port
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/by-country/US.txt  # one country
curl https://cdn.jsdelivr.net/gh/hproxy-com/free-proxy-list@main/all.json           # full details via CDN
```

Prefer a hosted API with country and protocol filtering and no repo cloning? Run the free **[HProxy Free Proxy List actor on Apify](https://apify.com/hproxy-owner/hproxy-free-proxy-list)** (no key, no signup), or use the real-time API and full docs at **[hproxy.com/docs](https://hproxy.com/docs)**.

## FAQ

**How many free proxies are in this list?**
Over 719,960 have been tracked all-time, and 59,874 are live and verified in the working pool right now. The published files hold the proxies confirmed working within the last 48 hours.

**Which protocols are supported?**
HTTP, HTTPS, SOCKS4 and SOCKS5. Each proxy is labelled with the protocols it actually answered on, not just the ones it was listed under.

**How often is the list updated?**
Continuously. New candidates are pulled from 100+ sources every few minutes, verified around the clock, and the files here are regenerated as results come in.

**Are the proxies anonymous?**
Each one is graded transparent, anonymous or elite based on whether it leaks your real IP. Filter on the `anonymity` field in `all.json` or `all.csv`.

**How do I use a proxy in Python?**
See [Use it in your code](#use-it-in-your-code) above. Pull `all.txt`, pick a line, and pass it to `requests` as an `http`/`https` proxy.

**Do I need an API key or an account?**
No. The raw files and the [Apify actor](https://apify.com/hproxy-owner/hproxy-free-proxy-list) are free with no signup.

**Are free proxies safe to use?**
Treat them as public and untrusted. They are great for web scraping, testing, and reaching geo-restricted content, but you should never send passwords, logins or sensitive data through a public proxy. For anything that matters, use dedicated proxies (see below).

**How is this different from other free proxy lists?**
Two things. First, every proxy here is actually verified and enriched (country, anonymity, latency, uptime), not just scraped and dumped. Second, this list is the superset of the ecosystem: we already aggregate the sources other lists pull from, so one file replaces all of them.

## Sources we aggregate

We continuously pull from 100+ public proxy sources, then dedupe, verify and enrich everything in one place, so you do not have to. Instead of scraping and cross-checking a dozen separate public repos and proxy sites yourself, this single list is their verified, de-duplicated superset, refreshed around the clock.

Found a public proxy source you think we should pull from? [Open an issue](https://github.com/hproxy-com/free-proxy-list/issues) and we will consider adding it to the engine.

## How it works

1. **Aggregate** fresh candidates from 100+ public sources, around the clock.
2. **Verify** every proxy through HTTP, HTTPS, SOCKS4 and SOCKS5, 24/7.
3. **Enrich** each live proxy with country, anonymity grade, latency and uptime.
4. **Publish** the freshly verified list here, continuously.

## Powered by HProxy

Free proxies die fast and are often already blocked. When you need proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.44/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential) &nbsp;&middot;&nbsp; [Free API on Apify](https://apify.com/hproxy-owner/hproxy-free-proxy-list)

## Contributing

Raw IPs cannot be added by pull request: the list regenerates every few minutes from the verification engine, so committed entries would be overwritten on the next update. The useful way to help is to [suggest a public proxy source](CONTRIBUTING.md) for the engine to pull from.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; continuously updated &nbsp;&middot;&nbsp; 2026-08-31 09:53 UTC</sub></p>
