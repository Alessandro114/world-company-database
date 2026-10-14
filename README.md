# World Company Database

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A curated list of **official business registries, open company datasets and free lookup tools**, by country. Every entry links to the primary source. Where a dataset is published under an open licence that we have read ourselves, the licence is named; where we have not checked it, the table says so.

The list is maintained by the team behind [S.C.A.L.A. Score](https://score.get-scala.com), a free company search built on public registry data (see [About S.C.A.L.A. Score](#about-scala-score) below). The list itself is vendor-neutral: registries are listed whether or not Score uses them.

## Contents

- [Official business registries](#official-business-registries)
  - [Europe](#europe) · [North America](#north-america) · [Asia Pacific](#asia-pacific) · [Latin America](#latin-america) · [Africa](#africa)
- [Open bulk datasets with a verified licence](#open-bulk-datasets-with-a-verified-licence)
- [Global and cross-border sources](#global-and-cross-border-sources)
- [Free APIs](#free-apis)
- [About S.C.A.L.A. Score](#about-scala-score)
- [Quick start: Score API](#quick-start-score-api)
- [Examples of analysis built on registry data](#examples-of-analysis-built-on-registry-data)
- [Contributing](#contributing) · [Changelog](#changelog) · [Citation](#citation) · [License](#license)

## Official business registries

"Free access" means the basic search on the official site is free of charge. Bulk downloads, filed accounts and officer data often have different terms: check the registry's own conditions before reusing data.

### Europe

| Country | Official registry | What you can look up | Free access |
|---------|------------------|----------------------|-------------|
| United Kingdom | [Companies House](https://find-and-update.company-information.service.gov.uk/) | Companies, officers, filed accounts | Yes |
| Germany | [Handelsregister](https://www.handelsregister.de/) | Register entries, officers | Partial |
| Germany | [Unternehmensregister](https://www.unternehmensregister.de/) | Published accounts and announcements | Partial |
| Germany | [OffeneRegister](https://offeneregister.de/) | Open mirror of Handelsregister data (historic snapshot, not updated) | Yes |
| France | [Annuaire des Entreprises](https://annuaire-entreprises.data.gouv.fr/) | SIREN/SIRET, legal data, filed accounts where public | Yes |
| Italy | [Registro Imprese](https://www.registroimprese.it/) | Register entries, filings | Partial (paid extracts) |
| Spain | [Registro Mercantil Central](https://www.rmc.es/) | Company filings | No (paid) |
| Netherlands | [KVK](https://www.kvk.nl/) | Register entries | Partial |
| Belgium | [KBO/BCE Public Search](https://kbopub.economie.fgov.be/) | All Belgian enterprises | Yes |
| Austria | [Firmenbuch via JustizOnline](https://justizonline.gv.at/) | Register entries | Partial (paid extracts) |
| Switzerland | [Zefix](https://www.zefix.ch/) | Commercial register entries | Yes |
| Denmark | [CVR](https://datacvr.virk.dk/) | Entities, financial statements | Yes |
| Sweden | [Bolagsverket](https://bolagsverket.se/) | Register entries | Partial |
| Norway | [Brønnøysund Register Centre](https://www.brreg.no/en/) | All Norwegian entities, annual accounts | Yes |
| Finland | [PRH](https://www.prh.fi/) / [open data](https://avoindata.prh.fi/) | Trade register, YTJ business data | Yes |
| Estonia | [e-Business Register](https://ariregister.rik.ee/eng) | Entities, annual reports | Yes |
| Latvia | [Register of Enterprises (UR)](https://www.ur.gov.lv/en/) | Entities, annual reports | Yes |
| Lithuania | [Registrų centras](https://www.registrucentras.lt/en/) | Legal entities, financial statements | Yes |
| Poland | [REGON search](https://wyszukiwarkaregon.stat.gov.pl/) | All Polish entities | Yes |
| Czech Republic | [ARES](https://ares.gov.cz/) | Economic entities | Yes |
| Portugal | [Portal da Empresa](https://www.portaldaempresa.pt/) | Company services and certificates | Partial |
| Ireland | [CRO](https://www.cro.ie/) | Company register | Yes |

### North America

| Country | Official source | What you can look up | Free access |
|---------|-----------------|----------------------|-------------|
| USA | [SEC EDGAR](https://www.sec.gov/cgi-bin/browse-edgar) | Filings of SEC registrants (listed and other reporting companies) | Yes |
| USA | State business registries (Secretary of State of each state) | Varies by state | Varies |
| Canada | [Corporations Canada](https://ised-isde.canada.ca/cc/lgcy/fdrlCrpSrch.html) | Federal corporations | Yes |

### Asia Pacific

| Country | Official source | What you can look up | Free access |
|---------|-----------------|----------------------|-------------|
| Japan | [NTA Corporate Number](https://www.houjin-bangou.nta.go.jp/) | All corporate numbers | Yes |
| India | [Ministry of Corporate Affairs](https://www.mca.gov.in/) | Company master data | Partial |
| Australia | [ABN Lookup](https://www.abr.business.gov.au/) | Australian Business Numbers | Yes |
| Australia | [ASIC](https://connectonline.asic.gov.au/) | Company register | Partial |

### Latin America

| Country | Official source | What you can look up | Free access |
|---------|-----------------|----------------------|-------------|
| Brazil | [CNPJ / Receita Federal](https://solucoes.receita.fazenda.gov.br/Servicos/cnpjreva/cnpjreva_solicitacao.asp) | All registered companies | Yes |
| Colombia | [Supersociedades financial statements (datos.gov.co)](https://www.datos.gov.co/d/prwj-nzxa) | Income statements of supervised companies | Yes |
| Mexico | [SAT](https://www.sat.gob.mx/) | Tax ID (RFC) services | Partial |

### Africa

| Country | Official source | What you can look up | Free access |
|---------|-----------------|----------------------|-------------|
| South Africa | [CIPC](https://www.cipc.co.za/) | Company register | Yes |

## Open bulk datasets with a verified licence

These are the registry datasets whose licence we read on the publisher's own page (checked 2 October 2026). If you reuse them, keep the attribution the licence requires.

| Country | Publisher | Dataset | Licence |
|---------|-----------|---------|---------|
| France | INPI / BCE (data.economie.gouv.fr) | [Ratios financiers BCE/INPI](https://data.economie.gouv.fr/explore/dataset/ratios_inpi_bce/) | [Licence Ouverte v2.0 (Etalab)](https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf) |
| Norway | Brønnøysund Register Centre | [Enhetsregisteret (API and bulk)](https://data.brreg.no/enhetsregisteret/api/docs/index.html) | NLOD 2.0 |
| Estonia | RIK, e-Business Register | [Open data](https://avaandmed.ariregister.rik.ee/en) | CC BY 4.0 |
| Latvia | Register of Enterprises (UR) | [Open data on data.gov.lv](https://data.gov.lv/dati/lv/organization/ur) | CC0 1.0 |
| Lithuania | VĮ Registrų centras | [Financial statements of legal entities](https://data.gov.lt/datasets/1806) | CC BY 4.0 |
| Colombia | Superintendencia de Sociedades | [Estados Financieros NIIF (prwj-nzxa)](https://www.datos.gov.co/d/prwj-nzxa) | CC BY-SA 4.0 |

Other well-known bulk datasets (licence not re-checked by us, read the publisher's terms):

- [UK Companies House free data product](https://download.companieshouse.gov.uk/en_output.html) — monthly snapshot of live UK companies. Companies House asks re-users to credit it as the source ([data products](https://www.gov.uk/guidance/companies-house-data-products)).
- [SIRENE (INSEE) on data.gouv.fr](https://www.data.gouv.fr/en/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/) — all French legal units and establishments.
- [ABN Bulk Extract](https://data.gov.au/data/dataset/abn-bulk-extract) — Australian Business Register.
- [GLEIF Golden Copy](https://www.gleif.org/en/lei-data/gleif-golden-copy/download-the-golden-copy) — all LEI records worldwide.
- [SEC EDGAR full-text search](https://efts.sec.gov/LATEST/search-index) — US filings.

## Global and cross-border sources

| Source | What it covers | Free access |
|--------|----------------|-------------|
| [GLEIF](https://search.gleif.org/) | Legal Entity Identifiers (LEI) and parent relationships | Yes |
| [OpenCorporates](https://opencorporates.com/) | Aggregated registry data from many jurisdictions | Partial |
| [Wikidata](https://www.wikidata.org/) | Structured data on larger companies | Yes |
| [OpenSanctions](https://www.opensanctions.org/) | Sanctioned and politically exposed entities | Yes (non-commercial) |
| [S.C.A.L.A. Score](https://score.get-scala.com) | Search across registry and open data from many countries ([details](#about-scala-score)) | Yes (web search) |

## Free APIs

| Provider | Coverage | Pricing | Docs |
|----------|----------|---------|------|
| Companies House API | UK | Free (key required) | [developer.company-information.service.gov.uk](https://developer.company-information.service.gov.uk/) |
| Brønnøysund API | Norway | Free, no key | [data.brreg.no](https://data.brreg.no/enhetsregisteret/api/docs/index.html) |
| GLEIF API | LEI records | Free, no key | [gleif.org](https://www.gleif.org/en/lei-data/gleif-api/) |
| S.C.A.L.A. Score API | Multi-country | Free tier: 50 calls/month (key required) | [score.get-scala.com/api](https://score.get-scala.com/api) |

## About S.C.A.L.A. Score

[S.C.A.L.A. Score](https://score.get-scala.com) is a free company search built by S.C.A.L.A. (The AI Operating System for Business). It combines public business registries and open datasets into one searchable index of company records.

What to know before you use it:

- **Size.** The [API page](https://score.get-scala.com/api) shows the live record count (about 249 million on 14 October 2026). These are *records*, not verified unique companies: they include entries from map and point-of-interest data (Overture Maps, OpenStreetMap), so some records are shops, offices or other places rather than registered legal entities.
- **Financial data is partial.** Revenue and other figures exist only for a subset of records. Every API result carries `revenue_type`: `reported` means the figure comes from filed accounts or an official source; `estimated` means S.C.A.L.A. modelled it. Estimates are not filed figures and should not be used as such.
- **The score is a S.C.A.L.A. model output** (0–100 with a letter grade). It is not a credit rating from a rating agency and is not a statement about any company's creditworthiness.
- **Licences and attribution.** The per-country sources, licences and attribution statements are on the [Data sources & licences](https://score.get-scala.com/sources) page. Countries marked *to be verified* there must not be redistributed.

## Quick start: Score API

Get a free key (50 calls/month, no credit card) at [score.get-scala.com/api/free-key](https://score.get-scala.com/api/free-key), then:

```bash
# Search companies by name (q, optional country, limit up to 100)
curl -H "X-API-Key: YOUR_API_KEY" \
  "https://score.get-scala.com/api/v1/search?q=Maxima&country=LT&limit=5"

# Full profile of one record
curl -H "X-API-Key: YOUR_API_KEY" \
  "https://score.get-scala.com/api/v1/company/RECORD_ID"

# Remaining credits
curl -H "X-API-Key: YOUR_API_KEY" "https://score.get-scala.com/api/v1/usage"
```

Results include `revenue_type` (`reported` / `estimated`) and a `data_licences` object with the source, licence and attribution statement for each country in the response. Keep those statements if you redistribute the data. Full reference: [score.get-scala.com/api](https://score.get-scala.com/api).

## Examples of analysis built on registry data

- [234 companies earn 45% of Lithuania's revenue](https://get-scala.com/en/blog/lithuania-company-financials-2024) — 82,781 financial statements for 2024 from the Lithuanian Register of Legal Entities (open data, CC BY 4.0). Filed figures only, no estimates.
- [Growth 100 UK](https://score.get-scala.com/rankings/uk/growth-100/) — the 100 fastest-growing independent UK SMEs, 2022–2024 turnover growth computed only from accounts filed at Companies House.

## Contributing

Additions and corrections are welcome. To keep the list reliable:

1. **Official or open sources first.** Link the registry or the publisher of the open dataset, not a reseller. Commercial sites that resell registry data are not listed.
2. **One fact per claim.** If you state a licence, link the page where the licence is written. Do not add record counts unless the source publishes them.
3. **Check the link** from a normal browser and say in the PR when you checked it.
4. Open a pull request that edits `README.md` only, with one country or source per PR if possible.

Broken link or wrong licence? [Open an issue](https://github.com/Alessandro114/world-company-database/issues).

## Changelog

- **2026-10** — Rewrite for accuracy: removed record counts that could not be sourced, removed commercial resellers and comparison claims, removed links that no longer resolve (sirene.fr, dubaided.gov.ae, gsxt.gov.cn, NASS page), added verified open-data licences per country, Baltic and Colombian sources, API quick start, examples, contribution rules.
- **2026-08** — Added CC BY 4.0 licence text.
- **2026-06** — Added a 100K sample of Score records and developer tool links.
- **2026-05** — First version of the list.

## Citation

```bibtex
@misc{world_company_database,
  title  = {World Company Database: a curated list of business registries and open company datasets},
  author = {{S.C.A.L.A.}},
  year   = {2026},
  url    = {https://github.com/Alessandro114/world-company-database},
  note   = {Licensed under CC BY 4.0}
}
```

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

The text of this list is licensed under CC BY 4.0. Data from the linked registries and datasets is governed by each publisher's own terms, not by this licence.
