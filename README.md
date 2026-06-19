<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1781896024" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>23,854 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,347 live right now, 292,946+ tracked all-time, updated 19.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 23,854 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,412 | [txt](http.txt) |
| HTTPS | 1,037 | [txt](https.txt) |
| SOCKS4 | 1,315 | [txt](socks4.txt) |
| SOCKS5 | 1,143 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (131 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 7,645 | [by-country/IR.txt](by-country/IR.txt) |
| Indonesia (ID) | 2,284 | [by-country/ID.txt](by-country/ID.txt) |
| United States (US) | 1,610 | [by-country/US.txt](by-country/US.txt) |
| China (CN) | 1,258 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 842 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 695 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 650 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 558 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 555 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 454 | [by-country/AU.txt](by-country/AU.txt) |
| Russia (RU) | 443 | [by-country/RU.txt](by-country/RU.txt) |
| Thailand (TH) | 403 | [by-country/TH.txt](by-country/TH.txt) |
| Philippines (PH) | 379 | [by-country/PH.txt](by-country/PH.txt) |
| France (FR) | 359 | [by-country/FR.txt](by-country/FR.txt) |
| Singapore (SG) | 338 | [by-country/SG.txt](by-country/SG.txt) |
| Brazil (BR) | 338 | [by-country/BR.txt](by-country/BR.txt) |
| Canada (CA) | 306 | [by-country/CA.txt](by-country/CA.txt) |
| Mexico (MX) | 303 | [by-country/MX.txt](by-country/MX.txt) |
| Colombia (CO) | 302 | [by-country/CO.txt](by-country/CO.txt) |
| Sweden (SE) | 294 | [by-country/SE.txt](by-country/SE.txt) |
| Bangladesh (BD) | 275 | [by-country/BD.txt](by-country/BD.txt) |
| United Kingdom (GB) | 271 | [by-country/GB.txt](by-country/GB.txt) |
| South Africa (ZA) | 199 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 190 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 190 | [by-country/VN.txt](by-country/VN.txt) |
| Malaysia (MY) | 164 | [by-country/MY.txt](by-country/MY.txt) |
| Netherlands (NL) | 158 | [by-country/NL.txt](by-country/NL.txt) |
| Switzerland (CH) | 152 | [by-country/CH.txt](by-country/CH.txt) |
| Turkey (TR) | 136 | [by-country/TR.txt](by-country/TR.txt) |
| Venezuela (VE) | 132 | [by-country/VE.txt](by-country/VE.txt) |
| Ireland (IE) | 131 | [by-country/IE.txt](by-country/IE.txt) |
| Ecuador (EC) | 131 | [by-country/EC.txt](by-country/EC.txt) |
| United Arab Emirates (AE) | 124 | [by-country/AE.txt](by-country/AE.txt) |
| Argentina (AR) | 113 | [by-country/AR.txt](by-country/AR.txt) |
| Spain (ES) | 96 | [by-country/ES.txt](by-country/ES.txt) |
| Cambodia (KH) | 91 | [by-country/KH.txt](by-country/KH.txt) |
| Peru (PE) | 77 | [by-country/PE.txt](by-country/PE.txt) |
| Israel (IL) | 73 | [by-country/IL.txt](by-country/IL.txt) |
| Dominican Republic (DO) | 67 | [by-country/DO.txt](by-country/DO.txt) |
| Finland (FI) | 66 | [by-country/FI.txt](by-country/FI.txt) |
| Chile (CL) | 66 | [by-country/CL.txt](by-country/CL.txt) |
| Ukraine (UA) | 65 | [by-country/UA.txt](by-country/UA.txt) |
| Poland (PL) | 55 | [by-country/PL.txt](by-country/PL.txt) |
| Egypt (EG) | 48 | [by-country/EG.txt](by-country/EG.txt) |
| Libya (LY) | 42 | [by-country/LY.txt](by-country/LY.txt) |
| Pakistan (PK) | 38 | [by-country/PK.txt](by-country/PK.txt) |
| Kenya (KE) | 37 | [by-country/KE.txt](by-country/KE.txt) |
| Bulgaria (BG) | 35 | [by-country/BG.txt](by-country/BG.txt) |
| Georgia (GE) | 34 | [by-country/GE.txt](by-country/GE.txt) |
| Paraguay (PY) | 32 | [by-country/PY.txt](by-country/PY.txt) |
| Taiwan (TW) | 30 | [by-country/TW.txt](by-country/TW.txt) |
| Kazakhstan (KZ) | 30 | [by-country/KZ.txt](by-country/KZ.txt) |
| Guatemala (GT) | 26 | [by-country/GT.txt](by-country/GT.txt) |
| Hungary (HU) | 25 | [by-country/HU.txt](by-country/HU.txt) |
| Nepal (NP) | 24 | [by-country/NP.txt](by-country/NP.txt) |
| Seychelles (SC) | 18 | [by-country/SC.txt](by-country/SC.txt) |
| Iraq (IQ) | 18 | [by-country/IQ.txt](by-country/IQ.txt) |
| Czechia (CZ) | 17 | [by-country/CZ.txt](by-country/CZ.txt) |
| Albania (AL) | 17 | [by-country/AL.txt](by-country/AL.txt) |
| Puerto Rico (PR) | 16 | [by-country/PR.txt](by-country/PR.txt) |
| Honduras (HN) | 15 | [by-country/HN.txt](by-country/HN.txt) |
| Austria (AT) | 13 | [by-country/AT.txt](by-country/AT.txt) |
| Romania (RO) | 13 | [by-country/RO.txt](by-country/RO.txt) |
| British Virgin Islands (VG) | 13 | [by-country/VG.txt](by-country/VG.txt) |
| Syria (SY) | 13 | [by-country/SY.txt](by-country/SY.txt) |
| Nigeria (NG) | 13 | [by-country/NG.txt](by-country/NG.txt) |
| Armenia (AM) | 13 | [by-country/AM.txt](by-country/AM.txt) |
| Palestine (PS) | 12 | [by-country/PS.txt](by-country/PS.txt) |
| Serbia (RS) | 10 | [by-country/RS.txt](by-country/RS.txt) |
| Estonia (EE) | 10 | [by-country/EE.txt](by-country/EE.txt) |
| Kosovo (XK) | 9 | [by-country/XK.txt](by-country/XK.txt) |
| Uzbekistan (UZ) | 9 | [by-country/UZ.txt](by-country/UZ.txt) |
| Latvia (LV) | 8 | [by-country/LV.txt](by-country/LV.txt) |
| Ghana (GH) | 8 | [by-country/GH.txt](by-country/GH.txt) |
| Tanzania (TZ) | 8 | [by-country/TZ.txt](by-country/TZ.txt) |
| Mongolia (MN) | 8 | [by-country/MN.txt](by-country/MN.txt) |
| Lebanon (LB) | 7 | [by-country/LB.txt](by-country/LB.txt) |
| Greece (GR) | 7 | [by-country/GR.txt](by-country/GR.txt) |
| Bolivia (BO) | 7 | [by-country/BO.txt](by-country/BO.txt) |
| Botswana (BW) | 7 | [by-country/BW.txt](by-country/BW.txt) |
| Panama (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| Belarus (BY) | 6 | [by-country/BY.txt](by-country/BY.txt) |
| Cyprus (CY) | 5 | [by-country/CY.txt](by-country/CY.txt) |
| Croatia (HR) | 5 | [by-country/HR.txt](by-country/HR.txt) |
| Belgium (BE) | 5 | [by-country/BE.txt](by-country/BE.txt) |
| Senegal (SN) | 5 | [by-country/SN.txt](by-country/SN.txt) |
| Costa Rica (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Moldova (MD) | 4 | [by-country/MD.txt](by-country/MD.txt) |
| Kyrgyzstan (KG) | 4 | [by-country/KG.txt](by-country/KG.txt) |
| Slovakia (SK) | 4 | [by-country/SK.txt](by-country/SK.txt) |
| Montenegro (ME) | 4 | [by-country/ME.txt](by-country/ME.txt) |
| Azerbaijan (AZ) | 4 | [by-country/AZ.txt](by-country/AZ.txt) |
| Rwanda (RW) | 3 | [by-country/RW.txt](by-country/RW.txt) |
| Congo (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| Bosnia and Herzegovina (BA) | 3 | [by-country/BA.txt](by-country/BA.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| Yemen (YE) | 3 | [by-country/YE.txt](by-country/YE.txt) |
| Norway (NO) | 3 | [by-country/NO.txt](by-country/NO.txt) |
| Uganda (UG) | 3 | [by-country/UG.txt](by-country/UG.txt) |
| Burkina Faso (BF) | 3 | [by-country/BF.txt](by-country/BF.txt) |
| Qatar (QA) | 3 | [by-country/QA.txt](by-country/QA.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| Laos (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| Lithuania (LT) | 2 | [by-country/LT.txt](by-country/LT.txt) |
| DR Congo (CD) | 2 | [by-country/CD.txt](by-country/CD.txt) |
| Malta (MT) | 2 | [by-country/MT.txt](by-country/MT.txt) |
| New Zealand (NZ) | 2 | [by-country/NZ.txt](by-country/NZ.txt) |
| Angola (AO) | 2 | [by-country/AO.txt](by-country/AO.txt) |
| Uruguay (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| Turkmenistan (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| Macau (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| Timor-Leste (TL) | 1 | [by-country/TL.txt](by-country/TL.txt) |
| North Macedonia (MK) | 1 | [by-country/MK.txt](by-country/MK.txt) |
| Oman (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| Somalia (SO) | 1 | [by-country/SO.txt](by-country/SO.txt) |
| Jamaica (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
| Cameroon (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| Slovenia (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| Maldives (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| Malawi (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| Iceland (IS) | 1 | [by-country/IS.txt](by-country/IS.txt) |
| Lesotho (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| Gambia (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| Samoa (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| Equatorial Guinea (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| Sri Lanka (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| Myanmar (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| Bhutan (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| Gabon (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| El Salvador (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-19 19:07 UTC</sub></p>
