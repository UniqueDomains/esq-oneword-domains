# Available .ESQ One-Word Domains (12,870)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C870%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .esq one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,870 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,870 domains · **Median ask:** $148.37 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/esq`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/esq?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./esq.csv">CSV</a> / <a href="./esq.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ESQ search](https://unique.domains/domains/tld/esq?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ESQ search](https://unique.domains/domains/tld/esq?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ESQ one-word domain catalog.

### Files

- `esq.csv`, public CSV extract (1,000 rows)
- `esq.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/esq-oneword-domains/main/esq.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| half.esq  | premium   | $1,623.75 | —             | high           | low    | 4      | name.com         |
| bad.esq   | premium   | $811.25   | —             | high           | medium | 3      | name.com         |
| great.esq | premium   | $811.25   | —             | high           | low    | 5      | name.com         |
| clean.esq | premium   | $411.25   | —             | high           | low    | 5      | name.com         |
| off.esq   | premium   | $811.25   | —             | high           | low    | 3      | name.com         |
| Audi.esq  | available | $26.99    | —             | high           | high   | 4      | name.com         |
| data.esq  | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC |
| ana.esq   | premium   | $411.25   | —             | high           | low    | 3      | name.com         |
| avon.esq  | available | $26.99    | —             | high           | low    | 4      | name.com         |
| flew.esq  | available | $26.99    | —             | high           | low    | 4      | name.com         |
| buy.esq   | premium   | $1,623.75 | —             | high           | medium | 3      | name.com         |
| jolt.esq  | available | $26.99    | —             | high           | low    | 4      | name.com         |
| CNN.esq   | premium   | $111.25   | —             | high           | low    | 3      | name.com         |
| lego.esq  | available | $26.99    | —             | high           | high   | 4      | name.com         |
| coy.esq   | premium   | $111.25   | $111.25       | medium         | low    | 3      | name.com         |
| thou.esq  | available | $26.99    | $37.99        | medium         | low    | 4      | name.com         |
| cue.esq   | premium   | $111.25   | —             | medium         | low    | 3      | name.com         |
| ttyl.esq  | available | $26.99    | —             | low            | low    | 4      | name.com         |
| dip.esq   | premium   | $198.75   | $198.75       | high           | low    | 3      | name.com         |
| vain.esq  | available | $26.99    | —             | medium         | low    | 4      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,870 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/esq?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/esq?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=related_pricing)

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

Every domain in this set pairs the .esq extension with a single, everyday English word — half, out, just, christmas, okay, feel, bad, great, damn, sorry. That combination produces short, memorable names that read naturally in speech and are easy to spell, which matters whether you're shortlisting a brand name or comparing a portfolio of listings. Across 12,870 .esq domains tracked here, the median ask is close to $148, giving a practical price anchor before evaluating individual names.

- 12,870 one-word .esq domains in this set
- Median asking price near $148 per domain
- Everyday words: half, out, feel, great, sorry
- Short, phonetic names easy to spell and say

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ESQ One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ESQ page](https://unique.domains/domains/tld/esq?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_esq_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
