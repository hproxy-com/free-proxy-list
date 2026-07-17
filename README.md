<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1784286541" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-0158FF?style=for-the-badge&labelColor=0B1220" alt="Website"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Tracked-564,793-0158FF?style=for-the-badge&labelColor=0B1220" alt="Tracked"></a>
  <a href="https://hproxy.com/free-proxy-list"><img src="https://img.shields.io/badge/Live-23,163-0158FF?style=for-the-badge&labelColor=0B1220" alt="Live"></a>
  <a href="https://github.com/hproxy-com/free-proxy-list/commits/main"><img src="https://img.shields.io/badge/Updated-continuously-0158FF?style=for-the-badge&labelColor=0B1220" alt="Updated"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-0158FF?style=for-the-badge&labelColor=0B1220" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-0158FF?style=for-the-badge&labelColor=0B1220" alt="Premium Proxies"></a>
</p>

<p align="center"><b>The biggest free proxy list, continuously scanned 24/7.</b><br>564,793 proxies tracked all-time, 23,163 in the live working pool (alive within 48h).</p>
<p align="center"><sub>HTTP, HTTPS, SOCKS4 and SOCKS5 &middot; country, anonymity and latency on every IP &middot; updated 17.07.2026</sub></p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| **All** | 23,163 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,693 | [txt](http.txt) |
| HTTPS | 1,228 | [txt](https.txt) |
| SOCKS4 | 1,458 | [txt](socks4.txt) |
| SOCKS5 | 1,497 | [txt](socks5.txt) |
| Indonesia (ID) | 2,420 | [txt](by-country/ID.txt) &middot; [all &raquo;](by-country) |

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
<summary><b>Free proxies by country</b> (133 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Indonesia (ID) | 2,420 | [by-country/ID.txt](by-country/ID.txt) |
| Iran (IR) | 2,405 | [by-country/IR.txt](by-country/IR.txt) |
| China (CN) | 1,767 | [by-country/CN.txt](by-country/CN.txt) |
| United States (US) | 1,711 | [by-country/US.txt](by-country/US.txt) |
| India (IN) | 1,303 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 970 | [by-country/JP.txt](by-country/JP.txt) |
| Australia (AU) | 892 | [by-country/AU.txt](by-country/AU.txt) |
| South Korea (KR) | 769 | [by-country/KR.txt](by-country/KR.txt) |
| Hong Kong (HK) | 700 | [by-country/HK.txt](by-country/HK.txt) |
| Thailand (TH) | 622 | [by-country/TH.txt](by-country/TH.txt) |
| France (FR) | 592 | [by-country/FR.txt](by-country/FR.txt) |
| Germany (DE) | 584 | [by-country/DE.txt](by-country/DE.txt) |
| _+121 more countries_ | | [full by-country/ folder &raquo;](by-country) |

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

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; continuously updated &nbsp;&middot;&nbsp; 2026-07-17 11:09 UTC</sub></p>
