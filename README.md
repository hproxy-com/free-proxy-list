<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1782062212" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>23,515 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,272 live right now, 288,558+ tracked all-time, updated 21.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 23,515 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,211 | [txt](http.txt) |
| HTTPS | 959 | [txt](https.txt) |
| SOCKS4 | 1,295 | [txt](socks4.txt) |
| SOCKS5 | 1,181 | [txt](socks5.txt) |

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
| Iran (IR) | 5,773 | [by-country/IR.txt](by-country/IR.txt) |
| Indonesia (ID) | 2,705 | [by-country/ID.txt](by-country/ID.txt) |
| United States (US) | 1,615 | [by-country/US.txt](by-country/US.txt) |
| China (CN) | 1,428 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 873 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 714 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 665 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 627 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 623 | [by-country/KR.txt](by-country/KR.txt) |
| Russia (RU) | 474 | [by-country/RU.txt](by-country/RU.txt) |
| Australia (AU) | 460 | [by-country/AU.txt](by-country/AU.txt) |
| Thailand (TH) | 454 | [by-country/TH.txt](by-country/TH.txt) |
| Philippines (PH) | 440 | [by-country/PH.txt](by-country/PH.txt) |
| Brazil (BR) | 379 | [by-country/BR.txt](by-country/BR.txt) |
| Singapore (SG) | 377 | [by-country/SG.txt](by-country/SG.txt) |
| France (FR) | 369 | [by-country/FR.txt](by-country/FR.txt) |
| Colombia (CO) | 345 | [by-country/CO.txt](by-country/CO.txt) |
| Mexico (MX) | 341 | [by-country/MX.txt](by-country/MX.txt) |
| Sweden (SE) | 337 | [by-country/SE.txt](by-country/SE.txt) |
| Bangladesh (BD) | 323 | [by-country/BD.txt](by-country/BD.txt) |
| Canada (CA) | 304 | [by-country/CA.txt](by-country/CA.txt) |
| United Kingdom (GB) | 304 | [by-country/GB.txt](by-country/GB.txt) |
| South Africa (ZA) | 223 | [by-country/ZA.txt](by-country/ZA.txt) |
| Vietnam (VN) | 194 | [by-country/VN.txt](by-country/VN.txt) |
| Italy (IT) | 187 | [by-country/IT.txt](by-country/IT.txt) |
| Netherlands (NL) | 173 | [by-country/NL.txt](by-country/NL.txt) |
| Malaysia (MY) | 168 | [by-country/MY.txt](by-country/MY.txt) |
| Ecuador (EC) | 157 | [by-country/EC.txt](by-country/EC.txt) |
| Turkey (TR) | 152 | [by-country/TR.txt](by-country/TR.txt) |
| United Arab Emirates (AE) | 149 | [by-country/AE.txt](by-country/AE.txt) |
| Switzerland (CH) | 149 | [by-country/CH.txt](by-country/CH.txt) |
| Venezuela (VE) | 143 | [by-country/VE.txt](by-country/VE.txt) |
| Ireland (IE) | 139 | [by-country/IE.txt](by-country/IE.txt) |
| Argentina (AR) | 119 | [by-country/AR.txt](by-country/AR.txt) |
| Spain (ES) | 103 | [by-country/ES.txt](by-country/ES.txt) |
| Cambodia (KH) | 100 | [by-country/KH.txt](by-country/KH.txt) |
| Dominican Republic (DO) | 88 | [by-country/DO.txt](by-country/DO.txt) |
| Peru (PE) | 87 | [by-country/PE.txt](by-country/PE.txt) |
| Ukraine (UA) | 82 | [by-country/UA.txt](by-country/UA.txt) |
| Chile (CL) | 80 | [by-country/CL.txt](by-country/CL.txt) |
| Israel (IL) | 77 | [by-country/IL.txt](by-country/IL.txt) |
| Finland (FI) | 66 | [by-country/FI.txt](by-country/FI.txt) |
| Poland (PL) | 60 | [by-country/PL.txt](by-country/PL.txt) |
| Egypt (EG) | 57 | [by-country/EG.txt](by-country/EG.txt) |
| Pakistan (PK) | 45 | [by-country/PK.txt](by-country/PK.txt) |
| Bulgaria (BG) | 43 | [by-country/BG.txt](by-country/BG.txt) |
| Libya (LY) | 43 | [by-country/LY.txt](by-country/LY.txt) |
| Paraguay (PY) | 43 | [by-country/PY.txt](by-country/PY.txt) |
| Kenya (KE) | 40 | [by-country/KE.txt](by-country/KE.txt) |
| Georgia (GE) | 34 | [by-country/GE.txt](by-country/GE.txt) |
| Taiwan (TW) | 29 | [by-country/TW.txt](by-country/TW.txt) |
| Guatemala (GT) | 28 | [by-country/GT.txt](by-country/GT.txt) |
| Nepal (NP) | 26 | [by-country/NP.txt](by-country/NP.txt) |
| Hungary (HU) | 24 | [by-country/HU.txt](by-country/HU.txt) |
| Iraq (IQ) | 24 | [by-country/IQ.txt](by-country/IQ.txt) |
| Kazakhstan (KZ) | 22 | [by-country/KZ.txt](by-country/KZ.txt) |
| Honduras (HN) | 20 | [by-country/HN.txt](by-country/HN.txt) |
| Albania (AL) | 19 | [by-country/AL.txt](by-country/AL.txt) |
| Austria (AT) | 19 | [by-country/AT.txt](by-country/AT.txt) |
| Czechia (CZ) | 19 | [by-country/CZ.txt](by-country/CZ.txt) |
| Nigeria (NG) | 18 | [by-country/NG.txt](by-country/NG.txt) |
| Seychelles (SC) | 18 | [by-country/SC.txt](by-country/SC.txt) |
| Syria (SY) | 18 | [by-country/SY.txt](by-country/SY.txt) |
| Puerto Rico (PR) | 16 | [by-country/PR.txt](by-country/PR.txt) |
| Palestine (PS) | 16 | [by-country/PS.txt](by-country/PS.txt) |
| Romania (RO) | 13 | [by-country/RO.txt](by-country/RO.txt) |
| British Virgin Islands (VG) | 13 | [by-country/VG.txt](by-country/VG.txt) |
| Armenia (AM) | 12 | [by-country/AM.txt](by-country/AM.txt) |
| Serbia (RS) | 11 | [by-country/RS.txt](by-country/RS.txt) |
| Estonia (EE) | 9 | [by-country/EE.txt](by-country/EE.txt) |
| Tanzania (TZ) | 9 | [by-country/TZ.txt](by-country/TZ.txt) |
| Uzbekistan (UZ) | 9 | [by-country/UZ.txt](by-country/UZ.txt) |
| Lebanon (LB) | 8 | [by-country/LB.txt](by-country/LB.txt) |
| Latvia (LV) | 8 | [by-country/LV.txt](by-country/LV.txt) |
| Mongolia (MN) | 8 | [by-country/MN.txt](by-country/MN.txt) |
| Kosovo (XK) | 8 | [by-country/XK.txt](by-country/XK.txt) |
| Ghana (GH) | 7 | [by-country/GH.txt](by-country/GH.txt) |
| Greece (GR) | 7 | [by-country/GR.txt](by-country/GR.txt) |
| Croatia (HR) | 7 | [by-country/HR.txt](by-country/HR.txt) |
| Bolivia (BO) | 6 | [by-country/BO.txt](by-country/BO.txt) |
| Botswana (BW) | 6 | [by-country/BW.txt](by-country/BW.txt) |
| Belarus (BY) | 6 | [by-country/BY.txt](by-country/BY.txt) |
| Panama (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| Azerbaijan (AZ) | 5 | [by-country/AZ.txt](by-country/AZ.txt) |
| Senegal (SN) | 5 | [by-country/SN.txt](by-country/SN.txt) |
| Bosnia and Herzegovina (BA) | 4 | [by-country/BA.txt](by-country/BA.txt) |
| Belgium (BE) | 4 | [by-country/BE.txt](by-country/BE.txt) |
| Costa Rica (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Cyprus (CY) | 4 | [by-country/CY.txt](by-country/CY.txt) |
| Moldova (MD) | 4 | [by-country/MD.txt](by-country/MD.txt) |
| Montenegro (ME) | 4 | [by-country/ME.txt](by-country/ME.txt) |
| Qatar (QA) | 4 | [by-country/QA.txt](by-country/QA.txt) |
| Angola (AO) | 3 | [by-country/AO.txt](by-country/AO.txt) |
| Burkina Faso (BF) | 3 | [by-country/BF.txt](by-country/BF.txt) |
| DR Congo (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| Kyrgyzstan (KG) | 3 | [by-country/KG.txt](by-country/KG.txt) |
| Lithuania (LT) | 3 | [by-country/LT.txt](by-country/LT.txt) |
| Rwanda (RW) | 3 | [by-country/RW.txt](by-country/RW.txt) |
| Slovakia (SK) | 3 | [by-country/SK.txt](by-country/SK.txt) |
| Uganda (UG) | 3 | [by-country/UG.txt](by-country/UG.txt) |
| Yemen (YE) | 3 | [by-country/YE.txt](by-country/YE.txt) |
| Afghanistan (AF) | 2 | [by-country/AF.txt](by-country/AF.txt) |
| Congo (CG) | 2 | [by-country/CG.txt](by-country/CG.txt) |
| Gambia (GM) | 2 | [by-country/GM.txt](by-country/GM.txt) |
| Laos (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| Myanmar (MM) | 2 | [by-country/MM.txt](by-country/MM.txt) |
| Malta (MT) | 2 | [by-country/MT.txt](by-country/MT.txt) |
| Norway (NO) | 2 | [by-country/NO.txt](by-country/NO.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| Saudi Arabia (SA) | 2 | [by-country/SA.txt](by-country/SA.txt) |
| Uruguay (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| Bhutan (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| Cameroon (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| Gabon (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| Equatorial Guinea (GQ) | 1 | [by-country/GQ.txt](by-country/GQ.txt) |
| Jamaica (JM) | 1 | [by-country/JM.txt](by-country/JM.txt) |
| Sri Lanka (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| Lesotho (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| North Macedonia (MK) | 1 | [by-country/MK.txt](by-country/MK.txt) |
| Macau (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| Maldives (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| Malawi (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| New Zealand (NZ) | 1 | [by-country/NZ.txt](by-country/NZ.txt) |
| Oman (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| Slovenia (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| Somalia (SO) | 1 | [by-country/SO.txt](by-country/SO.txt) |
| El Salvador (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| Timor-Leste (TL) | 1 | [by-country/TL.txt](by-country/TL.txt) |
| Turkmenistan (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| Samoa (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request: the list regenerates hourly from the verification engine, so committed entries would be overwritten on the next update. The useful way to help is to [suggest a public proxy source](CONTRIBUTING.md) for the engine to pull from.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-21 17:16 UTC</sub></p>
