<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1781813224" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>22,718 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,181 live right now, 295,546+ tracked all-time, updated 18.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 22,718 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,255 | [txt](http.txt) |
| HTTPS | 949 | [txt](https.txt) |
| SOCKS4 | 1,353 | [txt](socks4.txt) |
| SOCKS5 | 1,121 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (132 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 7,401 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 2,136 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,906 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 1,129 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 778 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 660 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 583 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 519 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 507 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 446 | [by-country/AU.txt](by-country/AU.txt) |
| Russia (RU) | 396 | [by-country/RU.txt](by-country/RU.txt) |
| Thailand (TH) | 360 | [by-country/TH.txt](by-country/TH.txt) |
| France (FR) | 347 | [by-country/FR.txt](by-country/FR.txt) |
| Philippines (PH) | 332 | [by-country/PH.txt](by-country/PH.txt) |
| Singapore (SG) | 303 | [by-country/SG.txt](by-country/SG.txt) |
| Canada (CA) | 297 | [by-country/CA.txt](by-country/CA.txt) |
| Brazil (BR) | 297 | [by-country/BR.txt](by-country/BR.txt) |
| Sweden (SE) | 286 | [by-country/SE.txt](by-country/SE.txt) |
| Mexico (MX) | 255 | [by-country/MX.txt](by-country/MX.txt) |
| Colombia (CO) | 250 | [by-country/CO.txt](by-country/CO.txt) |
| United Kingdom (GB) | 249 | [by-country/GB.txt](by-country/GB.txt) |
| Bangladesh (BD) | 244 | [by-country/BD.txt](by-country/BD.txt) |
| Switzerland (CH) | 218 | [by-country/CH.txt](by-country/CH.txt) |
| South Africa (ZA) | 198 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 174 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 157 | [by-country/VN.txt](by-country/VN.txt) |
| Netherlands (NL) | 147 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 141 | [by-country/MY.txt](by-country/MY.txt) |
| Ireland (IE) | 136 | [by-country/IE.txt](by-country/IE.txt) |
| Turkey (TR) | 119 | [by-country/TR.txt](by-country/TR.txt) |
| United Arab Emirates (AE) | 114 | [by-country/AE.txt](by-country/AE.txt) |
| Venezuela (VE) | 110 | [by-country/VE.txt](by-country/VE.txt) |
| Ecuador (EC) | 104 | [by-country/EC.txt](by-country/EC.txt) |
| Spain (ES) | 93 | [by-country/ES.txt](by-country/ES.txt) |
| Argentina (AR) | 93 | [by-country/AR.txt](by-country/AR.txt) |
| Cambodia (KH) | 83 | [by-country/KH.txt](by-country/KH.txt) |
| Israel (IL) | 71 | [by-country/IL.txt](by-country/IL.txt) |
| Peru (PE) | 65 | [by-country/PE.txt](by-country/PE.txt) |
| Ukraine (UA) | 62 | [by-country/UA.txt](by-country/UA.txt) |
| Chile (CL) | 57 | [by-country/CL.txt](by-country/CL.txt) |
| Finland (FI) | 56 | [by-country/FI.txt](by-country/FI.txt) |
| Dominican Republic (DO) | 56 | [by-country/DO.txt](by-country/DO.txt) |
| Poland (PL) | 51 | [by-country/PL.txt](by-country/PL.txt) |
| Bulgaria (BG) | 39 | [by-country/BG.txt](by-country/BG.txt) |
| Pakistan (PK) | 38 | [by-country/PK.txt](by-country/PK.txt) |
| Egypt (EG) | 38 | [by-country/EG.txt](by-country/EG.txt) |
| Taiwan (TW) | 32 | [by-country/TW.txt](by-country/TW.txt) |
| Kazakhstan (KZ) | 30 | [by-country/KZ.txt](by-country/KZ.txt) |
| Libya (LY) | 29 | [by-country/LY.txt](by-country/LY.txt) |
| Kenya (KE) | 28 | [by-country/KE.txt](by-country/KE.txt) |
| Paraguay (PY) | 28 | [by-country/PY.txt](by-country/PY.txt) |
| Georgia (GE) | 26 | [by-country/GE.txt](by-country/GE.txt) |
| Nepal (NP) | 24 | [by-country/NP.txt](by-country/NP.txt) |
| Guatemala (GT) | 22 | [by-country/GT.txt](by-country/GT.txt) |
| Hungary (HU) | 19 | [by-country/HU.txt](by-country/HU.txt) |
| Puerto Rico (PR) | 16 | [by-country/PR.txt](by-country/PR.txt) |
| Iraq (IQ) | 16 | [by-country/IQ.txt](by-country/IQ.txt) |
| Czechia (CZ) | 15 | [by-country/CZ.txt](by-country/CZ.txt) |
| Albania (AL) | 14 | [by-country/AL.txt](by-country/AL.txt) |
| British Virgin Islands (VG) | 13 | [by-country/VG.txt](by-country/VG.txt) |
| Nigeria (NG) | 13 | [by-country/NG.txt](by-country/NG.txt) |
| Austria (AT) | 12 | [by-country/AT.txt](by-country/AT.txt) |
| Seychelles (SC) | 12 | [by-country/SC.txt](by-country/SC.txt) |
| Syria (SY) | 12 | [by-country/SY.txt](by-country/SY.txt) |
| Honduras (HN) | 12 | [by-country/HN.txt](by-country/HN.txt) |
| Romania (RO) | 11 | [by-country/RO.txt](by-country/RO.txt) |
| Serbia (RS) | 10 | [by-country/RS.txt](by-country/RS.txt) |
| Estonia (EE) | 10 | [by-country/EE.txt](by-country/EE.txt) |
| Uzbekistan (UZ) | 9 | [by-country/UZ.txt](by-country/UZ.txt) |
| Latvia (LV) | 9 | [by-country/LV.txt](by-country/LV.txt) |
| Palestine (PS) | 9 | [by-country/PS.txt](by-country/PS.txt) |
| Kosovo (XK) | 8 | [by-country/XK.txt](by-country/XK.txt) |
| Ghana (GH) | 8 | [by-country/GH.txt](by-country/GH.txt) |
| Armenia (AM) | 7 | [by-country/AM.txt](by-country/AM.txt) |
| Mongolia (MN) | 6 | [by-country/MN.txt](by-country/MN.txt) |
| Croatia (HR) | 6 | [by-country/HR.txt](by-country/HR.txt) |
| Tanzania (TZ) | 6 | [by-country/TZ.txt](by-country/TZ.txt) |
| Panama (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| Lebanon (LB) | 5 | [by-country/LB.txt](by-country/LB.txt) |
| Senegal (SN) | 5 | [by-country/SN.txt](by-country/SN.txt) |
| Bolivia (BO) | 5 | [by-country/BO.txt](by-country/BO.txt) |
| Botswana (BW) | 5 | [by-country/BW.txt](by-country/BW.txt) |
| Greece (GR) | 5 | [by-country/GR.txt](by-country/GR.txt) |
| Belgium (BE) | 4 | [by-country/BE.txt](by-country/BE.txt) |
| Costa Rica (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Cyprus (CY) | 4 | [by-country/CY.txt](by-country/CY.txt) |
| Montenegro (ME) | 4 | [by-country/ME.txt](by-country/ME.txt) |
| Kyrgyzstan (KG) | 4 | [by-country/KG.txt](by-country/KG.txt) |
| Azerbaijan (AZ) | 4 | [by-country/AZ.txt](by-country/AZ.txt) |
| Qatar (QA) | 4 | [by-country/QA.txt](by-country/QA.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| Moldova (MD) | 3 | [by-country/MD.txt](by-country/MD.txt) |
| Norway (NO) | 3 | [by-country/NO.txt](by-country/NO.txt) |
| Slovakia (SK) | 3 | [by-country/SK.txt](by-country/SK.txt) |
| DR Congo (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| Burkina Faso (BF) | 3 | [by-country/BF.txt](by-country/BF.txt) |
| Bosnia and Herzegovina (BA) | 2 | [by-country/BA.txt](by-country/BA.txt) |
| Rwanda (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| Lithuania (LT) | 2 | [by-country/LT.txt](by-country/LT.txt) |
| Malta (MT) | 2 | [by-country/MT.txt](by-country/MT.txt) |
| New Zealand (NZ) | 2 | [by-country/NZ.txt](by-country/NZ.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| Uganda (UG) | 2 | [by-country/UG.txt](by-country/UG.txt) |
| Laos (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| Uruguay (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| North Macedonia (MK) | 1 | [by-country/MK.txt](by-country/MK.txt) |
| Macau (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| Turkmenistan (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| Timor-Leste (TL) | 1 | [by-country/TL.txt](by-country/TL.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| El Salvador (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| Oman (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| Cameroon (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| Maldives (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| Yemen (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |
| Congo (CG) | 1 | [by-country/CG.txt](by-country/CG.txt) |
| Burundi (BI) | 1 | [by-country/BI.txt](by-country/BI.txt) |
| Algeria (DZ) | 1 | [by-country/DZ.txt](by-country/DZ.txt) |
| Slovenia (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| Jamaica (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
| Gambia (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| Malawi (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| Sri Lanka (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| Samoa (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| Equatorial Guinea (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| Lesotho (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| Afghanistan (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| Bhutan (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| Myanmar (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| Gabon (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| Angola (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-18 20:07 UTC</sub></p>
