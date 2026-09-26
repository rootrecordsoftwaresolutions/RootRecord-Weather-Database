# Kauai County Weather Report

> **Level 1 county aggregate — deterministically assembled from preserved source-layer records.**

- **Generated:** 2026-09-25T20:41:28-10:00 HST
- **Report created:** 2026-09-25T20:41:28-10:00 HST
- **County:** Kauai County
- **Source level:** 0 Level Processing
- **Current report sections:** 12
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

## 5. Hawaii Rainfall Summary direct product

- **Resource ID:** hfo_rra_direct
- **Source:** https://forecast.weather.gov/product.php?issuedby=HFO&product=RRA&site=hfo
- **Source layer:** Official Sources
- **County assignment:** explicit-text

```text
194
SRHW80 PHFO 260546
RRAHFO

Hawaii Rainfall Summary
National Weather Service Honolulu HI
745 PM HST Fri Sep 25 2026

:
.B HFO  0925 H  DH19 /DRH-03/PPT/DRH-06/PPQ/DRH-12/PPK/DRH-24/PPD
:
:Automated rain gage reports from around the State of Hawaii.
:These are provisional reports that have not been quality
:controlled.
:
:T=Trace Rainfall, M=Missing Data
:
:Precipitation totals ending  7 PM HST
:
:Island of Kauai                                   Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
:       Windward/Mauka Sites
MKAH1 : Makaha Ridge (RAWS)         :    0.00  /  0.00  /  0.00  /  0.00
PLRH1 : Puu Lua (RAWS)              :    0.00  /  0.00  /  0.00  /  0.00
WKRH1 : Waiakoali (USGS)            :    0.17  /  0.18  /  0.20  /  0.25
KLOH1 : Kilohana (USGS)             :    0.60  /  0.67  /  1.16  /  1.43
MCRH1 : Mohihi Crossing (USGS)      :    0.11  /  0.12  /  0.16  /  0.22
WLGH1 : Waialae (USGS)              :    0.01  /  0.01  /  0.01  /  0.03
LLMH1 : Lower Limahuli (UHM)        :    0.07  /  0.08  /  0.08  /  0.12
WNHH1 : Wainiha (12010)             :    0.12  /  0.13  /  0.14  /  0.23
WIPH1 : Waipa (UHM)                 :    0.14  /  0.14  /  0.15  /  0.24
HNIH1 : Hanalei (12009)             :    0.10  /  0.10  /  0.12  /  0.18
WLLH1 : Mount Waialeale (USGS)      :      M   /    M   /    M   /    M
PRIH1 : Princeville Airport (12011) :    0.04  /  0.04  /  0.04  /  0.06
CMGH1 : Common Ground (UHM)         :    0.09  /  0.09  /  0.09  /  0.11
HLIH1 : Hanalei (RAWS)              :    0.11  /  0.12  /  0.13  /  0.16
MLDH1 : Moloaa Dairy (RAWS)         :    0.00  /  0.00  /  0.00  /  0.00
ANHH1 : Anahola (12001)             :    0.00  /  0.00  /  0.00  /  0.00
KPIH1 : Kapahi (12003)              :    0.05  /  0.05  /  0.07  /  0.08
WLDH1 : N Wailua Ditch (USGS)       :    0.04  /  0.04  /  0.08  /  0.11
WUHH1 : Wailua (12005)              :    0.08  /  0.13  /  0.19  /  0.19
WIRH1 : Waiahi Rain Gage (USGS)     :    0.10  /  0.10  /  0.25  /  0.27
LIHH1 : Lihue Var. Stn. (12006)     :    0.15  /  0.15  /  0.19  /  0.19
HNMH1 : Hanamaulu (UHM)             :    0.16  /  0.17  /  0.22  /  0.23
HLI   : Lihue Airport (ASOS)        :    0.01  /  0.03  /  0.04  /  0.05
:       Leeward Sites
OMAH1 : Omao (12004)                :    0.07  /  0.07  /  0.10  /  0.11
LNTH1 : Lawai NTBG (UHM)            :    0.05  /  0.05  /  0.06  /  0.06
KHEH1 : Kalaheo (12008)             :    0.04  /  0.05  /  0.06  /  0.07
PAKH1 : Port Allen (HSOIS)          :    0.00  /  0.00  /  0.00  /  0.00
HNPH1 : Hanapepe (12002)            :    0.00  /  0.00  /  0.00  /  0.00
POPH1 : Puu Opae (RAWS)             :    0.00  /  0.00  /  0.00  /  0.00
WHGH1 : Waimea Heights (RAWS)       :    0.00  /  0.00  /  0.00  /  0.00
WMTH1 : Waimea Tank (12007)         :    0.00  /  0.00  /  0.00  /  0.00
MNRH1 : Mana (RAWS)                 :    0.00  /  0.00  /  0.00  /  0.00
:
:Island of Oahu                                    Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
:       Windward/Mauka Sites
KAHH1 : Kahuku (13027)              :    0.00  /  0.00  /  0.00  /  0.00
KTAH1 : Kahuku Training Area (RAWS) :    0.00  /  0.00  /  0.00  /  0.00
KFWH1 : Kii (RAWS)                  :    0.00  /  0.00  /  0.00  /  0.00
PUNH1 : Punaluu Pump (13013)        :    0.05  /  0.05  /  0.10  /  0.14
PNSH1 : Punaluu Stream (USGS)       :    0.02  /  0.07  /  0.18  /  0.23
KNRH1 : Kahana (USGS)               :    0.06  /  0.06  /  0.19  /  0.31
HAKH1 : Hakipuu Mauka (13004)       :    0.01  /  0.01  /  0.13  /  0.31
WPPH1 : Waihee Pump (13002)         :    0.02  /  0.04  /  0.06  /  0.12
WHSH1 : Waiahole (USGS)             :    0.03  /  0.04  /  0.06  /  0.10
OFRH1 : Oahu Forest NWR (USFWS)     :    0.01  /  0.01  /  0.06  /  0.09
AHUH1 : Ahuimanu Loop (13005)       :    0.01  /  0.03  /  0.05  /  0.06
HRRH1 : Heeia NERR (NOAA/NOS)       :    0.01  /  0.05  /  0.07  /  0.12
LULH1 : Luluku (13016)              :    0.00  /  0.00  /  0.00  /  0.00
NRSH1 : Nuuanu Res No. 1 (UHM)      :    0.00  /  0.00  /  0.02  /  0.09
KWIH1 : Kalawahine (UHM)            :    0.01  /  0.01  /  0.06  /  0.23
LYOH1 : Lyon (UHM)                  :    0.00  /  0.00  /  0.09  /  0.33
MNLH1 : Manoa Lyon Arboretum (13023):    0.00  /  0.01  /  0.08  /  0.33
STVH1 : St. Stephens (13006)        :    0.00  /  0.02  /  0.05  /  0.16
MAUH1 : Maunawili (13008)           :      M   /    M   /    M   /    M
OFSH1 : Olomana Fire Station (13009):    0.00  /  0.00  /  0.00  /  0.04
WMLH1 : Waimanalo (13011)           :    0.00  /  0.00  /  0.04  /  0.07
BELH1 : Bellows AFS (HSOIS)         :    0.00  /  0.00  /  0.00  /  0.00
KMHH1 : Kamehame (13012)            :    0.00  /  0.00  /  0.02  /  0.08
HAJH1 : Hawaii Kai Golf Crse (13015):    0.00  /  0.00  /  0.01  /  0.17
:       Leeward/Central Sites
KUXH1 : Kaluanui (UHM)              :    0.00  /  0.01  /  0.04  /  0.13
NIUH1 : Niu Valley (13001)          :    0.00  /  0.00  /  0.11  /  0.24
PFSH1 : Palolo Fire Station (13010) :    0.00  /  0.00  /  0.06  /  0.17
HNL   : Honolulu Airport (ASOS)             See note at bottom  :
MOAH1 : Moanalua (13003)            :    0.00  /  0.01  /  0.03  /  0.09
MOGH1 : Moanalua RG (USGS)          :    0.04  /  0.15  /  0.18  /  0.39
TNLH1 : Tunnel RG (USGS)            :    0.07  /  0.12  /  0.26  /  0.39
PACH1 : Palisades (13020)           :    0.01  /  0.02  /  0.03  /  0.05
WAWH1 : Waiawa C.F. (13025)         :    0.01  /  0.01  /  0.02  /  0.02
MITH1 : Mililani (13022)            :    0.01  /  0.01  /  0.01  /  0.01
SCBH1 : Schofield Barracks (RAWS)   :    0.00  /  0.00  /  0.00  /  0.00
SCEH1 : Schofield East (RAWS)       :      M   /    M   /    M   /    M
WAFH1 : Wheeler Airfield            :    0.00  /  0.00  /  0.00  /  0.00
POAH1 : Poamoho (13018)             :    0.00  /  0.00  /  0.00  /  0.00
KRGH1 : Kalahee Ridge (UHM)         :    0.02  /  0.02  /  0.05  /  0.05
KMRH1 : Kamananui Stream (USGS)     :    0.06  /  0.07  /  0.16  /  0.17
PPRH1 : Pupukea Road (USGS)         :    0.07  /  0.07  /  0.13  /  0.15
PMHH1 : Poamoho RG 1 (USGS)         :    0.03  /  0.07  /  0.19  /  0.40
DLGH1 : Dillingham (RAWS)           :    0.00  /  0.00  /  0.00  /  0.00
AALH1 : Kaala (UHM)                 :    0.06  /  0.13  /  0.24  /  0.28
PECH1 : Waipio (13019)              :    0.00  /  0.00  /  0.00  /  0.00
KUNH1 : Kunia Substation (13021)    :    0.00  /  0.00  /  0.00  /  0.00
HOFH1 : Honouliuli (RAWS)           :    0.00  /  0.00  /  0.00  /  0.00
PTWH1 : Ewa Beach USGS (13024)      :    0.00  /  0.00  /  0.00  /  0.00
HJR   : Kalaeloa Airport (ASOS)             See note at bottom  :
PLHH1 : Palehua (RAWS)              :    0.01  /  0.01  /  0.02  /  0.02
LUAH1 : Lualualei (13017)           :    0.00  /  0.00  /  0.00  /  0.00
WNVH1 : Waianae Valley (RAWS)       :    0.00  /  0.00  /  0.00  /  0.00
WBHH1 : Waianae Boat Harbor (HSOIS) :    0.00  /  0.00  /  0.00  /  0.00
WAIH1 : Waianae (13014)             :      M   /    M   /    M   /    M
MKHH1 : Makaha Stream (USGS)        :    0.00  /  0.00  /  0.00  /  0.01
MKRH1 : Makua Range (RAWS)          :    0.00  /  0.00  /  0.00  /  0.00
KKRH1 : Kuaokala (RAWS)             :    0.00  /  0.00  /  0.00  /  0.00
:
:Island of Molokai                                 Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
KOPH1 : Keopukaloa (UHM)            :    0.00  /  0.00  /  0.00  /  0.00
HOMH1 : Honolimaloo (UHM)           :    0.04  /  0.04  /  0.04  /  0.10
KMLH1 : Kamalo (14013)              :    0.00  /  0.00  /  0.00  /  0.00
MKPH1 : Makapulapai (RAWS)          :    0.00  /  0.00  /  0.00  /  0.02
PAFH1 : Puu Alii (RAWS)             :    0.04  /  0.04  /  0.15  /  0.56
MLKH1 : Molokai 1 (RAWS)            :      M   /    M   /    M   /    M
KACH1 : Kaunakakai Mauka (14004)    :    0.00  /  0.00  /  0.00  /  0.00
HMK   : Molokai Airport (ASOS)      :    0.00  /  0.00  /    T   /    T
:
:Island of Lanai                                   Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
LANH1 : Lanai City (14012)          :    0.00  /  0.00  /  0.00  /  0.00
HNY   : Lanai Airport (ASOS)        :    0.00  /  0.00  /  0.00  /  0.00
LNIH1 : Lanai 1 (RAWS)              :    0.00  /  0.00  /  0.00  /  0.00
:
:Island of Kahoolawe                               Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
KAOH1 : Kaneloa (RAWS)              :      M   /    M   /    M   /    M
:
:Island of Maui                                    Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
:       Windward Sites
HNAH1 : Hana Airport (HSOIS)        :      M   /    M   /    M   /    M
WWKH1 : West Wailuaiki (USGS)       :    0.24  /  0.51  /  0.94  /  1.81
EBYH1 : EMI Baseyard (UHM)          :    0.02  /  0.04  /  0.04  /  0.31
AIKH1 : Haiku (14001)               :    0.01  /  0.01  /  0.01  /  0.08
HOG   : Kahului Airport (ASOS)      :    0.00  /  0.00  /  0.00  /    T
WUKH1 : Wailuku (14007)             :    0.00  /  0.00  /  0.00  /  0.00
KHKH1 : Kahakuloa (14002)           :    0.00  /  0.00  /  0.00  /  0.00
PKKH1 : Puu Kukui (USGS)            :    0.07  /  0.08  /  1.13  /  2.42
:       Leeward/Upcountry Sites
NKUH1 : Na Kula (RAWS)              :    0.00  /  0.00  /  0.00  /  0.00
KPNH1 : Kepuni (USGS)               :    0.00  /  0.00  /  0.00  /  0.00
PILH1 : Piiholo (UHM)               :    0.06  /  0.06  /  0.08  /  0.18
WKTH1 : Waikamoi Treeline (UHM)     :    0.20  /  0.21  /  0.23  /  0.52
PUKH1 : Pukalani (14006)            :    0.00  /  0.00  /  0.00  /  0.00
KBSH1 : Kula Branch Station (14008) :      M   /    M   /    M   /    M
KLGH1 : Kula Ag (UHM)               :    0.00  /  0.00  /  0.00  /  0.00
PHQH1 : Park HQ (UHM)               :    0.03  /  0.03  /  0.03  /  0.03
NNEH1 : Nene Nest (UHM)             :    0.03  /  0.03  /  0.03  /  0.03
SUMH1 : Summit (UHM)                :    0.00  /  0.00  /  0.00  /  0.00
KLFH1 : Kula 1 (RAWS)               :    0.00  /  0.00  /  0.00  /  0.00
KKNH1 : Kahikinui 1 (RAWS)          :    0.00  /  0.00  /  0.00  /  0.00
KMEH1 : Kamehamenui 1 (RAWS)        :    0.00  /  0.00  /  0.00  /  0.00
KKEH1 : Keokea (UHM)                :    0.00  /  0.00  /  0.00  /  0.00
ULUH1 : Ulupalakua (14003)          :    0.00  /  0.00  /  0.00  /  0.00
LPOH1 : Lipoa (UHM)                 :    0.00  /  0.00  /  0.00  /  0.00
KHIH1 : Kihei #2 (14009)            :      M   /    M   /  0.00  /    M
KPDH1 : Kealia Pond (USFWS)         :    0.00  /  0.00  /  0.00  /  0.00
WCCH1 : Waikapu Country Club (14005):    0.00  /  0.00  /  0.00  /  0.00
HULH1 : Hanaula (UHM)               :    0.00  /  0.00  /  0.01  /  0.14
OLUH1 : Olowalu (UHM)               :    0.00  /  0.00  /  0.01  /  0.02
LAHH1 : Lahainaluna (14011)         :    0.00  /  0.00  /  0.00  /  0.00
LWTH1 : Lahaina WTP (UHM)           :    0.00  /  0.00  /  0.00  /  0.00
HOOH1 : Honolua (UHM)               :    0.00  /  0.00  /  0.00  /  0.05
:
:Island of Hawaii                                  Inches
:ID     Location                         3-Hr    6-Hr   12-Hr   24-Hr
:       Windward Sites
UPLH1 : Upolu Airport (HSOIS)       :    0.03  /  0.07  /  0.20  /  0.20
KMMH1 : Kaluamakani (UHM)           :    0.18  /  0.30  /  0.30  /  0.30
KWSH1 : Kawainui Stream (USGS)      :    1.23  /  1.62  /  2.50  /  3.94
KUUH1 : Kamuela Upper (15002)       :    0.43  /  0.63  /  1.03  /  1.55
KMUH1 : Kamuela (15005)             :    0.23  /  0.37  /  0.39  /  0.49
HNKH1 : Honokaa (15010)             :    0.86  /  1.14  /  1.28  /  1.95
PMLH1 : Puu Mali (RAWS)             :    0.22  /  0.41  /  0.42  /  0.42
WPNH1 : Waipunalei (UHM)            :      M   /    M   /  0.21  /    M
KNKH1 : Kanakaleonui (UHM)          :    0.92  /  1.82  /  2.06  /  2.07
LPHH1 : Laupahoehoe PD (15001)      :    0.04  /  0.94  /  1.44  /  1.85
LAUH1 : Laupahoehoe (UHM)           :    1.92  /  3.53  /  4.04  /  4.80
SPNH1 : Spencer (UHM)               :    0.20  /  1.24  /  2.03  /  4.62
HKUH1 : Hakalau (RAWS)              :    1.21  /  1.79  /  2.09  /  2.18
KLXH1 : Kulaimano (UHM)             :    0.00  /  0.35  /  0.91  /  1.27
NLIH1 : Honolii Stream (USGS)       :    0.32  /  0.79  /  1.47  /  2.40
SDQH1 : Saddle Quarry (USGS)        :    1.05  /  1.58  /  2.08  /  2.38
PIOH1 : Piihonua (UHM)              :    0.43  /  0.93  /  1.70  /  2.84
PIIH1 : Piihonua (15016)            :    0.00  /  0.00  /  0.01  /  0.03
IPIH1 : IPIF (UHM)                  :    0.00  /  0.38  /  1.20  /  1.54
WKAH1 : Waiakea Uka (15017)         :    0.02  /  0.31  /  1.19  /  1.71
WEXH1 : Waiakea Exp Stn (NOAA/CRN)  :    0.00  /  0.25  /  0.72  /  0.83
HTO   : Hilo Airport (ASOS)         :      T   /  0.08  /  0.89  /  1.18
PHAH1 : Pahoa (15015)               :    0.00  /  0.53  /  1.43  /  1.80
PAOH1 : Pahoa (UHM)                 :    0.02  /  0.45  /  1.14  /  1.42
MTVH1 : Mountain View (15014)       :    0.07  /  0.62  /  1.69  /  2.05
GLNH1 : Glenwood (15013)            :    1.04  /  1.30  /  2.01  /  2.82
:       Leeward Sites
MOBH1 : Mauna Loa Ob Stn (NOAA/CRN) :    0.34  /  0.50  /  0.53  /  0.53
NHKH1 : Nahuku (UHM)                :    0.86  /  1.49  /  1.92  /  2.21
KKUH1 : Keaumo (RAWS)               :    0.45  /  0.87  /  0.89  /  0.89
KMOH1 : Kealakomo (RAWS)            :    0.01  /  0.17  /  0.19  /  0.20
PLIH1 : Pali 2 (RAWS)               :    0.07  /  0.11  /  0.11  /  0.11
KPRH1 : Kapapala (RAWS)             :    0.02  /  0.02  /  0.02  /  0.04
KAYH1 : Kapapala Ranch (15003)      :    0.00  /  0.00  /  0.00  /  0.00
PPLH1 : Pahala (15004)              :    0.03  /  0.06  /  0.06  /  0.13
KIOH1 : Kaiholena (UHM)             :      M   /    M   /    M   /    M
NENH1 : Nene Cabin (RAWS)           :    0.40  /  0.69  /  0.70  /  0.70
SOPH1 : South Point (HSOIS)         :    0.14  /  0.17  /  0.17  /  0.18
LKHH1 : Lower Kahuku (RAWS)         :    0.36  /  0.66  /  0.66  /  0.67
KRCH1 : Kahuku Ranch (RAWS)         :    0.01  /  0.01  /  0.01  /  0.01
KOMH1 : Kona Hema (UHM)             :    0.00  /  0.01  /  0.01  /  0.02
PHRH1 : Puho CS (RAWS)              :    0.00  /  0.00  /  0.00  /  0.00
HAUH1 : Honaunau (15007)            :    0.01  /  0.01  /  0.01  /  0.02
KLEH1 : Kealakekua (15008)          :    0.00  /  0.00  /  0.00  /  0.02
WIHH1 : Waiaha Stream (15009)       :    0.01  /  0.01  /  0.01  /  0.01
KOUH1 : Keahuolu (UHM)              :    0.01  /  0.01  /  0.01  /  0.01
KHOH1 : Kaloko-Honokohau (RAWS)     :    0.00  /  0.00  /  0.00  /  0.00
HKO   : Kona Intl Airport (ASOS)    :    0.00  /  0.00  /  0.00  /  0.00
PLMH1 : Palamanui (UHM)             :    0.00  /  0.00  /  0.01  /  0.01
KIRH1 : Kiholo RG (USGS)            :    0.00  /  0.00  /  0.00  /  0.00
KPLH1 : Kaupulehu (RAWS)            :    0.00  /  0.00  /  0.00  /  0.00
PULH1 : Puuanahulu (RAWS)           :    0.00  /  0.00  /  0.00  /  0.00
MMLH1 : Mamalahoa (UHM)             :    0.00  /  0.00  /  0.00  /  0.00
PWWH1 : Puu Waawaa (RAWS)           :    0.00  /  0.00  /  0.00  /  0.00
PWAH1 : Puu Waawaa (UHM)            :    0.00  /  0.00  /  0.00  /  0.00
KIUH1 : Kaiaulu Puu Waawaa (UHM)    :    0.00  /  0.00  /  0.00  /  0.00
PKAH1 : Pohakuloa Kipuka Alala RAWS :    0.00  /  0.00  /  0.00  /  0.00
PTRH1 : Pohakuloa Range 17 (RAWS)   :    0.00  /  0.00  /  0.00  /  0.00
PKWH1 : Pohakuloa West (RAWS)       :    0.00  /  0.00  /  0.00  /  0.00
PKMH1 : Pohakuloa Keamuku (RAWS)    :    0.00  /  0.00  /  0.00  /  0.00
AHMH1 : Ahumoa (RAWS)               :    0.00  /  0.00  /  0.00  /  0.00
WHIH1 : Waikii (15011)              :    0.00  /  0.00  /  0.00  /  0.00
LLAH1 : Lalamilo (UHM)              :    0.09  /  0.12  /  0.17  /  0.22
WKVH1 : Waikoloa (RAWS)             :    0.00  /  0.00  /  0.00  /  0.00
PERH1 : Puhe CS (RAWS)              :    0.00  /  0.00  /  0.00  /  0.00
KHRH1 : Kohala Ranch (RAWS)         :    0.00  /  0.00  /  0.00  /  0.00
KASH1 : Kahua Ranch (15006)         :    0.21  /  0.30  /  0.42  /  0.55
KEHH1 : Kehena (UHM)                :    0.80  /  1.13  /  1.64  /  2.24
PLAH1 : Puuloa (UHM)                :    0.22  /  0.28  /  0.28  /  0.28
.END

Service Note
Due to software decoder issues, rainfall totals for Honolulu Airport (PHNL)
and Kalaeloa Airport (PHJR) are temporarily unavailable.
Daily totals for both sites are available in the CF6 product on the web at
https://www.weather.gov/wrh/Climate?wfo=hfo
Select the Observed Weather tab and choose the Preliminary Monthly Climate Data
(CF6) product.
We apologize for the inconvenience and hope to have this issue resolved soon.

$$
```

