<p align="center">
  <a href="https://hproxy.com"><img src="assets/banner.svg" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>18,423 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,513 live right now, 277,470+ tracked all-time, updated 17.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 18,423 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,535 | [txt](http.txt) |
| HTTPS | 1,351 | [txt](https.txt) |
| SOCKS4 | 1,872 | [txt](socks4.txt) |
| SOCKS5 | 1,492 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (126 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 6,110 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,856 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,436 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 818 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 633 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 522 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 494 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 433 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 430 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 420 | [by-country/AU.txt](by-country/AU.txt) |
| Russia (RU) | 301 | [by-country/RU.txt](by-country/RU.txt) |
| France (FR) | 295 | [by-country/FR.txt](by-country/FR.txt) |
| Thailand (TH) | 292 | [by-country/TH.txt](by-country/TH.txt) |
| Sweden (SE) | 261 | [by-country/SE.txt](by-country/SE.txt) |
| Canada (CA) | 248 | [by-country/CA.txt](by-country/CA.txt) |
| Philippines (PH) | 243 | [by-country/PH.txt](by-country/PH.txt) |
| Brazil (BR) | 242 | [by-country/BR.txt](by-country/BR.txt) |
| Singapore (SG) | 218 | [by-country/SG.txt](by-country/SG.txt) |
| Switzerland (CH) | 203 | [by-country/CH.txt](by-country/CH.txt) |
| United Kingdom (GB) | 195 | [by-country/GB.txt](by-country/GB.txt) |
| Mexico (MX) | 190 | [by-country/MX.txt](by-country/MX.txt) |
| Bangladesh (BD) | 187 | [by-country/BD.txt](by-country/BD.txt) |
| Colombia (CO) | 187 | [by-country/CO.txt](by-country/CO.txt) |
| South Africa (ZA) | 173 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 155 | [by-country/IT.txt](by-country/IT.txt) |
| Ireland (IE) | 131 | [by-country/IE.txt](by-country/IE.txt) |
| Vietnam (VN) | 127 | [by-country/VN.txt](by-country/VN.txt) |
| Netherlands (NL) | 117 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 108 | [by-country/MY.txt](by-country/MY.txt) |
| Turkey (TR) | 89 | [by-country/TR.txt](by-country/TR.txt) |
| Venezuela (VE) | 86 | [by-country/VE.txt](by-country/VE.txt) |
| Ecuador (EC) | 82 | [by-country/EC.txt](by-country/EC.txt) |
| Spain (ES) | 78 | [by-country/ES.txt](by-country/ES.txt) |
| United Arab Emirates (AE) | 75 | [by-country/AE.txt](by-country/AE.txt) |
| Argentina (AR) | 70 | [by-country/AR.txt](by-country/AR.txt) |
| Israel (IL) | 68 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 63 | [by-country/KH.txt](by-country/KH.txt) |
| Peru (PE) | 49 | [by-country/PE.txt](by-country/PE.txt) |
| Finland (FI) | 45 | [by-country/FI.txt](by-country/FI.txt) |
| DO (DO) | 42 | [by-country/DO.txt](by-country/DO.txt) |
| Poland (PL) | 40 | [by-country/PL.txt](by-country/PL.txt) |
| Ukraine (UA) | 39 | [by-country/UA.txt](by-country/UA.txt) |
| Pakistan (PK) | 31 | [by-country/PK.txt](by-country/PK.txt) |
| Chile (CL) | 29 | [by-country/CL.txt](by-country/CL.txt) |
| Taiwan (TW) | 25 | [by-country/TW.txt](by-country/TW.txt) |
| BG (BG) | 25 | [by-country/BG.txt](by-country/BG.txt) |
| Kenya (KE) | 24 | [by-country/KE.txt](by-country/KE.txt) |
| Paraguay (PY) | 24 | [by-country/PY.txt](by-country/PY.txt) |
| Egypt (EG) | 24 | [by-country/EG.txt](by-country/EG.txt) |
| Kazakhstan (KZ) | 23 | [by-country/KZ.txt](by-country/KZ.txt) |
| LY (LY) | 22 | [by-country/LY.txt](by-country/LY.txt) |
| Georgia (GE) | 21 | [by-country/GE.txt](by-country/GE.txt) |
| Nepal (NP) | 18 | [by-country/NP.txt](by-country/NP.txt) |
| Hungary (HU) | 15 | [by-country/HU.txt](by-country/HU.txt) |
| Czechia (CZ) | 14 | [by-country/CZ.txt](by-country/CZ.txt) |
| HN (HN) | 14 | [by-country/HN.txt](by-country/HN.txt) |
| GT (GT) | 13 | [by-country/GT.txt](by-country/GT.txt) |
| PR (PR) | 12 | [by-country/PR.txt](by-country/PR.txt) |
| AL (AL) | 11 | [by-country/AL.txt](by-country/AL.txt) |
| Austria (AT) | 10 | [by-country/AT.txt](by-country/AT.txt) |
| EE (EE) | 10 | [by-country/EE.txt](by-country/EE.txt) |
| Romania (RO) | 10 | [by-country/RO.txt](by-country/RO.txt) |
| LV (LV) | 8 | [by-country/LV.txt](by-country/LV.txt) |
| RS (RS) | 8 | [by-country/RS.txt](by-country/RS.txt) |
| UZ (UZ) | 8 | [by-country/UZ.txt](by-country/UZ.txt) |
| SY (SY) | 8 | [by-country/SY.txt](by-country/SY.txt) |
| Nigeria (NG) | 7 | [by-country/NG.txt](by-country/NG.txt) |
| IQ (IQ) | 7 | [by-country/IQ.txt](by-country/IQ.txt) |
| BO (BO) | 6 | [by-country/BO.txt](by-country/BO.txt) |
| GH (GH) | 6 | [by-country/GH.txt](by-country/GH.txt) |
| PA (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| XK (XK) | 5 | [by-country/XK.txt](by-country/XK.txt) |
| AM (AM) | 5 | [by-country/AM.txt](by-country/AM.txt) |
| PS (PS) | 5 | [by-country/PS.txt](by-country/PS.txt) |
| SC (SC) | 5 | [by-country/SC.txt](by-country/SC.txt) |
| SN (SN) | 4 | [by-country/SN.txt](by-country/SN.txt) |
| CR (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| CY (CY) | 4 | [by-country/CY.txt](by-country/CY.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| MN (MN) | 4 | [by-country/MN.txt](by-country/MN.txt) |
| TZ (TZ) | 4 | [by-country/TZ.txt](by-country/TZ.txt) |
| BW (BW) | 4 | [by-country/BW.txt](by-country/BW.txt) |
| Belgium (BE) | 3 | [by-country/BE.txt](by-country/BE.txt) |
| HR (HR) | 3 | [by-country/HR.txt](by-country/HR.txt) |
| CG (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| LB (LB) | 3 | [by-country/LB.txt](by-country/LB.txt) |
| Greece (GR) | 3 | [by-country/GR.txt](by-country/GR.txt) |
| CD (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| AZ (AZ) | 3 | [by-country/AZ.txt](by-country/AZ.txt) |
| RW (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| BA (BA) | 2 | [by-country/BA.txt](by-country/BA.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| MD (MD) | 2 | [by-country/MD.txt](by-country/MD.txt) |
| KG (KG) | 2 | [by-country/KG.txt](by-country/KG.txt) |
| Norway (NO) | 2 | [by-country/NO.txt](by-country/NO.txt) |
| QA (QA) | 2 | [by-country/QA.txt](by-country/QA.txt) |
| LT (LT) | 2 | [by-country/LT.txt](by-country/LT.txt) |
| ME (ME) | 2 | [by-country/ME.txt](by-country/ME.txt) |
| LA (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| BF (BF) | 2 | [by-country/BF.txt](by-country/BF.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| TM (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| LK (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| MT (MT) | 1 | [by-country/MT.txt](by-country/MT.txt) |
| SV (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| UG (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |
| NZ (NZ) | 1 | [by-country/NZ.txt](by-country/NZ.txt) |
| MV (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| MO (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| YE (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |
| AF (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| JM (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
| LS (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| OM (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| CM (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| SK (SK) | 1 | [by-country/SK.txt](by-country/SK.txt) |
| SI (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| GM (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| MW (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| WS (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| MM (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| BT (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| GA (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| UY (UY) | 1 | [by-country/UY.txt](by-country/UY.txt) |
| AO (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-17 22:07 UTC</sub></p>
