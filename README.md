# MIRAI PLASTISENSE — Reference-matched functional prototype

## Run
Extract this ZIP and open `index.html` in Chrome/Edge. Keep `chamber-camera-reference.jpg` beside it. No Node/npm required.

## Dashboard and automation
- Dashboard is implemented using real HTML/CSS components and interactive charts—not a screenshot with invisible click zones.
- On startup, the app loads 120 generated stormwater demonstration scenarios, maps fields automatically, calculates descriptive statistics and starts a baseline model training run.
- Sensor panel uses project labels: Chamber Water Level, Inlet Flow Rate, Outlet Particle Count, ESP32 Temperature, Battery Level. Values replay from the current dataset row.
- Live Monitoring supports continuous row playback; Test Runs calculates removal efficiency from paired counts; Analytics imports CSVs, maps fields, trains/evaluates a baseline regression model, charts statistics and exports reports; Settings and About remain available.

## Data integrity
The built-in rows are generated demo data, not real environmental observations or live ESP32 readings. Training/holdout metrics on these generated rows only demonstrate the software pipeline and do not validate real-world accuracy. Import curated measured and labelled data for scientific evaluation. The chamber image is a visual reference, not a live camera feed.

Research links for later curation:
- DURUM urban stormwater microplastics: https://osf.io/9cgu4/
- MULTISOURCE stormwater sensor time series: https://zenodo.org/records/15374917
- California OPC/SFEI microplastic data: https://data.ca.gov/@california-ocean-protection-council/microplastic-and-microparticle-data-from-surface-water-san-francisco-bay-and-adjacent-sanctuari
# Mirai
# Mirai
