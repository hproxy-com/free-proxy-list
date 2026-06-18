<p align="center">
  <a href="https://hproxy.com"><img src="https://raw.githubusercontent.com/hproxy-com/free-proxy-list/main/assets/banner.svg?v=1781773625" alt="HProxy Free Proxy List" width="560"></a>
</p>

<p align="center">
  <a href="https://hproxy.com"><img src="https://img.shields.io/badge/Website-hproxy.com-006039?style=for-the-badge&labelColor=1A1918" alt="Website"></a>
  <a href="https://hproxy.com/proxy-checker"><img src="https://img.shields.io/badge/Proxy_Checker-Free-006039?style=for-the-badge&labelColor=1A1918" alt="Proxy Checker"></a>
  <a href="https://hproxy.com/residential"><img src="https://img.shields.io/badge/Premium_Proxies-from_$0.99_per_GB-006039?style=for-the-badge&labelColor=1A1918" alt="Premium Proxies"></a>
</p>

<p align="center"><b>20,573 free, live-checked proxies, updated every hour.</b><br>HTTP, HTTPS, SOCKS4 and SOCKS5, with country on every IP. 3,788 live right now, 296,106+ tracked all-time, updated 18.06.2026.</p>

## Download

| List | Proxies | Formats |
|------|--------:|---------|
| All | 20,573 | [txt](all.txt) &middot; [json](all.json) &middot; [csv](all.csv) |
| HTTP | 2,579 | [txt](http.txt) |
| HTTPS | 1,230 | [txt](https.txt) |
| SOCKS4 | 1,704 | [txt](socks4.txt) |
| SOCKS5 | 1,528 | [txt](socks5.txt) |

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
<summary><b>Free proxies by country</b> (129 countries)</summary>

