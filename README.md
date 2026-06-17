<p align="center">
  <a href="https://hproxy.com"><img src="assets/banner.svg" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>13,759 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 2,644 live right now, 363,807+ tracked all-time, updated 17.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 13,759 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 1,675 | [txt](http.txt) |
| HTTPS | 903 | [txt](https.txt) |
| SOCKS4 | 1,415 | [txt](socks4.txt) |
| SOCKS5 | 1,278 | [txt](socks5.txt) |

Text files are one `ip:port` per line. `all.json` and `all.csv` add protocol, anonymity, country, city, latency and uptime per proxy.

## Use as an API

Every file is a raw endpoint, refreshed hourly. Pull via GitHub raw or the jsDelivr CDN (faster, no rate limits):

```bash
# all proxies, three formats
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.txt
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/all.json
curl https://cdn.jsdelivr.net/gh/hproxy-com/free-proxy-list@main/all.csv
# filter by protocol or country
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/socks5.txt
curl https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/by-country/US.txt
```

**Want real-time results with filters?** The files above are hourly snapshots. The live API at `https://hproxy.com/api/proxy-list` filters the current pool by country, protocol and anonymity:

```bash
curl "https://hproxy.com/api/proxy-list?format=json&country=US&protocol=socks5&anonymity=elite"
```

Full API docs: **https://hproxy.com/docs**

