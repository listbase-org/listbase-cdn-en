# ListBase CDN — English (en)

Open dataset collection for **English** (English).
5957 datasets across 25 categories with 2,715,190 total records.

> Browse and download at [https://listbase.org/en/](https://listbase.org/en/)

## Categories

| Category | Datasets |
|----------|----------|
| [Agriculture](agriculture/) | 2 |
| [Business](business/) | 1 |
| [Culture & Religion](culture/) | 224 |
| [Economy](economy/) | 26 |
| [Education](education/) | 10 |
| [Entertainment](entertainment/) | 262 |
| [Environment](environment/) | 212 |
| [Finance & Trade](finance/) | 393 |
| [Food & Nutrition](food/) | 48 |
| [Geography](geography/) | 2957 |
| [Health](health/) | 24 |
| [History](history/) | 11 |
| [Language](language/) | 28 |
| [Mathematics](math/) | 12 |
| [Music](music/) | 16 |
| [Politics](politics/) | 243 |
| [Reference](reference/) | 646 |
| [Science](science/) | 82 |
| [Society](society/) | 6 |
| [Sports](sports/) | 284 |
| [Technology](tech/) | 105 |
| [Time & Calendar](time/) | 4 |
| [Tourism](tourism/) | 1 |
| [Transport](transport/) | 356 |
| [Units & Measurements](units/) | 4 |

## Usage

### Browse on the web
Visit [listbase.org/en/](https://listbase.org/en/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.en.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.en.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.en.listbase.org/geography/th-central-provinces_EN.xlsx
curl -O https://cdn.en.listbase.org/geography/th-central-provinces_EN.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.en.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.en.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_EN.csv   # CSV download
│   └── {dataset}_EN.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
