# Kalawao County Weather Report

> **Level 1 county aggregate — deterministically assembled from preserved source-layer records.**

- **Generated:** 2026-09-25T20:41:28-10:00 HST
- **Report created:** 2026-09-25T20:41:28-10:00 HST
- **County:** Kalawao County
- **Source level:** 0 Level Processing
- **Current report sections:** 8
- **Processing:** deterministic rules only; no AI/LLM classification.
- **Level 0:** untouched; its current and archived reports remain intact.

---

## 1. 7-Day Zone Forecasts (all islands)

- **Resource ID:** zfp_zone_forecast
- **Source:** https://api.weather.gov/products/types/ZFP/locations/HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
{"@id": "https://api.weather.gov/products/89550b4e-369e-4a12-bdf7-93c632312524", "id": "89550b4e-369e-4a12-bdf7-93c632312524", "wmoCollectiveId": "FPHW50", "issuingOffice": "PHFO", "issuanceTime": "2026-09-26T02:58:00+00:00", "productCode": "ZFP", "productName": "Zone Forecast Product"}
```

---

## 2. AIRMETs

- **Resource ID:** wa0_airmets
- **Source:** https://forecast.weather.gov/product.php?site=HFO&product=WA0&issuedby=HI
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
988
WAHW31 PHFO 260337
WA0HI

HNLS WA 260400
AIRMET SIERRA FOR IFR VALID UNTIL 261000
.
AIRMET MTN OBSC...KAUAI OAHU MOLOKAI MAUI
N THROUGH E SECTIONS.
TEMPO MTN OBSC ABV 025 EXP DUE TO CLD AND SHRA.
COND CONT BEYOND 1000Z.
.
AIRMET IFR...BIG ISLAND
UPOLU POINT TO CAPE KUMUKAHI TO SOUTH CAPE.
TEMPO CEILING BLW 010 AND/OR VIS BLW 3SM SHRA.
COND CONT BEYOND 1000Z.

=HNLT WA 260400
AIRMET TANGO FOR TURB VALID UNTIL 261000
.
AIRMET TURB...HI
OVER AND IMT S THRU W OF MTN.
TEMPO MOD TURB EXP BLW 070.
COND CONT BEYOND 1000Z.

=HNLZ WA 260400
AIRMET ZULU FOR ICE AND FZLVL VALID UNTIL 261000
.
NO SIGNIFICANT ICE EXP.
.
FZLVL...159.
```

---

## 3. Area Forecast Discussion

- **Resource ID:** afd_area_forecast_discussion
- **Source:** https://api.weather.gov/products/types/AFD/locations/HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
{"@id": "https://api.weather.gov/products/8759e216-9e2f-4366-8f44-be01140d2cfb", "id": "8759e216-9e2f-4366-8f44-be01140d2cfb", "wmoCollectiveId": "FXHW60", "issuingOffice": "PHFO", "issuanceTime": "2026-09-26T02:55:00+00:00", "productCode": "AFD", "productName": "Area Forecast Discussion"}
```

---

## 4. Coastal Waters Forecast (within 40nm)

- **Resource ID:** cwf_coastal_waters
- **Source:** https://api.weather.gov/products/types/CWF/locations/HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
{"@id": "https://api.weather.gov/products/b8546f14-f95e-4408-9f14-de0911476e7f", "id": "b8546f14-f95e-4408-9f14-de0911476e7f", "wmoCollectiveId": "FZHW50", "issuingOffice": "PHFO", "issuanceTime": "2026-09-26T02:25:00+00:00", "productCode": "CWF", "productName": "Coastal Waters Forecast"}
```

---

## 5. High Seas Forecast N. Pacific

- **Resource ID:** hsf_high_seas_npac
- **Source:** https://forecast.weather.gov/product.php?site=HFO&product=HSF&issuedby=NP
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
597
FZPN40 PHFO 260312
HSFNP

HIGH SEAS FORECAST
NATIONAL WEATHER SERVICE HONOLULU HI
0500 UTC SAT SEP 26 2026

SUPERSEDED BY NEXT ISSUANCE IN 6 HOURS

SEAS GIVEN AS SIGNIFICANT WAVE HEIGHT...WHICH IS THE AVERAGE HEIGHT
OF THE HIGHEST 1/3 OF THE WAVES. INDIVIDUAL WAVES MAY BE MORE THAN
TWICE THE SIGNIFICANT WAVE HEIGHT.