<details>
<summary><b>Free proxies by country</b> (114 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 4,543 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,631 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 913 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 609 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 488 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 414 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 370 | [by-country/DE.txt](by-country/DE.txt) |
| Australia (AU) | 344 | [by-country/AU.txt](by-country/AU.txt) |
| South Korea (KR) | 340 | [by-country/KR.txt](by-country/KR.txt) |
| Hong Kong (HK) | 323 | [by-country/HK.txt](by-country/HK.txt) |
| France (FR) | 238 | [by-country/FR.txt](by-country/FR.txt) |
| Russia (RU) | 209 | [by-country/RU.txt](by-country/RU.txt) |
| Thailand (TH) | 207 | [by-country/TH.txt](by-country/TH.txt) |
| Sweden (SE) | 201 | [by-country/SE.txt](by-country/SE.txt) |
| Canada (CA) | 178 | [by-country/CA.txt](by-country/CA.txt) |
| Brazil (BR) | 172 | [by-country/BR.txt](by-country/BR.txt) |
| Switzerland (CH) | 171 | [by-country/CH.txt](by-country/CH.txt) |
| Philippines (PH) | 168 | [by-country/PH.txt](by-country/PH.txt) |
| United Kingdom (GB) | 156 | [by-country/GB.txt](by-country/GB.txt) |
| South Africa (ZA) | 148 | [by-country/ZA.txt](by-country/ZA.txt) |
| Singapore (SG) | 148 | [by-country/SG.txt](by-country/SG.txt) |
| Mexico (MX) | 138 | [by-country/MX.txt](by-country/MX.txt) |
| Bangladesh (BD) | 136 | [by-country/BD.txt](by-country/BD.txt) |
| Colombia (CO) | 117 | [by-country/CO.txt](by-country/CO.txt) |
| Ireland (IE) | 109 | [by-country/IE.txt](by-country/IE.txt) |
| Italy (IT) | 106 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 91 | [by-country/VN.txt](by-country/VN.txt) |
| Netherlands (NL) | 88 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 72 | [by-country/MY.txt](by-country/MY.txt) |
| United Arab Emirates (AE) | 63 | [by-country/AE.txt](by-country/AE.txt) |
| Turkey (TR) | 59 | [by-country/TR.txt](by-country/TR.txt) |
| Ecuador (EC) | 57 | [by-country/EC.txt](by-country/EC.txt) |
| Venezuela (VE) | 54 | [by-country/VE.txt](by-country/VE.txt) |
| Spain (ES) | 52 | [by-country/ES.txt](by-country/ES.txt) |
| Israel (IL) | 50 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 45 | [by-country/KH.txt](by-country/KH.txt) |
| Argentina (AR) | 43 | [by-country/AR.txt](by-country/AR.txt) |
| Finland (FI) | 38 | [by-country/FI.txt](by-country/FI.txt) |
| Poland (PL) | 33 | [by-country/PL.txt](by-country/PL.txt) |
| Ukraine (UA) | 29 | [by-country/UA.txt](by-country/UA.txt) |
| Peru (PE) | 27 | [by-country/PE.txt](by-country/PE.txt) |
| Chile (CL) | 23 | [by-country/CL.txt](by-country/CL.txt) |
| Egypt (EG) | 20 | [by-country/EG.txt](by-country/EG.txt) |
| DO (DO) | 20 | [by-country/DO.txt](by-country/DO.txt) |
| Pakistan (PK) | 19 | [by-country/PK.txt](by-country/PK.txt) |
| BG (BG) | 19 | [by-country/BG.txt](by-country/BG.txt) |
| Georgia (GE) | 16 | [by-country/GE.txt](by-country/GE.txt) |
| Kazakhstan (KZ) | 16 | [by-country/KZ.txt](by-country/KZ.txt) |
| Kenya (KE) | 16 | [by-country/KE.txt](by-country/KE.txt) |
| LY (LY) | 15 | [by-country/LY.txt](by-country/LY.txt) |
| Taiwan (TW) | 14 | [by-country/TW.txt](by-country/TW.txt) |
| Paraguay (PY) | 14 | [by-country/PY.txt](by-country/PY.txt) |
| Nepal (NP) | 13 | [by-country/NP.txt](by-country/NP.txt) |
| HN (HN) | 10 | [by-country/HN.txt](by-country/HN.txt) |
| Austria (AT) | 9 | [by-country/AT.txt](by-country/AT.txt) |
| Czechia (CZ) | 8 | [by-country/CZ.txt](by-country/CZ.txt) |
| EE (EE) | 7 | [by-country/EE.txt](by-country/EE.txt) |
| Hungary (HU) | 7 | [by-country/HU.txt](by-country/HU.txt) |
| IQ (IQ) | 6 | [by-country/IQ.txt](by-country/IQ.txt) |
| Romania (RO) | 6 | [by-country/RO.txt](by-country/RO.txt) |
| Nigeria (NG) | 6 | [by-country/NG.txt](by-country/NG.txt) |
| UZ (UZ) | 5 | [by-country/UZ.txt](by-country/UZ.txt) |
| GT (GT) | 5 | [by-country/GT.txt](by-country/GT.txt) |
| PR (PR) | 5 | [by-country/PR.txt](by-country/PR.txt) |
| AL (AL) | 5 | [by-country/AL.txt](by-country/AL.txt) |
| GH (GH) | 5 | [by-country/GH.txt](by-country/GH.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| BW (BW) | 4 | [by-country/BW.txt](by-country/BW.txt) |
| LV (LV) | 4 | [by-country/LV.txt](by-country/LV.txt) |
| RS (RS) | 4 | [by-country/RS.txt](by-country/RS.txt) |
| PS (PS) | 4 | [by-country/PS.txt](by-country/PS.txt) |
| XK (XK) | 4 | [by-country/XK.txt](by-country/XK.txt) |
| AM (AM) | 4 | [by-country/AM.txt](by-country/AM.txt) |
| SN (SN) | 3 | [by-country/SN.txt](by-country/SN.txt) |
| BO (BO) | 3 | [by-country/BO.txt](by-country/BO.txt) |
| Greece (GR) | 3 | [by-country/GR.txt](by-country/GR.txt) |
| TZ (TZ) | 3 | [by-country/TZ.txt](by-country/TZ.txt) |
| QA (QA) | 3 | [by-country/QA.txt](by-country/QA.txt) |
| Belgium (BE) | 2 | [by-country/BE.txt](by-country/BE.txt) |
| MD (MD) | 2 | [by-country/MD.txt](by-country/MD.txt) |
| ME (ME) | 2 | [by-country/ME.txt](by-country/ME.txt) |
| LA (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| CG (CG) | 2 | [by-country/CG.txt](by-country/CG.txt) |
| SY (SY) | 2 | [by-country/SY.txt](by-country/SY.txt) |
| Saudi Arabia (SA) | 2 | [by-country/SA.txt](by-country/SA.txt) |
| PA (PA) | 2 | [by-country/PA.txt](by-country/PA.txt) |
| Norway (NO) | 1 | [by-country/NO.txt](by-country/NO.txt) |
| Portugal (PT) | 1 | [by-country/PT.txt](by-country/PT.txt) |
| TM (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| RW (RW) | 1 | [by-country/RW.txt](by-country/RW.txt) |
| CY (CY) | 1 | [by-country/CY.txt](by-country/CY.txt) |
| BI (BI) | 1 | [by-country/BI.txt](by-country/BI.txt) |
| LS (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| MT (MT) | 1 | [by-country/MT.txt](by-country/MT.txt) |
| MO (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| AF (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| GQ (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| UY (UY) | 1 | [by-country/UY.txt](by-country/UY.txt) |
| MW (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| BA (BA) | 1 | [by-country/BA.txt](by-country/BA.txt) |
| WS (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| CR (CR) | 1 | [by-country/CR.txt](by-country/CR.txt) |
| LT (LT) | 1 | [by-country/LT.txt](by-country/LT.txt) |
| CD (CD) | 1 | [by-country/CD.txt](by-country/CD.txt) |
| LK (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| SC (SC) | 1 | [by-country/SC.txt](by-country/SC.txt) |
| MM (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| BF (BF) | 1 | [by-country/BF.txt](by-country/BF.txt) |
| HR (HR) | 1 | [by-country/HR.txt](by-country/HR.txt) |
| AO (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |
| LB (LB) | 1 | [by-country/LB.txt](by-country/LB.txt) |
| UG (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |
| KG (KG) | 1 | [by-country/KG.txt](by-country/KG.txt) |
| YE (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-17 01:07 UTC</sub></p>
