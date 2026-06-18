<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1781752024" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>19,225 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,858 live right now, 294,863+ tracked all-time, updated 18.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 19,225 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,751 | [txt](http.txt) |
| HTTPS | 1,287 | [txt](https.txt) |
| SOCKS4 | 1,870 | [txt](socks4.txt) |
| SOCKS5 | 1,468 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (128 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 6,236 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,930 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,539 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 913 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 687 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 572 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 514 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 448 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 442 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 422 | [by-country/AU.txt](by-country/AU.txt) |
| Thailand (TH) | 320 | [by-country/TH.txt](by-country/TH.txt) |
| France (FR) | 313 | [by-country/FR.txt](by-country/FR.txt) |
| Russia (RU) | 309 | [by-country/RU.txt](by-country/RU.txt) |
| Sweden (SE) | 277 | [by-country/SE.txt](by-country/SE.txt) |
| Philippines (PH) | 267 | [by-country/PH.txt](by-country/PH.txt) |
| Canada (CA) | 265 | [by-country/CA.txt](by-country/CA.txt) |
| Brazil (BR) | 241 | [by-country/BR.txt](by-country/BR.txt) |
| Singapore (SG) | 239 | [by-country/SG.txt](by-country/SG.txt) |
| Switzerland (CH) | 205 | [by-country/CH.txt](by-country/CH.txt) |
| Mexico (MX) | 201 | [by-country/MX.txt](by-country/MX.txt) |
| United Kingdom (GB) | 200 | [by-country/GB.txt](by-country/GB.txt) |
| Colombia (CO) | 195 | [by-country/CO.txt](by-country/CO.txt) |
| Bangladesh (BD) | 182 | [by-country/BD.txt](by-country/BD.txt) |
| South Africa (ZA) | 181 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 155 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 129 | [by-country/VN.txt](by-country/VN.txt) |
| Netherlands (NL) | 124 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 118 | [by-country/MY.txt](by-country/MY.txt) |
| Ireland (IE) | 113 | [by-country/IE.txt](by-country/IE.txt) |
| United Arab Emirates (AE) | 95 | [by-country/AE.txt](by-country/AE.txt) |
| Venezuela (VE) | 93 | [by-country/VE.txt](by-country/VE.txt) |
| Turkey (TR) | 88 | [by-country/TR.txt](by-country/TR.txt) |
| Ecuador (EC) | 81 | [by-country/EC.txt](by-country/EC.txt) |
| Spain (ES) | 80 | [by-country/ES.txt](by-country/ES.txt) |
| Argentina (AR) | 72 | [by-country/AR.txt](by-country/AR.txt) |
| Israel (IL) | 66 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 63 | [by-country/KH.txt](by-country/KH.txt) |
| Peru (PE) | 52 | [by-country/PE.txt](by-country/PE.txt) |
| Finland (FI) | 48 | [by-country/FI.txt](by-country/FI.txt) |
| Ukraine (UA) | 44 | [by-country/UA.txt](by-country/UA.txt) |
| Dominican Republic (DO) | 44 | [by-country/DO.txt](by-country/DO.txt) |
| Poland (PL) | 42 | [by-country/PL.txt](by-country/PL.txt) |
| Chile (CL) | 40 | [by-country/CL.txt](by-country/CL.txt) |
| Pakistan (PK) | 31 | [by-country/PK.txt](by-country/PK.txt) |
| Bulgaria (BG) | 29 | [by-country/BG.txt](by-country/BG.txt) |
| Kazakhstan (KZ) | 27 | [by-country/KZ.txt](by-country/KZ.txt) |
| Taiwan (TW) | 26 | [by-country/TW.txt](by-country/TW.txt) |
| Paraguay (PY) | 26 | [by-country/PY.txt](by-country/PY.txt) |
| Kenya (KE) | 26 | [by-country/KE.txt](by-country/KE.txt) |
| Libya (LY) | 24 | [by-country/LY.txt](by-country/LY.txt) |
| Georgia (GE) | 22 | [by-country/GE.txt](by-country/GE.txt) |
| Egypt (EG) | 21 | [by-country/EG.txt](by-country/EG.txt) |
| Nepal (NP) | 21 | [by-country/NP.txt](by-country/NP.txt) |
| Hungary (HU) | 15 | [by-country/HU.txt](by-country/HU.txt) |
| Puerto Rico (PR) | 14 | [by-country/PR.txt](by-country/PR.txt) |
| Guatemala (GT) | 14 | [by-country/GT.txt](by-country/GT.txt) |
| British Virgin Islands (VG) | 13 | [by-country/VG.txt](by-country/VG.txt) |
| Czechia (CZ) | 13 | [by-country/CZ.txt](by-country/CZ.txt) |
| Albania (AL) | 13 | [by-country/AL.txt](by-country/AL.txt) |
| Iraq (IQ) | 12 | [by-country/IQ.txt](by-country/IQ.txt) |
| Austria (AT) | 11 | [by-country/AT.txt](by-country/AT.txt) |
| Romania (RO) | 10 | [by-country/RO.txt](by-country/RO.txt) |
| Estonia (EE) | 10 | [by-country/EE.txt](by-country/EE.txt) |
| Honduras (HN) | 10 | [by-country/HN.txt](by-country/HN.txt) |
| Serbia (RS) | 9 | [by-country/RS.txt](by-country/RS.txt) |
| Seychelles (SC) | 9 | [by-country/SC.txt](by-country/SC.txt) |
| Syria (SY) | 9 | [by-country/SY.txt](by-country/SY.txt) |
| Uzbekistan (UZ) | 8 | [by-country/UZ.txt](by-country/UZ.txt) |
| Latvia (LV) | 8 | [by-country/LV.txt](by-country/LV.txt) |
| Kosovo (XK) | 6 | [by-country/XK.txt](by-country/XK.txt) |
| Croatia (HR) | 6 | [by-country/HR.txt](by-country/HR.txt) |
| Panama (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| Nigeria (NG) | 6 | [by-country/NG.txt](by-country/NG.txt) |
| Bolivia (BO) | 5 | [by-country/BO.txt](by-country/BO.txt) |
| Botswana (BW) | 5 | [by-country/BW.txt](by-country/BW.txt) |
| Armenia (AM) | 5 | [by-country/AM.txt](by-country/AM.txt) |
| Mongolia (MN) | 5 | [by-country/MN.txt](by-country/MN.txt) |
| Ghana (GH) | 5 | [by-country/GH.txt](by-country/GH.txt) |
| Senegal (SN) | 4 | [by-country/SN.txt](by-country/SN.txt) |
| Palestine (PS) | 4 | [by-country/PS.txt](by-country/PS.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| Costa Rica (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Greece (GR) | 3 | [by-country/GR.txt](by-country/GR.txt) |
| Belgium (BE) | 3 | [by-country/BE.txt](by-country/BE.txt) |
| Cyprus (CY) | 3 | [by-country/CY.txt](by-country/CY.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| Tanzania (TZ) | 3 | [by-country/TZ.txt](by-country/TZ.txt) |
| Congo (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| DR Congo (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| Qatar (QA) | 3 | [by-country/QA.txt](by-country/QA.txt) |
| Lebanon (LB) | 3 | [by-country/LB.txt](by-country/LB.txt) |
| Azerbaijan (AZ) | 3 | [by-country/AZ.txt](by-country/AZ.txt) |
| Montenegro (ME) | 3 | [by-country/ME.txt](by-country/ME.txt) |
| Burkina Faso (BF) | 3 | [by-country/BF.txt](by-country/BF.txt) |
| Rwanda (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| Kyrgyzstan (KG) | 2 | [by-country/KG.txt](by-country/KG.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| Moldova (MD) | 2 | [by-country/MD.txt](by-country/MD.txt) |
| Norway (NO) | 2 | [by-country/NO.txt](by-country/NO.txt) |
| Laos (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| Bosnia and Herzegovina (BA) | 2 | [by-country/BA.txt](by-country/BA.txt) |
| Uruguay (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| Turkmenistan (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| North Macedonia (MK) | 1 | [by-country/MK.txt](by-country/MK.txt) |
| Timor-Leste (TL) | 1 | [by-country/TL.txt](by-country/TL.txt) |
| Lesotho (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| Uganda (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |
| Macau (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| Malta (MT) | 1 | [by-country/MT.txt](by-country/MT.txt) |
| Cameroon (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| New Zealand (NZ) | 1 | [by-country/NZ.txt](by-country/NZ.txt) |
| Slovenia (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| Equatorial Guinea (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| Maldives (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| Sri Lanka (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| Gambia (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| Malawi (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| Samoa (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| Afghanistan (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| Lithuania (LT) | 1 | [by-country/LT.txt](by-country/LT.txt) |
| Myanmar (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| Bhutan (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| Gabon (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| El Salvador (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| Angola (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |
| Yemen (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |
| Slovakia (SK) | 1 | [by-country/SK.txt](by-country/SK.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-18 03:07 UTC</sub></p>
