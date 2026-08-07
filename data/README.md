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
