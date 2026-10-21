# Education (Education)

10 datasets — 14,636 records

> Browse at [listbase.org/en/education/](https://listbase.org/en/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [World Universities and Domains](world-universities.json) | 10,239 | 2297 KB | [CSV](world-universities_EN.csv) | [Excel](world-universities_EN.xlsx) | [View](https://listbase.org/en/education/world-universities/) |
| [Global University Rankings 2025](global-university-rankings.json) | 2,855 | 1916 KB | [CSV](global-university-rankings_EN.csv) | [Excel](global-university-rankings_EN.xlsx) | [View](https://listbase.org/en/education/global-university-rankings/) |
| [US High Schools with Dress Codes](us-schools-dress-code-metadata.json) | 481 | 70 KB | [CSV](us-schools-dress-code-metadata_EN.csv) | [Excel](us-schools-dress-code-metadata_EN.xlsx) | [View](https://listbase.org/en/education/us-schools-dress-code-metadata/) |
| [American Time Use Survey Activities](atus-time-use-activities.json) | 464 | 117 KB | [CSV](atus-time-use-activities_EN.csv) | [Excel](atus-time-use-activities_EN.xlsx) | [View](https://listbase.org/en/education/atus-time-use-activities/) |
| [US College Majors Employment and Earnings](us-college-majors-employment.json) | 173 | 67 KB | [CSV](us-college-majors-employment_EN.csv) | [Excel](us-college-majors-employment_EN.xlsx) | [View](https://listbase.org/en/education/us-college-majors-employment/) |
| [North American Fraternities](north-american-fraternities.json) | 126 | 25 KB | [CSV](north-american-fraternities_EN.csv) | [Excel](north-american-fraternities_EN.xlsx) | [View](https://listbase.org/en/education/north-american-fraternities/) |
| [North American Sororities](north-american-sororities.json) | 96 | 18 KB | [CSV](north-american-sororities_EN.csv) | [Excel](north-american-sororities_EN.xlsx) | [View](https://listbase.org/en/education/north-american-sororities/) |
| [Women in STEM College Majors (US)](us-college-majors-women-in-stem.json) | 76 | 22 KB | [CSV](us-college-majors-women-in-stem_EN.csv) | [Excel](us-college-majors-women-in-stem_EN.xlsx) | [View](https://listbase.org/en/education/us-college-majors-women-in-stem/) |
| [Women's Representation in STEM College Majors](women-in-stem-majors.json) | 76 | 22 KB | [CSV](women-in-stem-majors_EN.csv) | [Excel](women-in-stem-majors_EN.xlsx) | [View](https://listbase.org/en/education/women-in-stem-majors/) |
| [Oldest Universities in the World](oldest-universities-world.json) | 50 | 8 KB | [CSV](oldest-universities-world_EN.csv) | [Excel](oldest-universities-world_EN.xlsx) | [View](https://listbase.org/en/education/oldest-universities-world/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.en.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.en.listbase.org/education/world-universities.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/en/education/)
