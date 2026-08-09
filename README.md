
````markdown
# CEDS-EDGAR Emissions Inventory Comparison

A Python-based comparison of global emissions inventories, focusing on differences between the Community Emissions Data System (CEDS) and the Emissions Database for Global Atmospheric Research (EDGAR).

This repository is a portfolio version of an emissions-inventory analysis workflow. The included notebook uses sample data to demonstrate data preparation, comparison and visualisation methods.

## Background

CEDS and EDGAR are two widely used global anthropogenic emissions inventories.

**CEDS (Community Emissions Data System)** provides historical emissions by pollutant, country, sector and year and is widely used in atmospheric and climate modelling, including CMIP6-related research.

**EDGAR (Emissions Database for Global Atmospheric Research)** is developed by the European Commission's Joint Research Centre (JRC) and provides global greenhouse-gas and air-pollutant emissions across countries, sectors and time periods.

Although both inventories describe anthropogenic emissions, their estimates can differ because of differences in activity data, emission factors, sector classifications, methodological assumptions and update procedures.

Comparing the inventories helps identify where estimates diverge and where additional harmonisation or uncertainty analysis may be needed.

## Analysis

The workflow focuses on greenhouse gases and air pollutants including:

`CH4` `CO` `CO2` `NH3` `NMVOC` `NOx` `SO2` `N2O`

The notebook demonstrates:

- preparation and cleaning of emissions time series
- aggregation by pollutant and year
- comparison of emissions estimates between inventories
- calculation of absolute and percentage differences
- identification of discrepancies
- visualisation of emissions trends

A typical workflow is:

```text
Emissions data
      |
      v
Data preparation
      |
      v
Aggregation
      |
      v
Inventory comparison
      |
      v
Difference calculation
      |
      v
Visualisation and interpretation
```

The same approach can be extended to country-level, sector-level and spatial comparisons, as well as uncertainty and scenario analysis.

## Repository

```text
foci-emissions-perturbation-analysis/
|
├── notebooks/
|   └── 01_demo_global_trends_sample_data.ipynb
|
├── DISCLAIMER.md
├── README.md
└── requirements.txt
```

## Data

The inventories referenced in this project are publicly available:

| Dataset | Source |
|---|---|
| CEDS | [Zenodo](https://zenodo.org/records/10904361) |
| EDGAR | [European Commission JRC](https://edgar.jrc.ec.europa.eu/) |

The notebook currently uses synthetic/sample data to illustrate the analysis. Original WEMC/FOCI working datasets, project files and unpublished results are not included in this repository.

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Running the Notebook

Clone the repository:

```bash
git clone https://github.com/aurelasakaj-hub/foci-emissions-perturbation-analysis.git
cd foci-emissions-perturbation-analysis
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook notebooks/
```

Open:

```text
01_demo_global_trends_sample_data.ipynb
```

## Project Context

The subject of this repository reflects professional experience gained while working with the **World Energy & Meteorology Council (WEMC)** and contributing to the **FOCI Horizon Europe project**.

My work included emissions-data analysis, CEDS and EDGAR inventory comparison, processing and quality control of large scientific datasets, statistical analysis, energy-sector emissions, and scientific reporting.

The public repository is an independent portfolio demonstration. It does not contain original WEMC/FOCI project code, confidential material, internal datasets, project deliverables or unpublished project results.

### FOCI

**Non-CO2 Forcers and their Climate, Weather, Air Quality and Health Impacts**

Horizon Europe - Grant Agreement **101056783**

## Author

**Aurela Sakaj**  
Climate & Environmental Data Scientist

[GitHub](https://github.com/aurelasakaj-hub) | [LinkedIn](https://www.linkedin.com/in/aurela-sakaj/) | [Email](mailto:sakaura3@gmail.com)

## Disclaimer

See [DISCLAIMER.md](DISCLAIMER.md) for information on project context, data usage and confidentiality.
````
