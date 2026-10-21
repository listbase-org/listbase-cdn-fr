# Transport (Transport)

1 datasets — 14,369 records

> Browse at [listbase.org/fr/transport/](https://listbase.org/fr/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Codes UN/LOCODE — France (ports, aéroports, terminaux)](fr-unlocode.json) | 14,369 | 9895 KB | [CSV](fr-unlocode_FR.csv) | [Excel](fr-unlocode_FR.xlsx) | [View](https://listbase.org/fr/transport/fr-unlocode/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/transport/fr-unlocode.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/transport/)
