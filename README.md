# CEDS–EDGAR Emissions Inventory Comparison

**Python portfolio demonstration for comparing global emissions inventories**

## Overview

This repository demonstrates a Python workflow for comparing emissions data from two major global inventories:

- **CEDS** — Community Emissions Data System
- **EDGAR** — Emissions Database for Global Atmospheric Research

The analysis is motivated by questions such as:

- How do different emissions inventories compare over time?
- Where do their estimates diverge?
- How can emissions data be cleaned, aggregated and visualised consistently?
- How can differences between inventories be quantified and interpreted?

The workflow is relevant to greenhouse gases and air pollutants including **CH₄, CO, CO₂, NH₃, NMVOC, NOx, SO₂ and N₂O**, with particular interest in emissions from the energy sector.

The project is informed by professional experience gained while contributing to emissions-data analysis within the **FOCI Horizon Europe project** at the World Energy & Meteorology Council (WEMC).

> **Note:** The public notebook in this repository uses synthetic/sample data to demonstrate the analytical workflow. It does not reproduce original WEMC or FOCI project code, datasets, deliverables or unpublished results.

---

## About CEDS and EDGAR

### CEDS

**CEDS (Community Emissions Data System)** is a global historical emissions inventory widely used in atmospheric and climate research.

It provides anthropogenic emissions by variables such as pollutant, country, sector and year and has been used in climate-model experiments, including work associated with CMIP6.

### EDGAR

**EDGAR (Emissions Database for Global Atmospheric Research)** is a global emissions inventory developed by the European Commission's Joint Research Centre (JRC).

It provides greenhouse-gas and air-pollutant emissions across countries, economic sectors and time periods.

### Why Compare Them?

CEDS and EDGAR can provide different estimates for the same pollutant, country or sector because emissions inventories may differ in:

- activity data;
- emission factors;
- sector classifications;
- aggregation methods;
- temporal coverage;
- methodological assumptions; and
- update cycles.

Comparing inventories helps identify where estimates diverge and where further investigation, harmonisation or uncertainty assessment may be useful.

---

## What This Repository Demonstrates

The public notebook demonstrates how to:

- load and structure emissions time-series data;
- clean and prepare environmental datasets;
- compare values from two emissions inventories;
- calculate absolute and percentage differences;
- aggregate emissions by pollutant and year;
- visualise emissions trends;
- identify discrepancies between datasets; and
- structure a clear and reproducible Python analysis.

The aim is to demonstrate environmental data-analysis skills and scientific reasoning rather than reproduce an official FOCI analysis.

---

## Analytical Workflow

```text
Emissions data
      ↓
Data cleaning and preparation
      ↓
Aggregation by pollutant and year
      ↓
Inventory comparison
      ↓
Absolute and percentage differences
      ↓
Visualisation
      ↓
Interpretation
A more extensive emissions-inventory analysis can also include:

sector and subsector comparisons;
country-level analysis;
spatial analysis;
inventory harmonisation;
uncertainty assessment;
climate-scenario analysis; and
emissions perturbations for climate and air-quality modelling.
Repository Structure
foci-emissions-perturbation-analysis/
│
├── notebooks/
│   └── 01_demo_global_trends_sample_data.ipynb
│
├── DISCLAIMER.md
├── README.md
└── requirements.txt
Data Sources

The emissions inventories referenced in this project are publicly available.

Dataset	Description	Source
CEDS	Community Emissions Data System	Zenodo
EDGAR	Emissions Database for Global Atmospheric Research	European Commission JRC

The notebook currently included in this repository uses synthetic/sample data to illustrate the workflow.

No original WEMC/FOCI working datasets, processed project files or unpublished project results are included.

Tools

The demonstration uses:

Python
pandas
NumPy
Matplotlib
Jupyter Notebook
Getting Started
Requirements
Python 3.8+
Jupyter Notebook or JupyterLab
Installation

Clone the repository:

git clone https://github.com/aurelasakaj-hub/foci-emissions-perturbation-analysis.git
cd foci-emissions-perturbation-analysis

Install the required packages:

pip install -r requirements.txt

Launch Jupyter:

jupyter notebook notebooks/

Then open:

01_demo_global_trends_sample_data.ipynb
Professional Context

During my work with the World Energy & Meteorology Council (WEMC), I contributed to the FOCI Horizon Europe project.

My work included experience with:

emissions-data collection and analysis;
CEDS and EDGAR emissions inventories;
processing and quality control of large scientific datasets;
emissions-inventory comparison and harmonisation;
statistical analysis;
energy-sector emissions;
climate and air-quality applications; and
scientific and technical reporting.

This repository is an independent portfolio demonstration and does not contain original WEMC/FOCI project code, confidential information, internal project datasets, project deliverables or unpublished project results.

FOCI Project

FOCI — Non-CO₂ Forcers and their Climate, Weather, Air Quality and Health Impacts

Programme: Horizon Europe
Grant Agreement: 101056783

FOCI investigates non-CO₂ climate forcers and their impacts on climate, weather, air quality and health.

Author

Aurela Sakaj

Climate & Environmental Data Scientist | Meteorology | Emissions | Climate Data

GitHub:aurelasakaj-hub
LinkedIn: https://www.linkedin.com/in/aurela-sakaj/
Email: sakaura3@gmail.com
Disclaimer

This repository is intended for professional portfolio and demonstration purposes.

See DISCLAIMER.md for additional information about data usage, project context and confidentiality.
