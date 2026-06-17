<p align="center">
  <a href="https://hproxy.com"><img src="assets/banner.svg" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>17,702 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,605 live right now, 181,309+ tracked all-time, updated 17.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 17,702 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,539 | [txt](http.txt) |
| HTTPS | 1,300 | [txt](https.txt) |
| SOCKS4 | 1,803 | [txt](socks4.txt) |
| SOCKS5 | 1,435 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (127 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 5,881 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,785 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,376 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 785 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 609 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 503 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 477 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 415 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 412 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 404 | [by-country/AU.txt](by-country/AU.txt) |
| France (FR) | 289 | [by-country/FR.txt](by-country/FR.txt) |
| Russia (RU) | 286 | [by-country/RU.txt](by-country/RU.txt) |
| Thailand (TH) | 275 | [by-country/TH.txt](by-country/TH.txt) |
| Sweden (SE) | 270 | [by-country/SE.txt](by-country/SE.txt) |
| Canada (CA) | 240 | [by-country/CA.txt](by-country/CA.txt) |
| Brazil (BR) | 237 | [by-country/BR.txt](by-country/BR.txt) |
| Philippines (PH) | 233 | [by-country/PH.txt](by-country/PH.txt) |
| Singapore (SG) | 206 | [by-country/SG.txt](by-country/SG.txt) |
| Switzerland (CH) | 199 | [by-country/CH.txt](by-country/CH.txt) |
| Mexico (MX) | 189 | [by-country/MX.txt](by-country/MX.txt) |
| United Kingdom (GB) | 182 | [by-country/GB.txt](by-country/GB.txt) |
| Bangladesh (BD) | 177 | [by-country/BD.txt](by-country/BD.txt) |
| Colombia (CO) | 174 | [by-country/CO.txt](by-country/CO.txt) |
| South Africa (ZA) | 162 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 145 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 119 | [by-country/VN.txt](by-country/VN.txt) |
| Ireland (IE) | 113 | [by-country/IE.txt](by-country/IE.txt) |
| Netherlands (NL) | 108 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 101 | [by-country/MY.txt](by-country/MY.txt) |
| Venezuela (VE) | 85 | [by-country/VE.txt](by-country/VE.txt) |
| Turkey (TR) | 83 | [by-country/TR.txt](by-country/TR.txt) |
| Spain (ES) | 78 | [by-country/ES.txt](by-country/ES.txt) |
| United Arab Emirates (AE) | 78 | [by-country/AE.txt](by-country/AE.txt) |
| Ecuador (EC) | 78 | [by-country/EC.txt](by-country/EC.txt) |
| Argentina (AR) | 66 | [by-country/AR.txt](by-country/AR.txt) |
| Israel (IL) | 65 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 55 | [by-country/KH.txt](by-country/KH.txt) |
| Peru (PE) | 48 | [by-country/PE.txt](by-country/PE.txt) |
| Finland (FI) | 43 | [by-country/FI.txt](by-country/FI.txt) |
| Poland (PL) | 41 | [by-country/PL.txt](by-country/PL.txt) |
| DO (DO) | 40 | [by-country/DO.txt](by-country/DO.txt) |
| Ukraine (UA) | 36 | [by-country/UA.txt](by-country/UA.txt) |
| Chile (CL) | 34 | [by-country/CL.txt](by-country/CL.txt) |
| Pakistan (PK) | 30 | [by-country/PK.txt](by-country/PK.txt) |
| BG (BG) | 27 | [by-country/BG.txt](by-country/BG.txt) |
| Kenya (KE) | 26 | [by-country/KE.txt](by-country/KE.txt) |
| Taiwan (TW) | 24 | [by-country/TW.txt](by-country/TW.txt) |
| Paraguay (PY) | 24 | [by-country/PY.txt](by-country/PY.txt) |
| LY (LY) | 23 | [by-country/LY.txt](by-country/LY.txt) |
| Kazakhstan (KZ) | 22 | [by-country/KZ.txt](by-country/KZ.txt) |
| Egypt (EG) | 20 | [by-country/EG.txt](by-country/EG.txt) |
| Georgia (GE) | 18 | [by-country/GE.txt](by-country/GE.txt) |
| Nepal (NP) | 17 | [by-country/NP.txt](by-country/NP.txt) |
| Hungary (HU) | 15 | [by-country/HU.txt](by-country/HU.txt) |
| GT (GT) | 15 | [by-country/GT.txt](by-country/GT.txt) |
| HN (HN) | 13 | [by-country/HN.txt](by-country/HN.txt) |
| Czechia (CZ) | 12 | [by-country/CZ.txt](by-country/CZ.txt) |
| PR (PR) | 12 | [by-country/PR.txt](by-country/PR.txt) |
| Austria (AT) | 11 | [by-country/AT.txt](by-country/AT.txt) |
| AL (AL) | 11 | [by-country/AL.txt](by-country/AL.txt) |
| Romania (RO) | 10 | [by-country/RO.txt](by-country/RO.txt) |
| EE (EE) | 9 | [by-country/EE.txt](by-country/EE.txt) |
| LV (LV) | 8 | [by-country/LV.txt](by-country/LV.txt) |
| UZ (UZ) | 8 | [by-country/UZ.txt](by-country/UZ.txt) |
| IQ (IQ) | 8 | [by-country/IQ.txt](by-country/IQ.txt) |
| SY (SY) | 7 | [by-country/SY.txt](by-country/SY.txt) |
| PA (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| GH (GH) | 6 | [by-country/GH.txt](by-country/GH.txt) |
| RS (RS) | 6 | [by-country/RS.txt](by-country/RS.txt) |
| BW (BW) | 5 | [by-country/BW.txt](by-country/BW.txt) |
| SC (SC) | 5 | [by-country/SC.txt](by-country/SC.txt) |
| Nigeria (NG) | 5 | [by-country/NG.txt](by-country/NG.txt) |
| BO (BO) | 5 | [by-country/BO.txt](by-country/BO.txt) |
| SN (SN) | 4 | [by-country/SN.txt](by-country/SN.txt) |
| PS (PS) | 4 | [by-country/PS.txt](by-country/PS.txt) |
| CR (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| XK (XK) | 4 | [by-country/XK.txt](by-country/XK.txt) |
| AM (AM) | 4 | [by-country/AM.txt](by-country/AM.txt) |
| MN (MN) | 4 | [by-country/MN.txt](by-country/MN.txt) |
| HR (HR) | 4 | [by-country/HR.txt](by-country/HR.txt) |
| Belgium (BE) | 3 | [by-country/BE.txt](by-country/BE.txt) |
| AZ (AZ) | 3 | [by-country/AZ.txt](by-country/AZ.txt) |
| CY (CY) | 3 | [by-country/CY.txt](by-country/CY.txt) |
| MD (MD) | 3 | [by-country/MD.txt](by-country/MD.txt) |
| Greece (GR) | 3 | [by-country/GR.txt](by-country/GR.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| CG (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| TZ (TZ) | 3 | [by-country/TZ.txt](by-country/TZ.txt) |
| CD (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| RW (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| UY (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| QA (QA) | 2 | [by-country/QA.txt](by-country/QA.txt) |
| LB (LB) | 2 | [by-country/LB.txt](by-country/LB.txt) |
| Norway (NO) | 2 | [by-country/NO.txt](by-country/NO.txt) |
| KG (KG) | 2 | [by-country/KG.txt](by-country/KG.txt) |
| ME (ME) | 2 | [by-country/ME.txt](by-country/ME.txt) |
| BA (BA) | 2 | [by-country/BA.txt](by-country/BA.txt) |
| LA (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| BF (BF) | 2 | [by-country/BF.txt](by-country/BF.txt) |
| TM (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| BI (BI) | 1 | [by-country/BI.txt](by-country/BI.txt) |
| MM (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| GQ (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| AO (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| JM (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
| MV (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| OM (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| YE (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |
| AF (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| MO (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| LK (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| LS (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| MT (MT) | 1 | [by-country/MT.txt](by-country/MT.txt) |
| CM (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| GM (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| MW (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| WS (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| LT (LT) | 1 | [by-country/LT.txt](by-country/LT.txt) |
| BT (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| GA (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| SV (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| NZ (NZ) | 1 | [by-country/NZ.txt](by-country/NZ.txt) |
| SK (SK) | 1 | [by-country/SK.txt](by-country/SK.txt) |
| UG (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-17 23:07 UTC</sub></p>
