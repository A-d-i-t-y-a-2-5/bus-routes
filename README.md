# bus-routes

A small Python project for exploring and working with bus stop and route data.

## Features

- **Data:** Includes a sample dataset of bus stops in JSON format.
- **Notebooks:** Analytical and exploratory work is provided in a Jupyter notebook.

## Data

The repository contains raw data used by the notebooks and scripts:

- **Bus stops:** [data/bus_stops.json](data/bus_stops.json)

## Quick start

1. Install UV (Windows PowerShell):

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

2. Install dependencies:

```bash
uv sync
```

3. Open the example notebook:

- [notebooks/stops.ipynb](notebooks/stops.ipynb)

## Usage

- Inspect or process the bus stop data in `data/bus_stops.json`.
- Use the notebook to run analyses and visualizations.

## Development

- Project metadata and dependencies are defined in [pyproject.toml](pyproject.toml).
- Add scripts or modules as needed and update the notebook examples.