THIS HIGH SEAS FORECAST USES 1-MINUTE AVERAGE WINDS WHICH MAY BE
HIGHER THAN 10-MINUTE AVERAGE WINDS.

SECURITE

NORTH PACIFIC EQUATOR TO 30N BETWEEN 140W AND 180W

SYNOPSIS VALID 0000 UTC SEP 26 2026.
24 HOUR FORECAST VALID 0000 UTC SEP 27 2026.
48 HOUR FORECAST VALID 0000 UTC SEP 28 2026.

.WARNINGS.

...HURRICANE WARNING...
.HURRICANE NOLO NEAR 16.9N 155.3W 975 MB AT 0300 UTC SEP 26
MOVING N OR 010 DEG AT 3 KT. MAXIMUM SUSTAINED WINDS 90 KT GUSTS
110 KT. TROPICAL STORM FORCE WINDS WITHIN 120 NM N
SEMICIRCLE...110 NM SE QUADRANT AND 90 NM SW QUADRANT. WINDS 20 TO
34 KT ELSEWHERE FROM 19N TO 13N BETWEEN 157W AND 152W. SEAS 4 M
OR GREATER WITHIN 150 NM OF CENTER EXCEPT 180 NM SW QUADRANT WITH
SEAS TO 7 M. SEAS 2.5 TO 4 M ELSEWHERE DESCRIBED IN SYNOPSIS AND
FORECAST SECTION.
.24 HOUR FORECAST HURRICANE NOLO NEAR 17.1N 156.4W. MAXIMUM
SUSTAINED WINDS 95 KT GUSTS 115 KT. TROPICAL STORM FORCE WINDS
WITHIN 130 NM N SEMICIRCLE...90 NM SE QUADRANT AND 80 NM SW
QUADRANT. WINDS 20 TO 34 KT ELSEWHERE FROM 19N TO 14N BETWEEN 157W
AND 153W. SEAS 4 M OR GREATER FROM 19N TO 14N BETWEEN 158W AND
153W WITH SEAS TO 7.5 M. SEAS 2.5 TO 4 M ELSEWHERE DESCRIBED IN
SYNOPSIS AND FORECAST SECTION.
.48 HOUR FORECAST HURRICANE NOLO NEAR 16.9N 159.8W. MAXIMUM
SUSTAINED WINDS 110 KT GUSTS 135 KT. TROPICAL STORM FORCE WINDS
WITHIN 150 NM NE QUADRANT...80 NM SE QUADRANT...70 NM SW
QUADRANT...AND 120 NM NW QUADRANT. WINDS 20 TO 34 KT ELSEWHERE 19N
TO 13N BETWEEN 157W AND 153W. SEAS 4 M OR GREATER FROM 20N TO 13N
BETWEEN 162W AND 156W WITH SEAS TO 8.5 M. SEAS 2.5 TO 4 M
ELSEWHERE DESCRIBED IN SYNOPSIS AND FORECAST SECTION.

FORECAST WINDS IN AND NEAR ACTIVE TROPICAL CYCLONES SHOULD BE
USED WITH CAUTION DUE TO UNCERTAINTY IN FORECAST TRACK...SIZE AND
INTENSITY.

.SYNOPSIS AND FORECAST.

.TROUGH 26N170W 20N172W MOVING W 10 KT.
.24 HOUR FORECAST TROUGH 26N176W 22N178W.
.48 HOUR FORECAST TROUGH MOVED W OF AREA.

.WINDS 20 TO 34 KT FROM 26N TO 19N BETWEEN 162W AND 148W.
.24 HOUR FORECAST WINDS 20 TO 34 KT FROM 26N TO 19N BETWEEN 165W
AND 146W.
.48 HOUR FORECAST WINDS 20 TO 34 KT FROM 26N TO 19N BETWEEN 168W
AND 150W.

.WINDS 20 KT OR LESS OVER REMAINDER OF FORECAST AREA.

.SEAS 2.5 TO 4 M FROM 25N TO 09N BETWEEN 162W AND 145W.
.24 HOUR FORECAST SEAS 2.5 TO 4 M E OF LINE 24N140W 26N151W
29N159W 28N167W 12N161W 11N149W 14N140W.
.48 HOUR FORECAST SEAS 2.5 TO 4 M N OF LINE 30N167W 25N172W
19N171W 10N159W 14N154W 07N140W.

