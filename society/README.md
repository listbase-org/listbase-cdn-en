# Society (Society)

6 datasets — 5,514 records

> Browse at [listbase.org/en/society/](https://listbase.org/en/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [US Police Officers Killed in the Line of Duty](us-police-officers-killed-line-of-duty.json) | 4,999 | 2576 KB | [CSV](us-police-officers-killed-line-of-duty_EN.csv) | [Excel](us-police-officers-killed-line-of-duty_EN.xlsx) | [View](https://listbase.org/en/society/us-police-officers-killed-line-of-duty/) |
| [World Giving Index by Country](world-giving-index.json) | 159 | 44 KB | [CSV](world-giving-index_EN.csv) | [Excel](world-giving-index_EN.xlsx) | [View](https://listbase.org/en/society/world-giving-index/) |
| [Crime Index by Country](crime-index-by-country.json) | 144 | 15 KB | [CSV](crime-index-by-country_EN.csv) | [Excel](crime-index-by-country_EN.xlsx) | [View](https://listbase.org/en/society/crime-index-by-country/) |
| [French Departmental Crime and Morality Statistics 1830s](french-departmental-crime-morality-1830s.json) | 86 | 54 KB | [CSV](french-departmental-crime-morality-1830s_EN.csv) | [Excel](french-departmental-crime-morality-1830s_EN.xlsx) | [View](https://listbase.org/en/society/french-departmental-crime-morality-1830s/) |
| [US Police Force Local Residency by City](police-locals-city-demographics.json) | 75 | 19 KB | [CSV](police-locals-city-demographics_EN.csv) | [Excel](police-locals-city-demographics_EN.xlsx) | [View](https://listbase.org/en/society/police-locals-city-demographics/) |
| [US Hate Crimes by State](us-hate-crimes-by-state.json) | 51 | 28 KB | [CSV](us-hate-crimes-by-state_EN.csv) | [Excel](us-hate-crimes-by-state_EN.xlsx) | [View](https://listbase.org/en/society/us-hate-crimes-by-state/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/society/us-police-officers-killed-line-of-duty.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/society/)
