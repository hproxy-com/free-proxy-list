<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1785468895" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-0158FF?style=for-the-badge&labelColor=0B1220" alt="Website"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Tracked-579,567-0158FF?style=for-the-badge&labelColor=0B1220" alt="Tracked"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Live-30,746-0158FF?style=for-the-badge&labelColor=0B1220" alt="Live"></a>
  <a href="https://github.com/hproxy-com/free-proxy-list/commits/main"><img src="https://img.shields.io/badge/Updated-continuously-0158FF?style=for-the-badge&labelColor=0B1220" alt="Updated"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-0158FF?style=for-the-badge&labelColor=0B1220" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-0158FF?style=for-the-badge&labelColor=0B1220" alt="Premium Proxies"></a>
</p>

<p align="center"><b>The biggest free proxy list, continuously scanned 24/7.</b><br>579,567 proxies tracked all-time, 30,746 in the live working pool (alive within 48h).</p>
<p align="center"><sub>HTTP, HTTPS, SOCKS4 and SOCKS5 &middot; country, anonymity and latency on every IP &middot; updated 31.07.2026</sub></p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| **All** | 30,746 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 3,738 | [txt](http.txt) |
| HTTPS | 1,715 | [txt](https.txt) |
| SOCKS4 | 2,005 | [txt](socks4.txt) |
| SOCKS5 | 1,194 | [txt](socks5.txt) |
| Indonesia (ID) | 3,084 | [txt](by-country/ID.txt) &middot; [all &raquo;](by-country) |

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
<summary><b>Free proxies by country</b> (136 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Indonesia (ID) | 3,084 | [by-country/ID.txt](by-country/ID.txt) |
| United States (US) | 2,835 | [by-country/US.txt](by-country/US.txt) |
| China (CN) | 2,305 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 1,971 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 1,548 | [by-country/JP.txt](by-country/JP.txt) |
| Australia (AU) | 1,469 | [by-country/AU.txt](by-country/AU.txt) |
| South Korea (KR) | 1,146 | [by-country/KR.txt](by-country/KR.txt) |
| Germany (DE) | 1,122 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 1,058 | [by-country/HK.txt](by-country/HK.txt) |
| France (FR) | 968 | [by-country/FR.txt](by-country/FR.txt) |
| Canada (CA) | 908 | [by-country/CA.txt](by-country/CA.txt) |
| Thailand (TH) | 887 | [by-country/TH.txt](by-country/TH.txt) |
| _+124 more countries_ | | [full by-country/ folder &raquo;](by-country) |

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

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; continuously updated &nbsp;&middot;&nbsp; 2026-07-31 03:34 UTC</sub></p>