.SEAS 2.5 M OR LOWER OVER REMAINDER OF FORECAST AREA.

.MONSOON TROUGH 14N140W 14N149W...AND 07N173W 06N176W 08N180W.

.ISOLATED MODERATE TSTMS S OF 06N BETWEEN 177W AND 167W.

.FORECASTER TROTTER. HONOLULU HI.
```

---

## 6. Hourly Wind/Precip Observations

- **Resource ID:** oso_hourly_obs
- **Source:** https://forecast.weather.gov/product.php?site=HFO&product=OSO&issuedby=HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
583
SXHW50 PHFO 260044
OSOHFO

Hawaii Wind Da a
Na ional Wea her Service Honolulu HI
243 PM HST Fri Sep 25 2026

W I N D D A T A
----------------------
IN KNOTS
ID Loca ion Da e Time DIR SPD GUST
-------- ------------------------- ------- -(HST)- ---- ---- ----
0000LLMH1 Lower Limahuli Kauai 25Sep26 14:15 310 4 10
0000CMGH1 Common Ground Kauai 25Sep26 14:15 90 8 13
0000HLIH1 Hanalei Kauai 25Sep26 13:41 110 10 18
0000MLDH1 Moloaa Dairy Kauai 25Sep26 12:45 90 3 11
0000HNMH1 Hanamaulu Kauai 25Sep26 14:15 40 8 16
0000PHLI Lihue Kauai 25Sep26 14:00 40 20 23
0000NWWH1 Nawiliwili NOS Kauai 25Sep26 14:30 30 16 23
0000POIH1 Poipu Kauai MSG MSG MSG MSG
0000LNTH1 Lawai NTBG Kauai 25Sep26 14:15 70 18 28
0000PAKH1 Por Allen Kauai 25Sep26 14:00 80 17 29
0000MKAH1 Makaha Ridge Kauai 25Sep26 14:11 60 4 15
0000MNRH1 Mana Kauai 25Sep26 14:34 250 4 11
0000PHBK Barking Sands Kauai 25Sep26 14:00 240 6 MSG
0000PLRH1 Puu Lua Kauai 25Sep26 14:35 90 7 18
0000POPH1 Puu Opae Kauai 25Sep26 14:34 200 4 20
0000WHGH1 Waimea Heigh s Kauai 25Sep26 14:35 30 6 10

0000KRGH1 Kalahee Ridge Oahu 25Sep26 14:10 40 8 20
0000KAHH1 Kahuku Oahu MSG MSG MSG MSG
0000KTAH1 Kahuku Trng Oahu 25Sep26 13:59 100 3 22
0000KFWH1 Kii Oahu 25Sep26 13:45 70 15 23
0000OFRH1 Oahu Fores NWR Oahu 25Sep26 14:36 80 27 44
0000KWMH1 Kaaawa Makai Oahu 25Sep26 14:15 40 5 9
0000PHNG Kaneohe MCBH Oahu 25Sep26 14:00 50 13 21
0000MOKH1 Mokuoloe Is NOS Oahu 25Sep26 14:30 50 14 17
0000BELH1 Bellows AFS Oahu 25Sep26 14:15 40 17 MSG
0000KUXH1 Kaluanui Oahu 25Sep26 14:15 190 5 12
0000LYOH1 Lyon Oahu 25Sep26 14:15 310 5 18
0000NRSH1 Nuuanu Res No 1 Oahu 25Sep26 14:15 360 7 18
0000PHNL Honolulu AP Oahu 25Sep26 14:00 70 12 24
0000OOUH1 Honolulu Hbr NOS Oahu 25Sep26 14:24 10 6 15
0000HOFH1 Honouliuli PHB Oahu 25Sep26 14:41 60 12 21
0000SCBH1 Schofield Brks Oahu 25Sep26 13:57 60 5 16
0000SCEH1 Schofield Eas Oahu MSG MSG MSG MSG
0000HWLH1 HECO Wilikina Oahu 25Sep26 14:30 30 4 10
0000PHJR Kalaeloa Oahu 25Sep26 14:18 50 9 25
0000HFHH1 HECO Farring on Oahu 25Sep26 14:30 70 11 22
0000HPLH1 HECO Palehua Oahu 25Sep26 14:30 60 10 22
0000HPDH1 HECO Palehua 2 Oahu 25Sep26 14:30 60 17 25
0000HPHH1 HECO Palehua 3 Oahu 25Sep26 14:30 50 9 19
0000HPRH1 HECO Paakea Oahu 25Sep26 14:30 30 9 25
0000HLRH1 HECO Lualualei Oahu 25Sep26 14:30 50 11 22
0000HWVH1 HECO Waianae Vly Oahu 25Sep26 14:30 10 7 17
0000PLHH1 Palehua Oahu 25Sep26 14:36 50 0 0
0000WNVH1 Waianae Valley Oahu 25Sep26 14:37 60 8 30
0000HHSH1 HECO Ala Hema S Oahu 25Sep26 14:30 90 6 12
0000WBHH1 Waianae Harbor Oahu MSG MSG MSG MSG
0000HKRH1 HECO Kili Dr Oahu 25Sep26 14:30 340 8 16
0000HMVH1 HECO Makaha Vly Oahu 25Sep26 14:30 340 8 20
0000MKRH1 Makua Range Oahu 25Sep26 13:58 70 14 29
0000KKRH1 Kuaokala Oahu 25Sep26 14:36 30 14 36
0000AALH1 Kaala Oahu 25Sep26 14:15 60 6 13
0000HFRH1 HECO Farring on2 Oahu 25Sep26 14:30 60 7 15
0000HFYH1 HECO Farring on3 Oahu 25Sep26 14:30 70 17 23
0000DLGH1 Dillingham Oahu 25Sep26 13:49 50 8 16

0000MKPH1 Makapulapai Molokai 25Sep26 14:15 90 22 34
0000PAFH1 Puu Alii Molokai 25Sep26 14:22 90 3 13
0000HOMH1 Honolimaloo Molokai 25Sep26 14:15 80 8 15
0000KOPH1 Keopukaloa Molokai 25Sep26 14:15 90 13 19
0000MLKH1 Molokai 1 Molokai MSG MSG MSG MSG
0000MMPH1 MECO Makaena Molokai 25Sep26 14:30 80 11 25
0000MKYH1 MECO Kalae Hwy Molokai 25Sep26 14:30 80 9 20
0000PHMK Molokai AP Molokai 25Sep26 14:00 80 16 32
0000ANPH1 Anapuka Molokai 25Sep26 14:15 60 20 31

0000LNIH1 Lanai 1 Lanai 25Sep26 14:37 60 0 2

0000KAOH1 Kaneloa Kahoolawe MSG MSG MSG MSG

0000PHOG Kahului AP Maui 25Sep26 14:00 40 22 32
0000KLIH1 Kahului Hbr NOS Maui 25Sep26 14:24 50 15 23
0000MHRH1 MECO Hansen Rd Maui 25Sep26 14:30 30 19 30
0000MHKH1 MECO Haleakala Hwy Maui 25Sep26 14:30 30 23 33
0000MMKH1 MECO Makawao Maui 25Sep26 14:30 100 13 27
0000MKTH1 MECO Kula 2 Maui 25Sep26 14:30 90 11 24
0000PILH1 Piiholo Maui 25Sep26 14:15 100 6 17
0000EBYH1 EMI Baseyard Maui 25Sep26 14:10 100 1 5
0000HNAH1 Hana Maui MSG MSG MSG MSG
0000NKUH1 Na Kula Maui 25Sep26 14:35 100 30 48
0000AWAH1 Auwahi Maui MSG MSG MSG MSG
0000KLFH1 Kula 1 Maui 25Sep26 13:48 310 5 9
0000KKNH1 Kahikinui 1 Maui 25Sep26 14:34 150 3 11
0000KMEH1 Kamehamenui 1 Maui 25Sep26 13:48 310 3 9
0000SUMH1 Summi Maui 25Sep26 14:15 80 7 10
0000NNEH1 Nene Nes Maui 25Sep26 14:15 130 2 5
0000PHQH1 Park HQ Maui 25Sep26 14:15 70 2 8
0000WKTH1 Waikamoi Treeline Maui 25Sep26 14:15 130 4 10
0000MCTH1 MECO Cra er Rd Maui 25Sep26 14:30 300 2 4
0000KLGH1 Kula Ag Maui 25Sep26 14:15 280 3 7
0000MWAH1 MECO Waipoli Rd Maui 25Sep26 14:30 270 2 5
0000KKEH1 Keokea Maui 25Sep26 14:15 290 2 5
0000MKUH1 MECO Kula Maui 25Sep26 14:30 200 5 9
0000PHUH1 Pulehu Maui 25Sep26 14:15 220 5 11
0000MNDH1 MECO Naalaea Rd Maui 25Sep26 14:30 210 5 9
0000MURH1 MECO Ulupalakua Maui 25Sep26 14:30 180 9 15
0000LPOH1 Lipoa Maui 25Sep26 14:15 190 8 15
0000MVHH1 MECO Ve erans Hwy Maui 25Sep26 14:30 330 20 29
0000KPDH1 Kealia Pond Maui 25Sep26 14:20 20 20 34
0000MMAH1 MECO Maalaea Maui 25Sep26 14:30 360 17 30
00000P36 Maalaea Bay Maui 25Sep26 14:15 0 0 0
0000HULH1 Hanaula Maui 25Sep26 14:15 60 8 27
0000OLUH1 Olowalu Maui 25Sep26 14:15 60 7 20
0000MMMH1 MECO Mamane Pl Maui 25Sep26 14:30 320 19 27
0000MHOH1 MECO Honoapiilani Maui 25Sep26 14:30 10 27 35
0000MHHH1 MECO Honoapiilani2 Maui 25Sep26 14:30 340 15 25
0000MKEH1 MECO Kealaloloa Rg Maui 25Sep26 14:30 10 29 41
0000MUGH1 MECO Ukumehame Gul Maui 25Sep26 14:30 360 18 34
0000MOOH1 MECO Olowalu Maui 25Sep26 14:30 50 16 37
0000OLUH1 Olowalu Maui 25Sep26 14:15 60 7 20
0000MLPH1 MECO Launiupoko Maui 25Sep26 14:30 260 3 8
0000MLTH1 MECO Launiupoko 2 Maui 25Sep26 14:30 50 16 28
0000MLRH1 MECO Lahainaluna Maui 25Sep26 14:30 220 4 8
0000LWTH1 Lahaina WTP Maui 25Sep26 14:15 240 5 7
0000MKNH1 MECO Kaanapali Maui 25Sep26 14:30 230 5 9
0000PHJH Kapalua-W Maui Maui 25Sep26 14:00 30 20 30
0000HOOH1 Honolua Maui 25Sep26 14:15 120 12 28

0000UPLH1 Upolu Airpor Hawaii 25Sep26 14:15 90 15 23
0000KMMH1 Kaluamakani Hawaii 25Sep26 14:15 50 16 24
0000PMLH1 Puu Mali Hawaii 25Sep26 14:00 90 20 30
0000KNKH1 Kanakaleonui Hawaii 25Sep26 14:15 90 5 7
0000WPNH1 Waipunalei Hawaii 25Sep26 13:30 140 3 10
0000LAUH1 Laupahoehoe Hawaii 25Sep26 14:15 100 6 12
0000SPNH1 Spencer Hawaii 25Sep26 14:15 120 6 11
0000HKUH1 Hakalau Hawaii 25Sep26 13:45 100 3 10
0000KLXH1 Kulaimano Hawaii 25Sep26 14:15 0 2 5
0000PIOH1 Piihonua Hawaii 25Sep26 14:15 50 1 3
0000PHTO Hilo AP Hawaii 25Sep26 14:16 320 6 MSG
0000ILOH1 Hilo Hbr NOS Hawaii 25Sep26 14:24 360 8 10
0000IPIH1 IPIF Hawaii 25Sep26 14:15 30 3 5
0000WEXH1 Waiakea Exp S n Hawaii 25Sep26 14:00 MSG 1 4
0000KEUH1 Keaau Hawaii 25Sep26 14:15 340 3 7
0000PAOH1 Pahoa Hawaii 25Sep26 14:15 20 1 5
0000NHKH1 Nahuku Hawaii 25Sep26 14:15 20 14 25
0000KKUH1 Keaumo Hawaii 25Sep26 14:34 20 12 20
0000MOBH1 Mauna Loa Obs Hawaii 25Sep26 14:00 MSG 18 28
0000PLIH1 Pali 2 Hawaii 25Sep26 14:01 30 19 30
0000KMOH1 Kealakomo Hawaii 25Sep26 13:44 10 19 30
0000KPRH1 Kapapala Hawaii 25Sep26 13:48 30 10 20
0000NENH1 Nene Cabin Hawaii 25Sep26 14:23 80 10 24
0000KIOH1 Kaiholena Hawaii 25Sep26 14:15 360 4 6
0000LKHH1 Lower Kahuku Hawaii 25Sep26 14:23 350 3 13
0000SOPH1 Sou h Poin Hawaii 25Sep26 14:00 60 14 24
0000KOMH1 Kona Hema Hawaii 25Sep26 14:15 230 4 5
0000KRCH1 Kahuku Ranch Hawaii 25Sep26 14:29 300 4 12
0000PHRH1 Puho CS Hawaii 25Sep26 14:22 290 3 7
0000HLNH1 HELCO Lolo Ln Hawaii 25Sep26 14:30 270 2 4
0000HHUH1 HELCO Hualalai Rd Hawaii 25Sep26 14:30 280 2 5
0000KOUH1 Keahuolu Hawaii 25Sep26 14:15 270 2 3
0000PHKO Kona In l AP Hawaii 25Sep26 14:00 230 7 MSG
0000KHOH1 Kaloko-Honokohau Hawaii 25Sep26 14:15 250 5 8
0000PLMH1 Palamanui Hawaii 25Sep26 14:15 230 2 6
0000PWAH1 Puu Waawaa (UHM) Hawaii 25Sep26 14:15 230 0 1
0000KIUH1 Kaiaulu Puu Waawaa Hawaii 25Sep26 14:15 340 6 9
0000KPLH1 Kaupulehu Hawaii 25Sep26 14:36 240 7 10
0000PWWH1 Puu Waawaa Hawaii 25Sep26 14:37 280 4 8
0000HMHH1 HELCO Mamalahoa 2 Hawaii 25Sep26 14:30 280 6 9
0000MMLH1 Mamalahoa Hawaii 25Sep26 14:15 290 1 4
0000HMWH1 HELCO Mamalahoa 3 Hawaii 25Sep26 14:30 40 9 14
0000PULH1 Puuanahulu Hawaii 25Sep26 14:37 40 8 16
0000AHMH1 Ahumoa Hawaii 25Sep26 14:35 320 3 8
0000AIPH1 Aipaloa Hawaii 25Sep26 14:15 360 3 5
0000HSRH1 HELCO Saddle Rd Hawaii 25Sep26 14:30 250 4 6
0000HMYH1 HELCO Mamalahoa Hawaii 25Sep26 14:30 20 19 26
0000HHCH1 HELCO Hokuloa UCC Hawaii 25Sep26 14:30 40 20 31
0000HWRH1 HELCO Waikoloa Rd Hawaii 25Sep26 14:30 50 23 40
0000HWXH1 HELCO Waikoloa 2 Hawaii 25Sep26 14:30 80 25 39
0000WKVH1 Waikoloa Hawaii 25Sep26 14:35 70 21 37
0000HLOH1 HELCO Lalamilo Hawaii 25Sep26 14:30 40 27 36
0000LLAH1 Lalamilo Hawaii 25Sep26 14:15 30 6 15
0000HKWH1 HELCO Kawaihae Rd Hawaii 25Sep26 14:30 50 28 41
0000PKAH1 PTA Kipuka Alala Hawaii 25Sep26 13:55 110 16 26
0000PKWH1 PTA Wes Hawaii 25Sep26 13:56 320 7 15
0000PKMH1 PTA Keamuku Hawaii 25Sep26 13:50 30 0 0
0000PTRH1 PTA Range 17 Hawaii MSG MSG MSG MSG
0000PERH1 Puhe CS Hawaii 25Sep26 14:24 60 9 29
0000KWHH1 Kawaihae NOS Hawaii MSG MSG MSG MSG
0000HHKH1 HELCO Hulukupuna Hawaii 25Sep26 14:30 90 15 25
0000PLAH1 Puuloa Hawaii 25Sep26 14:15 310 36 49
0000HMLH1 HELCO Maluokalani Hawaii MSG MSG MSG MSG
0000HKDH1 HELCO Ala Kahua Hawaii 25Sep26 14:30 220 29 41
0000KHRH1 Kohala Ranch Hawaii 25Sep26 14:35 50 28 43
0000KEHH1 Kehena Hawaii 25Sep26 14:15 10 8 20
```

