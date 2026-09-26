# RootRecord Weather Database

This repository contains the weather data and media collected by the RootRecord weather system.

## Local source

/home/rootrecord/Database/WEATHER

## Scope

This repository is the data/media side only. Weather collection code remains in the separate Solar-Pacific-RootRecord-Server repository.

Tracked content includes current products, archived products, JSON, HTML, text, satellite imagery, weather graphics, GIFs, hurricane data, and database metadata.

## Synchronization

The database is synchronized independently from the weather poller.

Local additions and changes are pushed to GitHub.

Deletions made on GitHub are propagated to this local database.

Git synchronization never starts, stops, restarts, kills, or signals the weather poller.

## Repository

https://github.com/rootrecordsoftwaresolutions/RootRecord-Weather-Database
