# 🌺 RootRecord Weather Database

> **Continuously updated, source-preserving weather data and media collected by the RootRecord weather system for Hawaiʻi.**

## 🛰️ Live GOES-18 Hawaii GeoColor

![GOES-18 Hawaii GeoColor](https://raw.githubusercontent.com/rootrecordsoftwaresolutions/RootRecord-Weather-Database/main/Hawai%27i/hfo/cdn.star.nesdis.noaa.gov/GOES18/ABI/SECTOR/hi/GEOCOLOR/GOES18-HI-GEOCOLOR-600x600/GOES18-HI-GEOCOLOR-600x600_current.gif)

This banner is the current locally collected **GOES-18 Hawaii — GeoColor** product. The image is updated through the existing weather-data synchronization pipeline.

## 🌐 What This Is

This repository contains the weather data and media collected by the RootRecord weather system.

Tracked content includes current products, archived products, JSON, HTML, text, satellite imagery, weather graphics, GIFs, hurricane data, reports, and database metadata.

The raw collected source material remains the authoritative local record. Generated reports are derived presentation layers and do not replace the original source data.

## 📚 Report Layers

- **Official Sources** — readable official-source records grouped by issuing source.
- **0 Level Processing** — statewide Hawaiʻi reporting.
- **1 County Processing** — deterministically routed county/geographic reporting.
- **Archives** — historical versions retained when substantive report content changes.

## 🌦️ Live Hawaiʻi Statewide Report

The full continuously regenerated statewide report is maintained by the weather reporting pipeline.

**[View the live statewide weather report →](https://github.com/rootrecordsoftwaresolutions/Solar-Pacific-RootRecord-Server/blob/main/weather/reports/README.md)**

The report is generated from the same current product sections as the Level 0 statewide report. Official-source records and raw source data remain preserved separately.

## 🔄 Automatic Updating

Weather reports and media are generated locally from the collected database and published through the existing RootRecord Weather Database synchronization workflow.

This README is the database repository's public landing page and is kept aligned with the weather reporting architecture.

## 🛡️ Source Integrity

- Original source identity is retained.
- Raw source material is preserved separately from generated reports.
- Official-source records remain isolated from processing levels.
- County routing uses deterministic geographic rules.
- Products without authoritative geographic assignment are not silently copied into counties.
- Current reports are archived when substantive content changes.

## 📁 Local Source

`/home/rootrecord/Database/WEATHER`

## 🔗 Repository

https://github.com/rootrecordsoftwaresolutions/RootRecord-Weather-Database

---

_Generated and maintained as part of the RootRecord weather reporting system._
