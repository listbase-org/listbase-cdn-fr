# ListBase CDN — Français (fr)

Open dataset collection for **Français** (French).
544 datasets across 9 categories with 1,324,195 total records.

> Browse and download at [https://listbase.org/fr/](https://listbase.org/fr/)

## Categories

| Category | Datasets |
|----------|----------|
| [Culture et religion (Culture & Religion)](culture/) | 2 |
| [Éducation (Education)](education/) | 20 |
| [Environnement (Environment)](environment/) | 2 |
| [Alimentation (Food & Nutrition)](food/) | 1 |
| [Géographie (Geography)](geography/) | 368 |
| [Référence (Reference)](reference/) | 124 |
| [Sport (Sports)](sports/) | 11 |
| [Temps et calendrier (Time & Calendar)](time/) | 15 |
| [Transport](transport/) | 1 |

## Usage

### Browse on the web
Visit [listbase.org/fr/](https://listbase.org/fr/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.fr.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.fr.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.fr.listbase.org/geography/th-central-provinces_FR.xlsx
curl -O https://cdn.fr.listbase.org/geography/th-central-provinces_FR.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.fr.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.fr.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_FR.csv   # CSV download
│   └── {dataset}_FR.xlsx  # Excel download
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
