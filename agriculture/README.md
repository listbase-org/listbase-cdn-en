# Agriculture (Agriculture)

2 datasets — 712 records

> Browse at [listbase.org/en/agriculture/](https://listbase.org/en/agriculture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [US Rice Production by State 1895–2011](us-rice-production-by-state.json) | 662 | 72 KB | [CSV](us-rice-production-by-state_EN.csv) | [Excel](us-rice-production-by-state_EN.xlsx) | [View](https://listbase.org/en/agriculture/us-rice-production-by-state/) |
| [Most Valuable Crops and Livestock Products Worldwide](global-crop-livestock-production.json) | 50 | 17 KB | [CSV](global-crop-livestock-production_EN.csv) | [Excel](global-crop-livestock-production_EN.xlsx) | [View](https://listbase.org/en/agriculture/global-crop-livestock-production/) |

## Quick Start

```bash
# List all agriculture datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="agriculture") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/agriculture/us-rice-production-by-state.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/agriculture/)