---

## 6. HFO statewide surf observations direct page

- **Resource ID:** hfo_surf_reports_direct
- **Source:** https://www.weather.gov/hfo/surfreports
- **Source layer:** Official Sources
- **County assignment:** NWS-zone-county-correlation

```text
948
SXHW80 PHFO 260115
OMRHFO

SURF OBSERVATIONS
NATIONAL WEATHER SERVICE HONOLULU HI
315 PM HST FRI SEP 25 2026

FULL FACE SURF OBSERVATIONS ARE TAKEN BY COUNTY LIFE GUARDS AND
COOPERATIVE OBSERVERS AND RELAYED TO THE NATIONAL WEATHER SERVICE
FOR DISSEMINATION. THESE OBSERVATIONS ARE NOT QUALITY CONTROLLED.

HIZ003-004-029>031-260100-
KAUAI-

LOCATION        TIME   SURF HEIGHT DIR   PER                  REMARKS
KEE          1235 PM           2-5  NE     9
HAENA        1235 PM           2-5  NE     9
HANALEI      1235 PM           0-2
ANAHOLA      1235 PM           3-6 ENE     9
KEALIA       1235 PM          6-10 ENE    10
LYDGATE      1235 PM          4-8+ ENE    10
POIPU        1235 PM           2-4
SALT POND    1235 PM           2-4
KEKAHA       1235 PM           1-3
$$

HIZ006-007-009>011-032>036-260100-
OAHU-

LOCATION        TIME   SURF HEIGHT DIR PER         WIND      REMARKS
DIAMOND HEAD
SUNSET
WAIKIKI      1145 AM           0-1            ENE 10-15       CANOES
SANDY BEACH  1145 AM           2-3            ENE 15-20  SHORE BREAK
MAKAPUU      1145 AM           4-6            ENE 10-15
EHUKAI       1145 AM           0-1             NE 10-15
MAKAHA       1145 AM           0-1               VRB 05
$$

HIZ015>018-022-045>050-260100-
MAUI-MOLOKAI-LANAI-KAHOOLAWE-

LOCATION        TIME   SURF HEIGHT   DIR         WIND      REMARKS
KANAHA       1108 AM           1-3          NE 10-20+  PARTLY CLDY
BALDWIN SHOR 1109 AM           1-2           NE 15-25  PARTLY CLDY
BALDWIN OUTE 1109 AM           3-6           NE 15-25  PARTLY CLDY
HOOKIPA      1110 AM           1-4           NE 10-20  MOSTLY CLDY
KAMAOLE I    1111 AM           1-2           NE 10-20        SUNNY
KAMAOLE III  1112 AM           0-1           NE 20-30  PARTLY CLDY
HANAKAOO
FLEMING
$$

HIZ023-026>028-051>054-260100-
BIG ISLAND OF HAWAII-

LOCATION        TIME   SURF HEIGHT   DIR         WIND      REMARKS
RICHARDSONS  1101 AM           2-3     E      VRB 0-5  OVERCAST/RA
HONOLII      1102 AM           3-5            L/V 0-5         RAIN
PUNALU`U
ISAAC HALE   1103 AM          5-6+            NE 5-10         RAIN
HAPUNA
KAHALUU      1105 AM           3-5    NW      L/V 0-5     OVERCAST
MAGIC SANDS  1106 AM           0-1            L/V 0-5     OVERCAST
KUA BAY      1107 AM    1-2 OCNL 3           SW 10-15     OVERCAST
$$

