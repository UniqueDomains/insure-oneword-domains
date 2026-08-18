# Available .INSURE One-Word Domains (16,515)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C515%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .insure one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,515 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,515 domains · **Median ask:** $11.79 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-18
**Canonical page:** `https://unique.domains/domains/tld/insure`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/insure?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./insure.csv">CSV</a> / <a href="./insure.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .INSURE search](https://unique.domains/domains/tld/insure?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .INSURE search](https://unique.domains/domains/tld/insure?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .INSURE one-word domain catalog.

### Files

- `insure.csv`, public CSV extract (1,000 rows)
- `insure.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/insure-oneword-domains/main/insure.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| act.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| aaa.insure    | resell    | —         | —             | high           | medium | 3      | GoDaddy.com, LLC  |
| tel.insure    | premium   | $500      | —             | medium         | low    | 3      | name.com          |
| add.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| bot.insure    | resell    | —         | —             | high           | medium | 3      | Dynadot Inc       |
| baby.insure   | premium   | $118.80   | $118.80       | high           | low    | 4      | namesilo          |
| are.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| dot.insure    | resell    | —         | —             | high           | medium | 3      | Porkbun LLC       |
| city.insure   | premium   | $78.54    | $78.54        | high           | medium | 4      | namesilo          |
| bid.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| new.insure    | resell    | —         | —             | high           | medium | 3      | Porkbun LLC       |
| wine.insure   | premium   | $242      | $242          | high           | low    | 4      | namesilo          |
| con.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| waste.insure  | resell    | —         | —             | high           | low    | 5      | GoDaddy.com, LLC  |
| phone.insure  | premium   | $242      | $242          | high           | low    | 5      | namesilo          |
| dew.insure    | available | $9.99     | —             | medium         | low    | 3      | name.com          |
| sports.insure | resell    | —         | —             | high           | medium | 6      | Sav.com, LLC - 34 |
| theft.insure  | premium   | $118.80   | $118.80       | medium         | low    | 5      | namesilo          |
| did.insure    | available | $9.99     | —             | high           | low    | 3      | name.com          |
| berlin.insure | premium   | $118.80   | $118.80       | high           | low    | 6      | namesilo          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,515 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/insure?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/insure?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=related_pricing)

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

This set of 12,243 one-word .insure domain names spans compact, brandable terms like toneup, settledown, and getphysical. Median asking price sits near $13, making it easy to compare options before committing to a purchase or renewal budget. Updated daily, the list reflects new .insure names as they become available.

- 12,243 one-word .insure domains tracked, updated daily
- Median asking price near $13 across this .insure selection
- Short, ownable names ready to register now
- Compare pricing and renewal before you buy

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .INSURE One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .INSURE page](https://unique.domains/domains/tld/insure?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
