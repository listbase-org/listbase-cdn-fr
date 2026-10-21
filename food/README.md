# Alimentation (Food & Nutrition)

1 datasets — 3,042 records

> Browse at [listbase.org/fr/food/](https://listbase.org/fr/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restaurants du Guide Michelin en France](fr-restaurants-michelin.json) | 3,042 | 3257 KB | [CSV](fr-restaurants-michelin_FR.csv) | [Excel](fr-restaurants-michelin_FR.xlsx) | [View](https://listbase.org/fr/food/fr-restaurants-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/food/fr-restaurants-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/food/)