LEGEND
   SURF HEIGHT              - Reported in feet
   WIND AND SWELL DIRECTION - Reported in 16 pt compass
   PERIOD /PER/             - Reported in seconds
   VISIBILITY /VIS/         - Reported in statute miles
   CLARITY                  - Water clarity
   TIME                     - Hawaiian Standard Time
   WIND SPEED               - Reported in miles per hour
   + /IN SURF HEIGHT/       - Occasionally higher sets
   0 /IN SURF HEIGHT/       - Flat

$$
```

---

## 7. High Seas Forecast N. Pacific

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

## 8. Hourly Wind/Precip Observations

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

## 9. Offshore Forecast (40-240nm)

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

## 10. Radar status/outage text messages

- **Resource ID:** ftm_radar_status
- **Source:** /hfo/FTM
- **Source layer:** Official Sources
- **County assignment:** explicit-text

```text
Kauai Radar (PHKI/SOK)
No outage message at this time.

----

Molokai Radar (PHMO/HMO)
858
NOUS60 PHFO 242239
FTMHMO

WSR-88D NOTIFICATION
NATIONAL WEATHER SERVICE HONOLULU HI
1239 PM HST THU SEP 24 2026

WSR-88D PHMO/HMO MOLOKAI RADAR IS BACK IN SERVICE.

