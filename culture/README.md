# Culture et religion (Culture & Religion)

2 datasets — 1,459 records

> Browse at [listbase.org/fr/culture/](https://listbase.org/fr/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Musées en France (Museums in France)](fr-musees.json) | 1,414 | 304 KB | [CSV](fr-musees_FR.csv) | [Excel](fr-musees_FR.xlsx) | [View](https://listbase.org/fr/culture/fr-musees/) |
| [Patrimoine mondial de l'UNESCO en France](fr-patrimoine-mondial-unesco.json) | 45 | 48 KB | [CSV](fr-patrimoine-mondial-unesco_FR.csv) | [Excel](fr-patrimoine-mondial-unesco_FR.xlsx) | [View](https://listbase.org/fr/culture/fr-patrimoine-mondial-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/culture/fr-musees.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/culture/)
