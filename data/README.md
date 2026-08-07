# FOCI Emissions Perturbation Analysis: CEDS vs EDGAR Comparison

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

**Quantifying discrepancies between CEDS and EDGAR emissions inventories to derive perturbations for CMIP6 climate scenarios**

---

## Overview

This repository contains a comprehensive analysis comparing two major global emissions inventories:

- **CEDS** (Community Emissions Data System) - v2024_04_01
- **EDGAR** (Emissions Database for Global Atmospheric Research) - v8.0/v8.1

The analysis covers **8 key pollutants** (CH₄, CO, CO₂, NH₃, NMVOC, NOx, SO₂, N₂O) over the **2004-2019** period, with a focus on the **energy sector**.

This work was conducted as part of the **FOCI** (Fostering Opportunities for Climate Innovation) project under **Horizon Europe**.

---

## Key Findings

| Pollutant | Pattern | Key Insight |
|-----------|---------|-------------|
| **CH₄** | Mixed | CEDS higher until 2008, then EDGAR surpasses |
| **CO₂** | EDGAR > CEDS | Gap growing; ~1.28M kt difference by 2019 |
| **SO₂** | Mixed | CEDS higher until 2013, then EDGAR exceeds |
| **NMVOC** | CEDS > EDGAR | Convergence over time |
| **NOx** | CEDS > EDGAR | Gap narrowing; ~11,210 kt by 2019 |

- **Oil & Natural Gas**: Largest CH₄ discrepancies (up to 33,311 kt in 2005)
- **Top Countries**: Russia, Venezuela, and China account for majority of discrepancies
- **Perturbations**: Derived for CMIP6 SSP2-4.5 scenarios

---

## Repository Structure

```
foci-emissions-perturbation-analysis/
├── data/
│   └── README.md                # Data source information
├── notebooks/
│   └── 01_global_trends.ipynb   # Global emissions analysis
├── reports/
│   ├── images/                  # Visualisations
│   └── summary_findings.md      # Key results summary
├── DISCLAIMER.md                # NDA and privacy disclaimer
├── LICENSE                      # MIT License
├── README.md                    # This file
└── requirements.txt             # Python dependencies
```

---

## Getting Started

### Prerequisites

```bash
Python 3.8+
Jupyter Notebook or Jupyter Lab
```

### Installation

```bash
git clone https://github.com/aurelasakaj-hub/foci-emissions-perturbation-analysis.git
cd foci-emissions-perturbation-analysis
pip install -r requirements.txt
jupyter notebook notebooks/
```

---

## Data Sources

| Dataset | Version | Source |
|---------|---------|--------|
| CEDS | v2024_04_01 | [Zenodo](https://zenodo.org/records/10904361) |
| EDGAR | v8.0/v8.1 | [JRC Portal](https://edgar.jrc.ec.europa.eu/) |

---

## Author

**Aurela Sakaj**

- [LinkedIn](https://www.linkedin.com/in/auraela-sakaj)
- [GitHub](https://github.com/aurelasakaj-hub)
- [Email](mailto:sakaura3@gmail.com)

---

## Acknowledgements

This work was performed under the **FOCI** project (Grant Agreement No 101003536), funded by the European Union's Horizon 2020 research and innovation programme.