----

Upolu Point/North Kohala Radar (PHKM/UPP)
646
NOUS60 PHFO 252159
FTMHKM

WSR-88D NOTIFICATION
NATIONAL WEATHER SERVICE HONOLULU HI
1159 AM HST FRI SEP 25 2026

WSR-88D PHKM/UPP UPOLU POINT RADAR IS BACK IN SERVICE.

LF

----

Naalehu/South Hawaii (PHWA/HWC)
No outage message at this time.
```

---

## 11. State Forecast for Hawaii

- **Resource ID:** sfp_state_forecast
- **Source:** https://api.weather.gov/products/types/SFP/locations/HFO
- **Source layer:** Official Sources
- **County assignment:** statewide

```text
{"@id": "https://api.weather.gov/products/a55c50e8-ef57-4b0a-9a1e-9be99cc0ba7a", "id": "a55c50e8-ef57-4b0a-9a1e-9be99cc0ba7a", "wmoCollectiveId": "FPHW60", "issuingOffice": "PHFO", "issuanceTime": "2026-09-26T02:59:00+00:00", "productCode": "SFP", "productName": "State Forecast"}
```

---

## 12. Statewide Surf Observations

- **Resource ID:** surfreports_statewide_observations
- **Source:** /hfo/surfreports
- **Source layer:** Official Sources
- **County assignment:** NWS-zone-county-correlation

```text
948
SXHW80 PHFO 260115
OMRHFO

