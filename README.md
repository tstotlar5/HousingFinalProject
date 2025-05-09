# BAIS3250_FinalProject  
**Project Title:** Housing Affordability in Johnson County, Iowa  
**Course:** BAIS 3250 – Data Wrangling  

## Table of Contents
- [data/](#data)  
  - raw/  
  - interim/  
  - processed/  
- [notebooks/](#notebooks)  
- [docs/](#docs)  
- [Data Dictionary](#Data-dictionary)  
- [Links & Sources](#links--sources)  
- [References](#references)  

---

## data/

### raw/  
Raw downloads from source sites, unmodified.  
- `ACS_B19013_JohnsonCo_2013.csv`  
- `ACS_B19013_JohnsonCo_2018.csv`  
- `ACS_B19013_JohnsonCo_2023.csv`  
- `ACS_B25106_JohnsonCo_2013.csv`  
- `ACS_B25106_JohnsonCo_2018.csv`  
- `ACS_B25106_JohnsonCo_2023.csv`  
- `historical_transactions_2013.csv`  
- `historical_transactions_2018.csv`  
- `historical_transactions_2023.csv`  

### interim/  
Cleaned and combined intermediate files.  
- `iowa_city_housing_combined.csv`  
- `ACS_JohnsonCo_combined.csv`  

### processed/  
Final merged dataset used for analysis.  
- `master_housing_plus_ACS.csv`  

---

## notebooks/
- `DataScrape and Integration.ipynb` – Code for scraping 2013/2018/2023 sales and merging with ACS data  
- `Visualizations.ipynb` – Exploratory plots, hypothesis tests, and ML modeling  

---

## docs/
- `Final Project Report.pdf` – Full written report (Introduction, Data, Analysis, Conclusion)  

---

## Data Dictionary

| Field                  | Type     | Description                                                    |
|------------------------|----------|----------------------------------------------------------------|
| Parcel Number          | Integer  | County parcel identifier                                       |
| Sale Date              | Date     | Date of property sale                                          |
| Sale Amount            | Float    | Sale price in U.S. dollars                                     |
| Address                | String   | Full street address                                            |
| Style                  | String   | Architectural style (e.g. Ranch, 2‑Story)                      |
| Year Built             | Integer  | Year the structure was built                                   |
| Total SF               | Integer  | Total residential square footage                               |
| Lot Area               | Float    | Lot size in square feet                                        |
| Appraised Value        | Float    | County assessed value in U.S. dollars                          |
| Recording              | String   | County recording reference                                     |
| Year                   | Integer  | Transaction year (2013, 2018, or 2023)                         |
| Cost_Burden_Proportion | Float    | Fraction of households spending > 30 % on housing (ACS)        |
| Median_Income          | Integer  | Median household income in U.S. dollars (ACS)                  |

---

## Links & Sources

- **Assessor’s search page**  
  https://iowacity.iowaassessors.com/showResSaleSearch.php?  
- **ACS Table B19013**: Median Household Income  
  https://api.census.gov/data/2023/acs/acs5/subject/variables.html  
- **ACS Table B25106**: Housing Costs as % of Income  
  https://api.census.gov/data/2023/acs/acs5/subject/variables.html  

---

## References

1. “Johnson County, Iowa Housing Market Report December 2024.” Rocket Homes, 2024.  
2. “Iowa Housing Market: Home Prices & Trends.” Houzeo, 2024.  
3. “Johnson County seeks proposals for affordable housing project.” The Gazette, February 20, 2025.  
4. “Nearly Half of Renter Households Are Cost‑Burdened, Proportions Differ by Race.” U.S. Census Bureau, September 12, 2024.  
5. “The state of affordable housing in the US.” Pew Research Center, October 25, 2024.  

---

**Last updated:** 2025‑05‑09  
