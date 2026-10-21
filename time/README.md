# Temps et calendrier (Time & Calendar)

15 datasets — 11,395 records

> Browse at [listbase.org/fr/time/](https://listbase.org/fr/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Jours fériés en France (toutes collectivités, 2000-2031)](fr-jours-feries.json) | 4,848 | 798 KB | [CSV](fr-jours-feries_FR.csv) | [Excel](fr-jours-feries_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries/) |
| [Jours fériés au Luxembourg – Liste complète (1901–2030)](fr-luxembourg-jours-feries-completos.json) | 1,699 | 843 KB | [CSV](fr-luxembourg-jours-feries-completos_FR.csv) | [Excel](fr-luxembourg-jours-feries-completos_FR.xlsx) | [View](https://listbase.org/fr/time/fr-luxembourg-jours-feries-completos/) |
| [Jours fériés - Alsace-Moselle (2000-2031)](fr-jours-feries-alsace-moselle.json) | 415 | 38 KB | [CSV](fr-jours-feries-alsace-moselle_FR.csv) | [Excel](fr-jours-feries-alsace-moselle_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-alsace-moselle/) |
| [Jours fériés - Guadeloupe (2000-2031)](fr-jours-feries-guadeloupe.json) | 383 | 35 KB | [CSV](fr-jours-feries-guadeloupe_FR.csv) | [Excel](fr-jours-feries-guadeloupe_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-guadeloupe/) |
| [Jours fériés - La Réunion (2000-2031)](fr-jours-feries-la-reunion.json) | 383 | 36 KB | [CSV](fr-jours-feries-la-reunion_FR.csv) | [Excel](fr-jours-feries-la-reunion_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-la-reunion/) |
| [Jours fériés - Mayotte (2000-2031)](fr-jours-feries-mayotte.json) | 383 | 35 KB | [CSV](fr-jours-feries-mayotte_FR.csv) | [Excel](fr-jours-feries-mayotte_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-mayotte/) |
| [Jours fériés - Saint-Barthélemy (2000-2031)](fr-jours-feries-saint-barthelemy.json) | 383 | 36 KB | [CSV](fr-jours-feries-saint-barthelemy_FR.csv) | [Excel](fr-jours-feries-saint-barthelemy_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-saint-barthelemy/) |
| [Jours fériés - Saint-Martin (2000-2031)](fr-jours-feries-saint-martin.json) | 383 | 36 KB | [CSV](fr-jours-feries-saint-martin_FR.csv) | [Excel](fr-jours-feries-saint-martin_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-saint-martin/) |
| [Jours fériés - Martinique (2000-2031)](fr-jours-feries-martinique.json) | 382 | 35 KB | [CSV](fr-jours-feries-martinique_FR.csv) | [Excel](fr-jours-feries-martinique_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-martinique/) |
| [Jours fériés - Guyane (2000-2031)](fr-jours-feries-guyane.json) | 381 | 35 KB | [CSV](fr-jours-feries-guyane_FR.csv) | [Excel](fr-jours-feries-guyane_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-guyane/) |
| [Jours fériés - France métropolitaine (2000-2031)](fr-jours-feries-metropole.json) | 351 | 32 KB | [CSV](fr-jours-feries-metropole_FR.csv) | [Excel](fr-jours-feries-metropole_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-metropole/) |
| [Jours fériés - Nouvelle-Calédonie (2000-2031)](fr-jours-feries-nouvelle-caledonie.json) | 351 | 32 KB | [CSV](fr-jours-feries-nouvelle-caledonie_FR.csv) | [Excel](fr-jours-feries-nouvelle-caledonie_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-nouvelle-caledonie/) |
| [Jours fériés - Polynésie française (2000-2031)](fr-jours-feries-polynesie-francaise.json) | 351 | 32 KB | [CSV](fr-jours-feries-polynesie-francaise_FR.csv) | [Excel](fr-jours-feries-polynesie-francaise_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-polynesie-francaise/) |
| [Jours fériés - Saint-Pierre-et-Miquelon (2000-2031)](fr-jours-feries-saint-pierre-et-miquelon.json) | 351 | 32 KB | [CSV](fr-jours-feries-saint-pierre-et-miquelon_FR.csv) | [Excel](fr-jours-feries-saint-pierre-et-miquelon_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-saint-pierre-et-miquelon/) |
| [Jours fériés - Wallis-et-Futuna (2000-2031)](fr-jours-feries-wallis-et-futuna.json) | 351 | 32 KB | [CSV](fr-jours-feries-wallis-et-futuna_FR.csv) | [Excel](fr-jours-feries-wallis-et-futuna_FR.xlsx) | [View](https://listbase.org/fr/time/fr-jours-feries-wallis-et-futuna/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.fr.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.fr.listbase.org/time/fr-jours-feries.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fr/time/)