SURF OBSERVATIONS
NATIONAL WEATHER SERVICE HONOLULU HI
315 PM HST FRI SEP 25 2026

FULL FACE SURF OBSERVATIONS ARE TAKEN BY COUNTY LIFE GUARDS AND
COOPERATIVE OBSERVERS AND RELAYED TO THE NATIONAL WEATHER SERVICE
FOR DISSEMINATION. THESE OBSERVATIONS ARE NOT QUALITY CONTROLLED.

HIZ003-004-029>031-260100-
KAUAI-

LOCATION        TIME   SURF HEIGHT DIR   PER                  REMARKS
KEE          1235 PM           2-5  NE     9
HAENA        1235 PM           2-5  NE     9
HANALEI      1235 PM           0-2
ANAHOLA      1235 PM           3-6 ENE     9
KEALIA       1235 PM          6-10 ENE    10
LYDGATE      1235 PM          4-8+ ENE    10
POIPU        1235 PM           2-4
SALT POND    1235 PM           2-4
KEKAHA       1235 PM           1-3
$$

HIZ006-007-009>011-032>036-260100-
OAHU-

LOCATION        TIME   SURF HEIGHT DIR PER         WIND      REMARKS
DIAMOND HEAD
SUNSET
WAIKIKI      1145 AM           0-1            ENE 10-15       CANOES
SANDY BEACH  1145 AM           2-3            ENE 15-20  SHORE BREAK
MAKAPUU      1145 AM           4-6            ENE 10-15
EHUKAI       1145 AM           0-1             NE 10-15
MAKAHA       1145 AM           0-1               VRB 05
$$

