# Sport (Sports)

11 datasets — 7,214 records

> Browse at [listbase.org/fr/sports/](https://listbase.org/fr/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Athlètes olympiques français 1896–2022 (6295)](fr-athletes-olympiques-francais.json) | 6,295 | 3019 KB | [CSV](fr-athletes-olympiques-francais_FR.csv) | [Excel](fr-athletes-olympiques-francais_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-athletes-olympiques-francais/) |
| [Ligue 1 2025-26 — Calendrier et résultats](fr-ligue-1-fixtures-2025-26.json) | 306 | 105 KB | [CSV](fr-ligue-1-fixtures-2025-26_FR.csv) | [Excel](fr-ligue-1-fixtures-2025-26_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-ligue-1-fixtures-2025-26/) |
| [Ligue 2 2025-26 — Calendrier et résultats](fr-ligue-2-fixtures-2025-26.json) | 306 | 107 KB | [CSV](fr-ligue-2-fixtures-2025-26_FR.csv) | [Excel](fr-ligue-2-fixtures-2025-26_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-ligue-2-fixtures-2025-26/) |
| [Coupe de France 2024-25 — Calendrier et résultats](fr-coupe-de-france-fixtures-2024-25.json) | 200 | 69 KB | [CSV](fr-coupe-de-france-fixtures-2024-25_FR.csv) | [Excel](fr-coupe-de-france-fixtures-2024-25_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-coupe-de-france-fixtures-2024-25/) |
| [Clubs de football en France](fr-clubs-football.json) | 86 | 27 KB | [CSV](fr-clubs-football_FR.csv) | [Excel](fr-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-clubs-football/) |
| [Stades de football en France](fr-stades-football.json) | 10 | 4 KB | [CSV](fr-stades-football_FR.csv) | [Excel](fr-stades-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-stades-football/) |
| [Clubs de football en Île-de-France](fr-ile-de-france-clubs-football.json) | 4 | 3 KB | [CSV](fr-ile-de-france-clubs-football_FR.csv) | [Excel](fr-ile-de-france-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-ile-de-france-clubs-football/) |
| [Clubs de football en Hauts-de-France](fr-hauts-de-france-clubs-football.json) | 2 | 2 KB | [CSV](fr-hauts-de-france-clubs-football_FR.csv) | [Excel](fr-hauts-de-france-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-hauts-de-france-clubs-football/) |
| [Clubs de football en Occitanie](fr-occitanie-clubs-football.json) | 2 | 2 KB | [CSV](fr-occitanie-clubs-football_FR.csv) | [Excel](fr-occitanie-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-occitanie-clubs-football/) |
| [Clubs de football en Pays de la Loire](fr-pays-de-la-loire-clubs-football.json) | 2 | 3 KB | [CSV](fr-pays-de-la-loire-clubs-football_FR.csv) | [Excel](fr-pays-de-la-loire-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-pays-de-la-loire-clubs-football/) |
| [Clubs de football en Nouvelle-Aquitaine](fr-nouvelle-aquitaine-clubs-football.json) | 1 | 2 KB | [CSV](fr-nouvelle-aquitaine-clubs-football_FR.csv) | [Excel](fr-nouvelle-aquitaine-clubs-football_FR.xlsx) | [View](https://listbase.org/fr/sports/fr-nouvelle-aquitaine-clubs-football/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/sports/fr-athletes-olympiques-francais.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/sports/)
