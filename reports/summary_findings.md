# Summary of Findings: CEDS vs EDGAR Emissions Comparison (2004-2019)

## Overview

This analysis compares the Community Emissions Data System (CEDS) and Emissions Database for Global Atmospheric Research (EDGAR) inventories for 8 key pollutants in the energy sector from 2004-2019.

## Key Findings

### 1. Global Emissions Trends

| Pollutant | Pattern | Key Finding |
|-----------|---------|-------------|
| CH₄ | Mixed | CEDS higher until 2008, then EDGAR surpasses |
| CO | CEDS > EDGAR | Gap narrows over time |
| CO₂ | EDGAR > CEDS | Gap growing; 1.28M kt difference by 2019 |
| NH₃ | CEDS > EDGAR | Stable gap |
| NMVOC | CEDS > EDGAR | Convergence over time |
| NOx | CEDS > EDGAR | Gap narrowing |
| SO₂ | Mixed | CEDS higher until 2013, then EDGAR surpasses |
| N₂O | CEDS > EDGAR | Consistent gap |

### 2. Energy Sector Subsectors

#### Largest Discrepancies by Subsector

| Subsector | Pollutant | Max Difference (kt) | Primary Countries |
|-----------|-----------|---------------------|-------------------|
| Oil & Natural Gas (1B2b) | CH₄ | 33,311 (2005) | Venezuela, Russia, Algeria |
| Electricity & Heat (1A1a) | CO | 7,611 | Russia, China |
| Electricity & Heat (1A1a) | SO₂ | 9,707 | China, Turkey |
| Solid Fuels (1B1) | NMVOC | 3,846 | India, South Africa |
| Electricity & Heat (1A1a) | NOx | 6,414 | Russia, China |

### 3. Country-Level Insights

**Top Contributors to Discrepancies:**

| Pollutant | Top 3 Countries | Pattern |
|-----------|-----------------|---------|
| CH₄ | Russia, Venezuela, Algeria | CEDS > EDGAR (stable) |
| CO | Russia, China, Uganda | CEDS > EDGAR |
| SO₂ | China, Turkey, Mexico | Mixed (CEDS > then < EDGAR) |
| NMVOC | China, Russia, Saudi Arabia | CEDS > EDGAR |
| NOx | Russia, China, USA | CEDS > EDGAR |

### 4. Emission Perturbations for Climate Scenarios

**Sector-Wide Percentage Differences (2015-2019 average):**

| Sector | Mean Difference (%) | Range (%) |
|--------|---------------------|-----------|
| Oil & Natural Gas | 47.50 | 1.40 - 93.61 |
| Electricity & Heat | 28.79 | 1.89 - 55.68 |
| Petroleum Refining | 16.74 | 2.13 - 31.35 |
| Solid Fuels | 12.04 | 2.92 - 21.15 |

## Methodology Notes

### Key Differences Between Inventories

1. **Emission Factors**: EDGAR uses more country-specific factors; CEDS uses default global factors
2. **Data Integration**: EDGAR integrates satellite data (NOAA VIIRS for flaring)
3. **Sector Classification**: Different aggregation levels require mapping
4. **Update Frequency**: EDGAR updates more frequently; CEDS prioritises long-term consistency

### Uncertainty Implications

- CH₄: ±29% (second highest after N₂O ±50%)
- Highest uncertainty countries: Russia (±40-100%), Venezuela (±50-100%)
- Emerging contributors: Colombia, Algeria, Oman show significant gaps

## References

- Crippa, M. et al. (2022). EDGAR v6.0 Greenhouse Gas Emissions
- Hoesly, R. M. et al. (2018). Historical anthropogenic emissions from CEDS
- Solazzo, E. et al. (2021). Uncertainties in EDGAR inventory