| Country | Proxies | File |
|---------|--------:|------|
| Iran (IR) | 6,722 | [by-country/IR.txt](by-country/IR.txt) |
| United States (US) | 1,995 | [by-country/US.txt](by-country/US.txt) |
| Indonesia (ID) | 1,622 | [by-country/ID.txt](by-country/ID.txt) |
| China (CN) | 1,003 | [by-country/CN.txt](by-country/CN.txt) |
| India (IN) | 722 | [by-country/IN.txt](by-country/IN.txt) |
| Japan (JP) | 618 | [by-country/JP.txt](by-country/JP.txt) |
| Germany (DE) | 525 | [by-country/DE.txt](by-country/DE.txt) |
| Hong Kong (HK) | 479 | [by-country/HK.txt](by-country/HK.txt) |
| South Korea (KR) | 457 | [by-country/KR.txt](by-country/KR.txt) |
| Australia (AU) | 436 | [by-country/AU.txt](by-country/AU.txt) |
| Russia (RU) | 362 | [by-country/RU.txt](by-country/RU.txt) |
| France (FR) | 330 | [by-country/FR.txt](by-country/FR.txt) |
| Thailand (TH) | 330 | [by-country/TH.txt](by-country/TH.txt) |
| Sweden (SE) | 289 | [by-country/SE.txt](by-country/SE.txt) |
| Canada (CA) | 283 | [by-country/CA.txt](by-country/CA.txt) |
| Philippines (PH) | 282 | [by-country/PH.txt](by-country/PH.txt) |
| Singapore (SG) | 263 | [by-country/SG.txt](by-country/SG.txt) |
| Brazil (BR) | 257 | [by-country/BR.txt](by-country/BR.txt) |
| United Kingdom (GB) | 220 | [by-country/GB.txt](by-country/GB.txt) |
| Mexico (MX) | 219 | [by-country/MX.txt](by-country/MX.txt) |
| Switzerland (CH) | 210 | [by-country/CH.txt](by-country/CH.txt) |
| Bangladesh (BD) | 207 | [by-country/BD.txt](by-country/BD.txt) |
| Colombia (CO) | 205 | [by-country/CO.txt](by-country/CO.txt) |
| South Africa (ZA) | 190 | [by-country/ZA.txt](by-country/ZA.txt) |
| Italy (IT) | 161 | [by-country/IT.txt](by-country/IT.txt) |
| Vietnam (VN) | 148 | [by-country/VN.txt](by-country/VN.txt) |
| Malaysia (MY) | 134 | [by-country/MY.txt](by-country/MY.txt) |
| Netherlands (NL) | 132 | [by-country/NL.txt](by-country/NL.txt) |
| Ireland (IE) | 122 | [by-country/IE.txt](by-country/IE.txt) |
| United Arab Emirates (AE) | 106 | [by-country/AE.txt](by-country/AE.txt) |
| Turkey (TR) | 103 | [by-country/TR.txt](by-country/TR.txt) |
| Venezuela (VE) | 102 | [by-country/VE.txt](by-country/VE.txt) |
| Spain (ES) | 87 | [by-country/ES.txt](by-country/ES.txt) |
| Ecuador (EC) | 87 | [by-country/EC.txt](by-country/EC.txt) |
| Argentina (AR) | 79 | [by-country/AR.txt](by-country/AR.txt) |
| Israel (IL) | 70 | [by-country/IL.txt](by-country/IL.txt) |
| Cambodia (KH) | 68 | [by-country/KH.txt](by-country/KH.txt) |
| Peru (PE) | 55 | [by-country/PE.txt](by-country/PE.txt) |
| Finland (FI) | 49 | [by-country/FI.txt](by-country/FI.txt) |
| Ukraine (UA) | 49 | [by-country/UA.txt](by-country/UA.txt) |
| Dominican Republic (DO) | 49 | [by-country/DO.txt](by-country/DO.txt) |
| Poland (PL) | 48 | [by-country/PL.txt](by-country/PL.txt) |
| Chile (CL) | 45 | [by-country/CL.txt](by-country/CL.txt) |
| Pakistan (PK) | 32 | [by-country/PK.txt](by-country/PK.txt) |
| Bulgaria (BG) | 30 | [by-country/BG.txt](by-country/BG.txt) |
| Egypt (EG) | 30 | [by-country/EG.txt](by-country/EG.txt) |
| Kazakhstan (KZ) | 28 | [by-country/KZ.txt](by-country/KZ.txt) |
| Kenya (KE) | 26 | [by-country/KE.txt](by-country/KE.txt) |
| Libya (LY) | 26 | [by-country/LY.txt](by-country/LY.txt) |
| Nepal (NP) | 25 | [by-country/NP.txt](by-country/NP.txt) |
| Taiwan (TW) | 23 | [by-country/TW.txt](by-country/TW.txt) |
| Georgia (GE) | 23 | [by-country/GE.txt](by-country/GE.txt) |
| Paraguay (PY) | 23 | [by-country/PY.txt](by-country/PY.txt) |
| Guatemala (GT) | 20 | [by-country/GT.txt](by-country/GT.txt) |
| Hungary (HU) | 17 | [by-country/HU.txt](by-country/HU.txt) |
| Iraq (IQ) | 15 | [by-country/IQ.txt](by-country/IQ.txt) |
| Albania (AL) | 15 | [by-country/AL.txt](by-country/AL.txt) |
| Puerto Rico (PR) | 14 | [by-country/PR.txt](by-country/PR.txt) |
| Czechia (CZ) | 14 | [by-country/CZ.txt](by-country/CZ.txt) |
| British Virgin Islands (VG) | 13 | [by-country/VG.txt](by-country/VG.txt) |
| Honduras (HN) | 13 | [by-country/HN.txt](by-country/HN.txt) |
| Austria (AT) | 11 | [by-country/AT.txt](by-country/AT.txt) |
| Seychelles (SC) | 11 | [by-country/SC.txt](by-country/SC.txt) |
| Estonia (EE) | 10 | [by-country/EE.txt](by-country/EE.txt) |
| Romania (RO) | 10 | [by-country/RO.txt](by-country/RO.txt) |
| Serbia (RS) | 9 | [by-country/RS.txt](by-country/RS.txt) |
| Syria (SY) | 9 | [by-country/SY.txt](by-country/SY.txt) |
| Uzbekistan (UZ) | 8 | [by-country/UZ.txt](by-country/UZ.txt) |
| Nigeria (NG) | 7 | [by-country/NG.txt](by-country/NG.txt) |
| Latvia (LV) | 7 | [by-country/LV.txt](by-country/LV.txt) |
| Palestine (PS) | 7 | [by-country/PS.txt](by-country/PS.txt) |
| Ghana (GH) | 7 | [by-country/GH.txt](by-country/GH.txt) |
| Panama (PA) | 6 | [by-country/PA.txt](by-country/PA.txt) |
| Bolivia (BO) | 5 | [by-country/BO.txt](by-country/BO.txt) |
| Kosovo (XK) | 5 | [by-country/XK.txt](by-country/XK.txt) |
| Croatia (HR) | 5 | [by-country/HR.txt](by-country/HR.txt) |
| Botswana (BW) | 5 | [by-country/BW.txt](by-country/BW.txt) |
| Cyprus (CY) | 4 | [by-country/CY.txt](by-country/CY.txt) |
| Belarus (BY) | 4 | [by-country/BY.txt](by-country/BY.txt) |
| Azerbaijan (AZ) | 4 | [by-country/AZ.txt](by-country/AZ.txt) |
| Costa Rica (CR) | 4 | [by-country/CR.txt](by-country/CR.txt) |
| Greece (GR) | 4 | [by-country/GR.txt](by-country/GR.txt) |
| Armenia (AM) | 4 | [by-country/AM.txt](by-country/AM.txt) |
| Mongolia (MN) | 4 | [by-country/MN.txt](by-country/MN.txt) |
| Tanzania (TZ) | 4 | [by-country/TZ.txt](by-country/TZ.txt) |
| Belgium (BE) | 3 | [by-country/BE.txt](by-country/BE.txt) |
| Congo (CG) | 3 | [by-country/CG.txt](by-country/CG.txt) |
| DR Congo (CD) | 3 | [by-country/CD.txt](by-country/CD.txt) |
| Kyrgyzstan (KG) | 3 | [by-country/KG.txt](by-country/KG.txt) |
| Saudi Arabia (SA) | 3 | [by-country/SA.txt](by-country/SA.txt) |
| Montenegro (ME) | 3 | [by-country/ME.txt](by-country/ME.txt) |
| Burkina Faso (BF) | 3 | [by-country/BF.txt](by-country/BF.txt) |
| Qatar (QA) | 2 | [by-country/QA.txt](by-country/QA.txt) |
| Uruguay (UY) | 2 | [by-country/UY.txt](by-country/UY.txt) |
| Laos (LA) | 2 | [by-country/LA.txt](by-country/LA.txt) |
| Rwanda (RW) | 2 | [by-country/RW.txt](by-country/RW.txt) |
| Moldova (MD) | 2 | [by-country/MD.txt](by-country/MD.txt) |
| Slovakia (SK) | 2 | [by-country/SK.txt](by-country/SK.txt) |
| Norway (NO) | 2 | [by-country/NO.txt](by-country/NO.txt) |
| Lebanon (LB) | 2 | [by-country/LB.txt](by-country/LB.txt) |
| Portugal (PT) | 2 | [by-country/PT.txt](by-country/PT.txt) |
| Senegal (SN) | 2 | [by-country/SN.txt](by-country/SN.txt) |
| Lithuania (LT) | 2 | [by-country/LT.txt](by-country/LT.txt) |
| Bosnia and Herzegovina (BA) | 2 | [by-country/BA.txt](by-country/BA.txt) |
| North Macedonia (MK) | 1 | [by-country/MK.txt](by-country/MK.txt) |
| Turkmenistan (TM) | 1 | [by-country/TM.txt](by-country/TM.txt) |
| Timor-Leste (TL) | 1 | [by-country/TL.txt](by-country/TL.txt) |
| Myanmar (MM) | 1 | [by-country/MM.txt](by-country/MM.txt) |
| Afghanistan (AF) | 1 | [by-country/AF.txt](by-country/AF.txt) |
| Oman (OM) | 1 | [by-country/OM.txt](by-country/OM.txt) |
| El Salvador (SV) | 1 | [by-country/SV.txt](by-country/SV.txt) |
| Cameroon (CM) | 1 | [by-country/CM.txt](by-country/CM.txt) |
| Macau (MO) | 1 | [by-country/MO.txt](by-country/MO.txt) |
| New Zealand (NZ) | 1 | [by-country/NZ.txt](by-country/NZ.txt) |
| Malta (MT) | 1 | [by-country/MT.txt](by-country/MT.txt) |
| Yemen (YE) | 1 | [by-country/YE.txt](by-country/YE.txt) |
| Algeria (DZ) | 1 | [by-country/DZ.txt](by-country/DZ.txt) |
| Lesotho (LS) | 1 | [by-country/LS.txt](by-country/LS.txt) |
| Uganda (UG) | 1 | [by-country/UG.txt](by-country/UG.txt) |
| Slovenia (SI) | 1 | [by-country/SI.txt](by-country/SI.txt) |
| Maldives (MV) | 1 | [by-country/MV.txt](by-country/MV.txt) |
| Sri Lanka (LK) | 1 | [by-country/LK.txt](by-country/LK.txt) |
| Gambia (GM) | 1 | [by-country/GM.txt](by-country/GM.txt) |
| Malawi (MW) | 1 | [by-country/MW.txt](by-country/MW.txt) |
| Samoa (WS) | 1 | [by-country/WS.txt](by-country/WS.txt) |
| Bhutan (BT) | 1 | [by-country/BT.txt](by-country/BT.txt) |
| Gabon (GA) | 1 | [by-country/GA.txt](by-country/GA.txt) |
| Denmark (DK) | 1 | [by-country/DK.txt](by-country/DK.txt) |
| Angola (AO) | 1 | [by-country/AO.txt](by-country/AO.txt) |

