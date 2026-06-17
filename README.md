<p align="center">
  <a href="https://hproxy.com"><img src="assets/banner.svg" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>16,303 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,085 live right now, 329,820+ tracked all-time, updated 17.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 16,303 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,282 | [txt](http.txt) |
| HTTPS | 1,109 | [txt](https.txt) |
| SOCKS4 | 1,776 | [txt](socks4.txt) |
| SOCKS5 | 1,228 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (119 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 5,597 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,754 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,173 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 699 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 590 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 458 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 427 | [by-country/DE.txt](by-country/DE.txt) |
| South Korea (KR) | 394 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 389 | [by-country/AU.txt](by-country/AU.txt) |
| Hong Kong (HK) | 364 | [by-country/HK.txt](by-country/HK.txt) |
| France (FR) | 266 | [by-country/FR.txt](by-country/FR.txt) |
| Thailand (TH) | 254 | [by-country/TH.txt](by-country/TH.txt) |
| Sweden (SE) | 249 | [by-country/SE.txt](by-country/SE.txt) |
| Russia (RU) | 242 | [by-country/RU.txt](by-country/RU.txt) |
| Canada (CA) | 208 | [by-country/CA.txt](by-country/CA.txt) |
| Brazil (BR) | 202 | [by-country/BR.txt](by-country/BR.txt) |
| Philippines (PH) | 201 | [by-country/PH.txt](by-country/PH.txt) |
| Switzerland (CH) | 194 | [by-country/CH.txt](by-country/CH.txt) |
| United Kingdom (GB) | 173 | [by-country/GB.txt](by-country/GB.txt) |
| Mexico (MX) | 170 | [by-country/MX.txt](by-country/MX.txt) |
| Singapore (SG) | 170 | [by-country/SG.txt](by-country/SG.txt) |
| Bangladesh (BD) | 163 | [by-country/BD.txt](by-country/BD.txt) |
| South Africa (ZA) | 161 | [by-country/ZA.txt](by-country/ZA.txt) |
| Colombia (CO) | 146 | [by-country/CO.txt](by-country/CO.txt) |
| Italy (IT) | 126 | [by-country/IT.txt](by-country/IT.txt) |
| Ireland (IE) | 117 | [by-country/IE.txt](by-country/IE.txt) |
| Vietnam (VN) | 109 | [by-country/VN.txt](by-country/VN.txt) |
| Netherlands (NL) | 98 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 87 | [by-country/MY.txt](by-country/MY.txt) |
| Turkey (TR) | 72 | [by-country/TR.txt](by-country/TR.txt) |
| Ecuador (EC) | 71 | [by-country/EC.txt](by-country/EC.txt) |
| Venezuela (VE) | 68 | [by-country/VE.txt](by-country/VE.txt) |
| United Arab Emirates (AE) | 67 | [by-country/AE.txt](by-country/AE.txt) |
| Spain (ES) | 65 | [by-country/ES.txt](by-country/ES.txt) |
| Argentina (AR) | 58 | [by-country/AR.txt](by-country/AR.txt) |
| Israel (IL) | 56 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 50 | [by-country/KH.txt](by-country/KH.txt) |
| Finland (FI) | 41 | [by-country/FI.txt](by-country/FI.txt) |
| Ukraine (UA) | 39 | [by-country/UA.txt](by-country/UA.txt) |
| Poland (PL) | 37 | [by-country/PL.txt](by-country/PL.txt) |
| Peru (PE) | 34 | [by-country/PE.txt](by-country/PE.txt) |
| DO (DO) | 29 | [by-country/DO.txt](by-country/DO.txt) |
| BG (BG) | 24 | [by-country/BG.txt](by-country/BG.txt) |
| Chile (CL) | 24 | [by-country/CL.txt](by-country/CL.txt) |
| Pakistan (PK) | 22 | [by-country/PK.txt](by-country/PK.txt) |
| Egypt (EG) | 21 | [by-country/EG.txt](by-country/EG.txt) |
| Georgia (GE) | 20 | [by-country/GE.txt](by-country/GE.txt) |
| Kenya (KE) | 20 | [by-country/KE.txt](by-country/KE.txt) |
| Paraguay (PY) | 19 | [by-country/PY.txt](by-country/PY.txt) |
| Kazakhstan (KZ) | 17 | [by-country/KZ.txt](by-country/KZ.txt) |
| Taiwan (TW) | 15 | [by-country/TW.txt](by-country/TW.txt) |
| LY (LY) | 15 | [by-country/LY.txt](by-country/LY.txt) |
| Nepal (NP) | 14 | [by-country/NP.txt](by-country/NP.txt) |
| Czechia (CZ) | 11 | [by-country/CZ.txt](by-country/CZ.txt) |
| HN (HN) | 10 | [by-country/HN.txt](by-country/HN.txt) |
| Austria (AT) | 9 | [by-country/AT.txt](by-country/AT.txt) |
| Romania (RO) | 8 | [by-country/RO.txt](by-country/RO.txt) |
| PR (PR) | 8 | [by-country/PR.txt](by-country/PR.txt) |
| AL (AL) | 8 | [by-country/AL.txt](by-country/AL.txt) |
| GT (GT) | 8 | [by-country/GT.txt](by-country/GT.txt) |
| Hungary (HU) | 8 | [by-country/HU.txt](by-country/HU.txt) |
| EE (EE) | 7 | [by-country/EE.txt](by-country/EE.txt) |
| IQ (IQ) | 7 | [by-country/IQ.txt](by-country/IQ.txt) |
| Nigeria (NG) | 7 | [by-country/NG.txt](by-country/NG.txt) |
| GH (GH) | 6 | [by-country/GH.txt](by-country/GH.txt) |
| XK (XK) | 6 | [by-country/XK.txt](by-country/XK.txt) |
| RS (RS) | 5 | [by-country/RS.txt](by-country/RS.txt) |
| LV (LV) | 5 | [by-country/LV.txt](by-country/LV.txt) |
| BO (BO) | 5 | [by-country/BO.txt](by-country/BO.txt) |
| UZ (UZ) | 5 | [by-country/UZ.txt](by-country/UZ.txt) |
| PS (PS) | 5 | [by-country/PS.txt](by-country/PS.txt) |
| SN (SN) | 4 | [by-country/SN.txt](by-country/SN.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| AM (AM) | 4 | [by-country/AM.txt](by-country/AM.txt) |
| BW (BW) | 4 | [by-country/BW.txt](by-country/BW.txt) |
| QA (QA) | 3 | [by-country/QA.txt](by-country/QA.txt) |
| TZ (TZ) | 3 | [by-country/TZ.txt](by-country/TZ.txt) |
| Greece (GR) | 3 | [by-country/GR.txt](by-country/GR.txt) |
| CG (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| SY (SY) | 3 | [by-country/SY.txt](by-country/SY.txt) |
| CD (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| SC (SC) | 3 | [by-country/SC.txt](by-country/SC.txt) |
| HR (HR) | 3 | [by-country/HR.txt](by-country/HR.txt) |
| RW (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| Belgium (BE) | 2 | [by-country/BE.txt](by-country/BE.txt) |
| Saudi Arabia (SA) | 2 | [by-country/SA.txt](by-country/SA.txt) |
| CY (CY) | 2 | [by-country/CY.txt](by-country/CY.txt) |
| PA (PA) | 2 | [by-country/PA.txt](by-country/PA.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| MD (MD) | 2 | [by-country/MD.txt](by-country/MD.txt) |
| MN (MN) | 2 | [by-country/MN.txt](by-country/MN.txt) |
| MT (MT) | 2 | [by-country/MT.txt](by-country/MT.txt) |
| ME (ME) | 2 | [by-country/ME.txt](by-country/ME.txt) |
| AZ (AZ) | 2 | [by-country/AZ.txt](by-country/AZ.txt) |
| LT (LT) | 2 | [by-country/LT.txt](by-country/LT.txt) |
| LA (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| BF (BF) | 2 | [by-country/BF.txt](by-country/BF.txt) |
| MO (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| SV (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| UG (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |
| LB (LB) | 1 | [by-country/LB.txt](by-country/LB.txt) |
| BI (BI) | 1 | [by-country/BI.txt](by-country/BI.txt) |
| LS (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| AF (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| MW (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| BA (BA) | 1 | [by-country/BA.txt](by-country/BA.txt) |
| LK (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| WS (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| TM (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| Norway (NO) | 1 | [by-country/NO.txt](by-country/NO.txt) |
| CR (CR) | 1 | [by-country/CR.txt](by-country/CR.txt) |
| BT (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| MM (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| UY (UY) | 1 | [by-country/UY.txt](by-country/UY.txt) |
| AO (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |
| GQ (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| JM (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
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

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-17 07:07 UTC</sub></p>
