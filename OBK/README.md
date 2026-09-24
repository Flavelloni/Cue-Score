# Oslo BK Fargo data

This folder contains generated rating data for Oslo BK.

- `player_fargo_ratings.csv` contains current ratings, ratings calculated
  without the latest tournament, each player's latest tournament date, and a
  flag showing participation in the latest tournament.
- `latest_processed_tournament.json` identifies the newest tournament included
  in the calculations.
- `tournaments/` contains compressed CueScore API responses used for
  incremental ingestion.

The private `Flavelloni/OBK-fargo` repository owns the calculation code and its
scheduled GitHub Actions workflow. This public repository contains generated
data only.
