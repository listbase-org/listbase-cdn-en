# Time & Calendar (Time & Calendar)

4 datasets — 333 records

> Browse at [listbase.org/en/time/](https://listbase.org/en/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Public Holidays by Country — Summary](country-holidays-summary.json) | 201 | 41 KB | [CSV](country-holidays-summary_EN.csv) | [Excel](country-holidays-summary_EN.xlsx) | [View](https://listbase.org/en/time/country-holidays-summary/) |
| [World Timezones](world-timezones.json) | 108 | 30 KB | [CSV](world-timezones_EN.csv) | [Excel](world-timezones_EN.xlsx) | [View](https://listbase.org/en/time/world-timezones/) |
| [Comprehensive Chinese Zodiac Animals Dataset (12 Signs)](time-chinese-zodiac.json) | 12 | 11 KB | [CSV](time-chinese-zodiac_EN.csv) | [Excel](time-chinese-zodiac_EN.xlsx) | [View](https://listbase.org/en/time/time-chinese-zodiac/) |
| [Complete Western Zodiac Signs Data](time-zodiac-signs.json) | 12 | 9 KB | [CSV](time-zodiac-signs_EN.csv) | [Excel](time-zodiac-signs_EN.xlsx) | [View](https://listbase.org/en/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/time/country-holidays-summary.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/time/)