HIZ015>018-022-045>050-260100-
MAUI-MOLOKAI-LANAI-KAHOOLAWE-

LOCATION        TIME   SURF HEIGHT   DIR         WIND      REMARKS
KANAHA       1108 AM           1-3          NE 10-20+  PARTLY CLDY
BALDWIN SHOR 1109 AM           1-2           NE 15-25  PARTLY CLDY
BALDWIN OUTE 1109 AM           3-6           NE 15-25  PARTLY CLDY
HOOKIPA      1110 AM           1-4           NE 10-20  MOSTLY CLDY
KAMAOLE I    1111 AM           1-2           NE 10-20        SUNNY
KAMAOLE III  1112 AM           0-1           NE 20-30  PARTLY CLDY
HANAKAOO
FLEMING
$$

HIZ023-026>028-051>054-260100-
BIG ISLAND OF HAWAII-

LOCATION        TIME   SURF HEIGHT   DIR         WIND      REMARKS
RICHARDSONS  1101 AM           2-3     E      VRB 0-5  OVERCAST/RA
HONOLII      1102 AM           3-5            L/V 0-5         RAIN
PUNALU`U
ISAAC HALE   1103 AM          5-6+            NE 5-10         RAIN
HAPUNA
KAHALUU      1105 AM           3-5    NW      L/V 0-5     OVERCAST
MAGIC SANDS  1106 AM           0-1            L/V 0-5     OVERCAST
KUA BAY      1107 AM    1-2 OCNL 3           SW 10-15     OVERCAST
$$

LEGEND
   SURF HEIGHT              - Reported in feet
   WIND AND SWELL DIRECTION - Reported in 16 pt compass
   PERIOD /PER/             - Reported in seconds
   VISIBILITY /VIS/         - Reported in statute miles
   CLARITY                  - Water clarity
   TIME                     - Hawaiian Standard Time
   WIND SPEED               - Reported in miles per hour
   + /IN SURF HEIGHT/       - Occasionally higher sets
   0 /IN SURF HEIGHT/       - Flat

$$
```

---
