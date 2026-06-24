<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1782277286" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Tracked-530,914-006039?style=for-the-badge&labelColor=1A1918" alt="Tracked"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Live-18,377-006039?style=for-the-badge&labelColor=1A1918" alt="Live"></a>
  <a href="https://github.com/hproxy-com/free-proxy-list/commits/main"><img src="https://img.shields.io/badge/Updated-continuously-006039?style=for-the-badge&labelColor=1A1918" alt="Updated"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>The biggest free proxy list, continuously scanned 24/7.</b><br>530,914 proxies tracked all-time, 18,377 in the live working pool (alive within 48h).</p>
<p align="center"><sub>HTTP, HTTPS, SOCKS4 and SOCKS5 &middot; country, anonymity and latency on every IP &middot; updated 24.06.2026</sub></p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| **All** | 18,377 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,331 | [txt](http.txt) |
| HTTPS | 1,390 | [txt](https.txt) |
| SOCKS4 | 1,641 | [txt](socks4.txt) |
| SOCKS5 | 1,512 | [txt](socks5.txt) |
| Iran (IR) | 3,718 | [txt](by-country/IR.txt) &middot; [all &raquo;](by-country) |

Text files are one `ip:port` per line. `all.json` and `all.csv` add protocol, anonymity, country, city, latency and uptime per proxy.

## Use as an API

Every file is a raw endpoint, continuously refreshed (also on the jsDelivr CDN for no rate limits):

```bash
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.txt              # every proxy, ip:port
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/by-country/US.txt    # one country
curl https://cdn.jsdelivr.net/gh/hproxy-com/free-proxy-list@main/all.json            # via jsDelivr CDN
```

Need live filtering by country, protocol and anonymity? Use the real-time API and full docs at **https://hproxy.com/docs**.

<details>
<summary><b>Free proxies by country</b> (125 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 3,718 | [by-country/IR.txt](by-country/IR.txt) |
| Indonesia (ID) | 2,033 | [by-country/ID.txt](by-country/ID.txt) |
| United States (US) | 1,358 | [by-country/US.txt](by-country/US.txt) |
| China (CN) | 1,122 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 836 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 601 | [by-country/JP.txt](by-country/JP.txt) |
| South Korea (KR) | 577 | [by-country/KR.txt](by-country/KR.txt) |
| Germany (DE) | 575 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 569 | [by-country/HK.txt](by-country/HK.txt) |
| Australia (AU) | 487 | [by-country/AU.txt](by-country/AU.txt) |
| Thailand (TH) | 371 | [by-country/TH.txt](by-country/TH.txt) |
| France (FR) | 370 | [by-country/FR.txt](by-country/FR.txt) |
| _+113 more countries_ | | [full by-country/ folder &raquo;](by-country) |

</details>

## How it works

1. **Aggregate** fresh candidates from 90+ public sources, around the clock.
2. **Verify** every proxy through HTTP, HTTPS, SOCKS4 and SOCKS5, 24/7.
3. **Enrich** each live proxy with country, anonymity grade and latency.
4. **Publish** the freshly verified list here, continuously.

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request: the list regenerates every couple of minutes from the verification engine, so committed entries would be overwritten on the next update. The useful way to help is to [suggest a public proxy source](CONTRIBUTING.md) for the engine to pull from.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; continuously updated &nbsp;&middot;&nbsp; 2026-06-24 05:01 UTC</sub></p>
