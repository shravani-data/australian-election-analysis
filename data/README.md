# Data Directory

The datasets used in this project are not included in this repository due to their large file size.

All datasets are publicly available from the following sources:

## Australian Electoral Commission (AEC)

### Election Results Data
Used for analysing first preference voting patterns in the 2022 and 2025 Australian Federal Elections.

Source:
Australian Electoral Commission  
https://results.aec.gov.au/

Datasets used:
- House of Representatives Distribution of Preferences by Candidate by Division (2022)
- House of Representatives Distribution of Preferences by Candidate by Division (2025)

---

## Australian Electoral Commission (AEC)

### Electoral Boundaries and Demographic Classifications

Source:
Australian Electoral Commission  
https://www.aec.gov.au/electorates/

Datasets used:
- Electoral Division GIS boundaries
- Demographic Classification of Electoral Divisions (2025)

---

## Australian Bureau of Statistics (ABS)

### 2021 Census of Population and Housing

Source:
Australian Bureau of Statistics  
https://www.abs.gov.au/census

Datasets used:
- General Community Profile (G01)
- Selected Characteristics (G02)
- Income Profile (G17A)

---

## Data Reproduction

The datasets can be downloaded from the above sources and placed inside this `data/` directory.

The analysis workflow in:

`australian_election_analysis.qmd`

will process the raw datasets and generate the required intermediate datasets used for analysis.

Generated files such as:
- `data_classified.csv`
- `electorate_change.csv`

are intentionally excluded from version control and can be recreated by running the analysis code.