---

## 7. Offshore Forecast (40-240nm)

- **Resource ID:** off_offshore_forecast
- **Source:** https://forecast.weather.gov/product.php?site=HFO&product=OFF&issuedby=HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
779
FZHW60 PHFO 260301
OFFHFO

Offshore Wa ers Forecas for Hawaii
Na ional Wea her Service Honolulu HI
501 PM HST Fri Sep 25 2026

Hawaiian offshore wa ers beyond 40 nau ical miles ou o 240
nau ical miles including he por ion of he Papahanaumokuakea
Marine Na ional Monumen eas of French Friga e Shoals

Seas given as significan wave heigh , which is he average heigh
of he highes 1/3 of he waves. Individual waves may be more han
wice he significan wave heigh .

PHZ105-261130-
501 PM HST Fri Sep 25 2026

.Synopsis for he Hawaiian offshore wa ers...
S rong winds and hazardous seas will accompany Hurricane Nolo as
i advances nor h and hen wes ward across area wa ers oday
hrough he weekend.

AT 500 PM HST HURRICANE NOLO WAS CENTERED AT 16.9N 155.3W...MOVING N
AT 3 KT

NOLO FORECAST POSITIONS
200 AM HST SATURDAY 17.1N 155.5W
200 PM HST SATURDAY 17.1N 156.4W
200 AM HST SUNDAY 16.9N 157.9W
200 PM HST SUNDAY 16.9N 159.8W
200 AM HST MONDAY 17.7N 161.7W
200 PM HST MONDAY 19.1N 163.2W
200 PM HST TUESDAY 22.0N 164.5W
200 PM HST MONDAY 23.6N 165.5W
200 PM HST TUESDAY 25.0N 168.0W
200 PM HST WEDNESDAY 25.0N 171.0W

