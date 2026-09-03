# Bees Dashboard

A Dash dashboard that visualizes the percentage of honey bee colonies impacted across the United States by year and cause.

## Features

- Interactive year and state filters
- Choropleth map of affected bee colonies
- Bar chart showing colony impact by cause
- Plotly dark theme

## Requirements

- Python 3
- Dash
- pandas
- Plotly

Install the dependencies with:

```bash
pip install dash pandas plotly
```

## Run the dashboard

```bash
python bees_dashboard.py
```

Then open the local URL shown in the terminal, usually `http://127.0.0.1:8050/`.

## Data

The dashboard currently loads the dataset from the remote URL defined in `bees_dashboard.py`. A copy of the dataset is also included in this repository as `intro_bees.csv`.
