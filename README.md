# CO2 Emissions Analysis: India, United States, and Germany

## Project Overview
This project analyzes historical CO2 emissions per capita for India,
the United States, and Germany using Python.

## Dataset
Source: Our World in Data
Original data source: Global Carbon Budget (2025)
Population data: Various sources (2024)
Unit: Tonnes per person

The dataset includes CO2 emissions from fossil fuels and industrial
processes but excludes land-use change.

Data source: https://ourworldindata.org/grapher/co-emissions-per-capita

## Tools
- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Analysis
1. Loaded and inspected the dataset.
2. Filtered data for three countries.
3. Created historical emissions charts.
4. Compared latest available emissions values.
5. Calculated percentage differences relative to India.
6. Calculated average emissions across available observations.

## Key Findings: 2024
- United States: 14.20 tonnes per person.
- Germany: 6.77 tonnes per person.
- India: 2.20 tonnes per person.

US emissions per person were approximately 545% higher than India's.
Germany's emissions per person were approximately 208% higher than India's.

These are per-person comparisons, not total national emissions.

## Limitations
Historical coverage differs across countries, so their average values
are based on different sets of years. The data represents territorial
emissions rather than consumption-based emissions.

## Visualizations
- country_comparison.png
- india_co2_trend.png
- average_emissions_comparison.png

## Results
- co2_emissions_country_comparison.csv
- average_co2_emissions.csv

## Citation
Global Carbon Budget (2025); Population based on various sources (2024),
with major processing by Our World in Data.

https://ourworldindata.org/grapher/co-emissions-per-capita