PHZ180-261130-
Hawaiian Offshore Wa ers-
501 PM HST Fri Sep 25 2026

...HURRICANE WARNING IN EFFECT...

.TONIGHT...Hurricane condi ions expec ed. E winds 15 o 25 k NW
Half, E 80 o 90 k SE Half. Seas 8 o 14 f . Sca ered
hunders orms SE Wa ers.

.SATURDAY...Hurricane condi ions expec ed. E winds 20 o 30 k NW
Half, E 85 o 95 k SE Half. Seas 8 o 14 f . Isola ed
hunders orms SE Wa ers.
.SATURDAY NIGHT...Hurricane condi ions expec ed. E winds 20 o 30
k NW Half, E 90 o 100 k SE Half. Seas 9 o 14 f . Sca ered
hunders orms SE Wa ers.
.SUNDAY...Hurricane condi ions expec ed. NW Half, E winds 30 o
40 k , rising o 40 o 50 k la e in he af ernoon. SE Half, E
winds 90 o 100 k , diminishing o 50 o 60 k . Seas 9 o 14 f .
Isola ed hunders orms NW Half - sca ered hunders orms SE
Wa ers.
.SUNDAY NIGHT...Hurricane condi ions expec ed. E winds 75 o 85
k NW Half, E 40 o 50 k SE Half. Seas 8 o 14 f . Isola ed
hunders orms S of 20N.
.MONDAY...Hurricane condi ions expec ed. E winds 95 o 105 k NW
Half, E 20 o 30 k SE Half. Seas 7 o 13 f . Isola ed
hunders orms S of 24N.
.TUESDAY...Hurricane condi ions possible. E winds 80 o 90 k NW
Half, E 15 o 25 k SE Half. Seas 6 o 13 f . Isola ed
hunders orms S of 24N.
.WEDNESDAY...Hurricane condi ions possible. SE winds 30 o 40 k
NW Half, E 15 o 25 k SE Half. Seas 6 o 11 f .
```

---

## 8. State Forecast for Hawaii

- **Resource ID:** sfp_state_forecast
- **Source:** https://api.weather.gov/products/types/SFP/locations/HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
{"@id": "https://api.weather.gov/products/a55c50e8-ef57-4b0a-9a1e-9be99cc0ba7a", "id": "a55c50e8-ef57-4b0a-9a1e-9be99cc0ba7a", "wmoCollectiveId": "FPHW60", "issuingOffice": "PHFO", "issuanceTime": "2026-09-26T02:59:00+00:00", "productCode": "SFP", "productName": "State Forecast"}
```

---
