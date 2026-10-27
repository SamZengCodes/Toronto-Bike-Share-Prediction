# Toronto Bike Share Predictiion

Predicting when Bike Share Toronto stations will run out of bikes, using historical trip data and like station status.

## Status
Work in Progress: setting up data collection.

## Data
- Trip history: [Bike Share Toronto Ridership Data](https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/) (Toronto Open Data)
- Live station status: Bike Share Toronto GBFS feed

Data files are not included in this repo. Download the trip CSVs into `data/raw/`.

## Setup
    python -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt

