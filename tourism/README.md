# Tourism (Tourism)

1 datasets — 1,561 records

> Browse at [listbase.org/en/tourism/](https://listbase.org/en/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Chicago Airbnb Listings — Prices and Ratings](chicago-airbnb-listings.json) | 1,561 | 516 KB | [CSV](chicago-airbnb-listings_EN.csv) | [Excel](chicago-airbnb-listings_EN.xlsx) | [View](https://listbase.org/en/tourism/chicago-airbnb-listings/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/tourism/chicago-airbnb-listings.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/tourism/)