</details>

## Powered by HProxy

Free proxies die fast and are often already blocked. For proxies that stay up, [**HProxy**](https://hproxy.com) does residential, ISP, mobile and datacenter, billed by the gigabyte, from $0.99/GB.

[Live list](https://hproxy.com/free-proxy-list) &nbsp;&middot;&nbsp; [Proxy checker](https://hproxy.com/proxy-checker) &nbsp;&middot;&nbsp; [Pricing](https://hproxy.com/residential)

## Contributing

Raw IPs cannot be added by pull request (the list regenerates hourly). Instead, [suggest a proxy source](CONTRIBUTING.md), or feed proxies through the [free checker](https://hproxy.com/proxy-checker), which adds verified proxies to the pool automatically.

## Legal

These proxies are aggregated from publicly available sources. We do not scan, port-scan or collect them ourselves, and we store nothing about the devices behind them. They are provided as-is, with no warranty, for lawful use only. You are responsible for how you use them: follow the GitHub Acceptable Use Policy and your local laws, and never route passwords or sensitive data through a public proxy. If an IP address is yours and you want it removed, open an issue.

<p align="center"><sub><a href="https://hproxy.com">hproxy.com</a> &nbsp;&middot;&nbsp; auto-updated hourly &nbsp;&middot;&nbsp; 2026-06-18 09:07 UTC</sub></p>
