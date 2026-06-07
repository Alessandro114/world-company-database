# World Company Database — Sample Dataset

## Overview

A sample of **100,000 companies** from the S.C.A.L.A. Score database, which contains **244M+ companies** across 50+ countries.

## Dataset

- **File**: `score_sample_100k.csv.gz` (2.4 MB compressed, ~9.4 MB uncompressed)
- **Rows**: 100,000 (randomly sampled)
- **Format**: CSV with header

## Columns

| Column | Type | Description |
|--------|------|-------------|
| name | text | Company name |
| country | text | ISO 2-letter country code |
| city | text | City |
| province | text | Province/state |
| postal_code | text | Postal/ZIP code |
| legal_form | text | Legal form (LLC, GmbH, SRL, etc.) |
| sector | text | NACE sector code |
| sector_desc | text | Sector description |
| status | text | Company status (active, ceased, etc.) |
| founded | text | Founding year |
| employees | int | Number of employees |
| revenue | bigint | Annual revenue (EUR) |
| net_income | bigint | Net income (EUR) |
| total_assets | bigint | Total assets (EUR) |
| equity | bigint | Shareholders' equity (EUR) |
| financial_year | int | Financial year of the data |
| score | int | S.C.A.L.A. proprietary score (0-100) |
| grade | text | Score grade (A-F) |
| source | text | Data source |

## Country Distribution (top 10)

| Country | Companies |
|---------|-----------|
| BR | 18,740 |
| US | 15,409 |
| AU | 8,064 |
| FR | 7,081 |
| UK | 4,251 |
| DE | 4,182 |
| IN | 3,366 |
| RU | 3,219 |
| JP | 2,981 |
| CN | 2,803 |

## Data Sources

- EU Business Registries (OpenCorporates, national registries)
- Overture Maps Foundation
- GLEIF (Legal Entity Identifiers)
- National open data portals (Brasil.io, data.gov.au, INSEE, etc.)
- Wikidata

## Full Database Access

This is a small sample. The full database contains **244M+ companies** with richer data.

- **API**: [get-scala.com/score](https://get-scala.com/score) — RESTful API with free tier
- **MCP Server**: `npx scala-mcp-server` — for Claude, ChatGPT, and AI agents
- **Python SDK**: `pip install scala-score`
- **JavaScript SDK**: `npm install scala-score`

## License

This sample dataset is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The underlying data comes from public business registries and open data sources.
