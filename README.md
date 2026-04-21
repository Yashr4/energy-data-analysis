# Sustainable Electrical Systems – Coursework 1

Analysis of a US wind power plant using MATLAB, covering capacity factor 
calculations, wind speed modelling, and energy output optimisation.

## Overview

This coursework analyses a specific wind power plant in the United States 
using data from the EIA-860 and EIA-923 surveys (2019). The analysis includes:

- Identifying plant location, turbine type, and hub height (EIA-860)
- Calculating annual capacity factor from hourly wind speed data
- Comparing calculated vs. observed capacity factor (EIA-923)
- Plotting the probability density function of wind speed
- Estimating energy output gains across 10+ levels of increased rated capacity

## Files

| File | Description |
|------|-------------|
| `Yash_Runghoo_02276750.mlx` | MATLAB Live Script – main analysis and report |
| `Yash_Runghoo_02276750.csv` | Hourly wind speed data (2019) for the plant location |
| `Yash_Runghoo_02276750.pdf` | PDF export of the Live Script |

## Data Sources

- [EIA-860 (2023)](https://www.eia.gov/electricity/data/eia860/) – Annual Electric Generator Survey
- [EIA-923 (2019)](https://www.eia.gov/electricity/data/eia923/) – Power Plant Operations Report
- Wind speed data sourced from [NREL Wind Toolkit](https://www.nrel.gov/grid/wind-toolkit.html)

## Tools

- MATLAB Live Script (.mlx)
- EIA open datasets (Excel)
