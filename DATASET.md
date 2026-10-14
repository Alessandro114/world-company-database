# Sample dataset: `score_sample_100k.csv.gz`

> **Status (October 2026): under licence review.** Part of the rows in this file come from sources whose licence has not been confirmed or does not allow redistribution under CC BY 4.0 (see [Known issues](#known-issues)). Do not redistribute this file until the review is complete. The list in `README.md` is not affected.

## What it is

100,000 records drawn at random from the [S.C.A.L.A. Score](https://score.get-scala.com) index in June 2026, across 167 country codes. Records come from public registries, open datasets and map/point-of-interest data, so not every row is a registered legal entity.

## Columns

| Column | Meaning |
|--------|---------|
| `name` | Name as given by the source |
| `country` | Country code. Mostly ISO 3166-1 alpha-2, but the United Kingdom appears both as `GB` and as the non-ISO `UK` |
| `city`, `province`, `postal_code` | Location as given by the source |
| `legal_form` | Legal form, where the source provides it |
| `sector` | Sector code or category. A NACE code for registry rows, a free-text category (e.g. `library`) for map rows |
| `sector_desc` | Sector description, where available |
| `status` | Status as given by the source (e.g. `active`) |
| `founded` | Year or date of incorporation, where available |
| `employees` | Employee count, where available |
| `revenue`, `net_income`, `total_assets`, `equity` | Financial figures, where available. See below |
| `financial_year` | Financial year of the figures |
| `score`, `grade` | S.C.A.L.A. model output (0–100, letter grade). Not a credit rating |
| `source` | Source identifier(s), comma-separated |

## Reported vs estimated figures

Only 7,125 of the 100,000 rows have a revenue value, and **6,739 of those are estimates**, not filed figures. A row is estimated when its `source` contains `estimated_` (for example `sirene,estimated_cm_437`): the value was modelled by S.C.A.L.A., not read from filed accounts. Treat only rows *without* `estimated_` in `source` as taken from the named source, and check that source before relying on a figure. Currency is not normalised across all rows.

## Known issues

- Rows with `reportaziende` in `source` (215) come from a third-party commercial website, not from an open dataset.
- Rows from `osm_geofabrik` (3,729) are OpenStreetMap data, which is licensed under ODbL, not CC BY 4.0.
- Rows from `pdl_free`, `hf_pdl`, `bigpicture`, `linkedin_profiles` and Overture Maps sources have licences that were not audited.
- Italian (`IT`), Danish (`DK`) and United Kingdom (`GB`/`UK`) rows depend on sources whose licence is marked *to be verified* on the [Data sources & licences](https://score.get-scala.com/sources) page.

## Licence

The CC BY 4.0 licence of this repository covers the list in `README.md`. It does not override the terms of the sources in this file; until the review above is complete, no licence is granted for redistributing this file.

For data with verified licences, use the [Score API](https://score.get-scala.com/api) (every response carries a `data_licences` object with the attribution required for each country) or the open datasets listed in `README.md`.
