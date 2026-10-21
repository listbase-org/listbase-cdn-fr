# Environnement (Environment)

2 datasets — 3,123 records

> Browse at [listbase.org/fr/environment/](https://listbase.org/fr/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Centrales électriques en France](fr-centrales-electriques.json) | 3,051 | 1550 KB | [CSV](fr-centrales-electriques_FR.csv) | [Excel](fr-centrales-electriques_FR.xlsx) | [View](https://listbase.org/fr/environment/fr-centrales-electriques/) |
| [Centrales nucléaires en France](fr-centrales-nucleaires.json) | 72 | 30 KB | [CSV](fr-centrales-nucleaires_FR.csv) | [Excel](fr-centrales-nucleaires_FR.xlsx) | [View](https://listbase.org/fr/environment/fr-centrales-nucleaires/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/environment/fr-centrales-electriques.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/environment/)
