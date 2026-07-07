# Available .NYC One-Word Domains (10,917)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C917%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .nyc one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,917 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,917 domains · **Median ask:** $235.39 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/nyc`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/nyc?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./nyc.csv">CSV</a> / <a href="./nyc.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .NYC search](https://unique.domains/domains/tld/nyc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .NYC search](https://unique.domains/domains/tld/nyc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .NYC one-word domain catalog.

### Files

- `nyc.csv`, public CSV extract (1,000 rows)
- `nyc.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/nyc-oneword-domains/main/nyc.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar            |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------- |
| ahuh.nyc | available | $31.99    | $31.99        | high           | low    | 4      | namesilo             |
| buy.nyc  | resell    | —         | —             | high           | medium | 3      | Hello Internet Corp. |
| bow.nyc  | premium   | $1,107    | $29.50        | high           | low    | 3      | namesilo             |
| avon.nyc | available | $31.99    | $31.99        | high           | low    | 4      | namesilo             |
| dip.nyc  | resell    | —         | —             | high           | low    | 3      | Hello Internet Corp. |
| CNN.nyc  | premium   | $625      | —             | high           | low    | 3      | name.com             |
| brow.nyc | available | $43.98    | —             | medium         | low    | 4      | namecheap            |
| eye.nyc  | resell    | —         | —             | medium         | low    | 3      | Hello Internet Corp. |
| coy.nyc  | premium   | $625      | $46.99        | medium         | low    | 3      | name.com             |
| corn.nyc | available | $31.99    | $31.99        | medium         | low    | 4      | namesilo             |
| iii.nyc  | resell    | —         | —             | medium         | low    | 3      | GoDaddy.com, LLC     |
| cue.nyc  | premium   | $625      | —             | medium         | low    | 3      | name.com             |
| flee.nyc | available | $31.99    | $31.99        | medium         | low    | 4      | namesilo             |
| bite.nyc | resell    | —         | —             | high           | low    | 4      | Hello Internet Corp. |
| don.nyc  | premium   | $625      | —             | high           | low    | 3      | name.com             |
| flew.nyc | available | $31.99    | $31.99        | high           | low    | 4      | namesilo             |
| done.nyc | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC     |
| gag.nyc  | premium   | $625      | —             | high           | low    | 3      | name.com             |
| flop.nyc | available | $31.99    | $31.99        | medium         | low    | 4      | namesilo             |
| door.nyc | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,917 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/nyc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/nyc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set of one-word .nyc domain names totals 10,917 entries, with a median ask near $235. The names lean toward everyday, wellness, and community vocabulary — words like counselling, appreciation, and keepfit — giving them a friendly, ownable feel for NYC-facing brands. For investors, this .nyc pool offers volume at a low individual entry cost, useful for building a diversified position. For founders, the .nyc extension signals local relevance, and single-word domains here are easy to remember and pitch. When comparing names in this list, weigh dictionary-word clarity, renewal cost, and how directly the word maps to the intended brand or service.

- 10,917 one-word .nyc domain names in this selection
- Median ask near $235 across the set
- Everyday, wellness & community-style vocabulary
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .NYC One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .NYC page](https://unique.domains/domains/tld/nyc?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_nyc_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
