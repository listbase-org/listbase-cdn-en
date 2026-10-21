# Units & Measurements (Units & Measurements)

4 datasets — 216 records

> Browse at [listbase.org/en/units/](https://listbase.org/en/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Comprehensive Unit Conversion Factors Dataset](units-conversions.json) | 83 | 16 KB | [CSV](units-conversions_EN.csv) | [Excel](units-conversions_EN.xlsx) | [View](https://listbase.org/en/units/units-conversions/) |
| [Temperature Conversion Matrix Dataset](units-temperatures.json) | 55 | 10 KB | [CSV](units-temperatures_EN.csv) | [Excel](units-temperatures_EN.xlsx) | [View](https://listbase.org/en/units/units-temperatures/) |
| [International Shoe Size Conversion Chart Dataset](units-shoe-sizes.json) | 43 | 8 KB | [CSV](units-shoe-sizes_EN.csv) | [Excel](units-shoe-sizes_EN.xlsx) | [View](https://listbase.org/en/units/units-shoe-sizes/) |
| [Clothing Size Standards Dataset](units-clothing-sizes.json) | 35 | 10 KB | [CSV](units-clothing-sizes_EN.csv) | [Excel](units-clothing-sizes_EN.xlsx) | [View](https://listbase.org/en/units/units-clothing-sizes/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/units/units-conversions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/units/)
