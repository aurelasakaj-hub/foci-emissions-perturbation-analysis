# Data Sources

## Access Information

### CEDS (Community Emissions Data System)
- **Version**: v2024_04_01
- **Source**: Höglund-Isaksson et al. (2024)
- **Link**: https://zenodo.org/records/10904361
- **Period**: 1750-2019 (analysis uses 2004-2019)

### EDGAR (Emissions Database for Global Atmospheric Research)
- **Version**: v8.0 (2023) / v8.1 (2024)
- **Source**: European Commission, Joint Research Centre
- **Link**: https://edgar.jrc.ec.europa.eu/dataset_ap81
- **Period**: 1970-2022 (analysis uses 2004-2019)

## Data Processing Notes

1. **Sector Mapping**: CEDS and EDGAR use different sector classifications. See notebooks for mapping details.
2. **Units**: All emissions are in kilotons (kt) unless otherwise specified.
3. **Pollutants**: CH₄, CO, CO₂, NH₃, NMVOC, NOx, SO₂, N₂O

## Data Disclaimer

**Raw data files are not stored in this repository due to size and licensing restrictions.**

Please download directly from the sources above to reproduce the analysis.
