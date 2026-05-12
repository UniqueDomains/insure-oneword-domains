# Available .INSURE One-Word Domains (12,244)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C244%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .insure one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,244 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,244 domains · **Median ask:** $16.80 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `insure.csv` — public CSV extract (1,000 rows)
- `insure.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/insure-oneword-domains/main/insure.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| matcha.insure       | available | $9.99     | —             | 86             | 39     | 6      | name.com    |
| farms.insure        | resell    | —         | —             | 54             | 16     | 5      | Dynadot Inc |
| homes.insure        | premium   | $84.99    | —             | 86             | 34     | 5      | name.com    |
| neuroscience.insure | available | $9.99     | —             | 80             | 37     | 12     | name.com    |
| rewards.insure      | premium   | $118.80   | $118.80       | 62             | 30     | 7      | namesilo    |
| William.insure      | available | $91.98    | —             | 74             | 31     | 7      | namecheap   |
| brands.insure       | premium   | $250      | —             | 62             | 28     | 6      | name.com    |
| letsgo.insure       | available | $9.99     | —             | 57             | 31     | 7      | name.com    |
| Vehicles.insure     | premium   | $560      | $560          | 49             | 13     | 8      | namecheap   |
| maps.insure         | available | $9.99     | —             | 56             | 31     | 4      | name.com    |
| LGBTQ.insure        | premium   | —         | —             | 86             | 20     | 5      | —           |
| slots.insure        | available | $9.99     | —             | 49             | 31     | 5      | name.com    |
| inspiration.insure  | available | $9.99     | —             | 88             | 30     | 11     | name.com    |
| flight.insure       | available | $9.99     | —             | 80             | 29     | 6      | name.com    |
| blocks.insure       | available | $9.99     | —             | 53             | 29     | 6      | name.com    |
| commonground.insure | available | $9.99     | —             | 74             | 28     | 13     | name.com    |
| backyard.insure     | available | $9.99     | —             | 80             | 27     | 9      | name.com    |
| KFC.insure          | available | $91.98    | —             | 74             | 27     | 3      | namecheap   |
| trades.insure       | available | $9.99     | —             | 71             | 26     | 6      | name.com    |
| drops.insure        | available | $9.99     | —             | 52             | 25     | 5      | name.com    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,244 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/insure?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/insure?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .insure domains, which makes it narrower and more category-specific than a mixed-TLD set. Names such as own.insure, bid.insure, cinema.insure, and biological.insure show the range: some are direct and commercial, while others are broader words adapted to an insurance context. For founders, the best choices are usually the ones that read naturally with “insure” and are easy to explain aloud. For investors, the key question is whether the word has clear insurance relevance and realistic resale appeal within a specialized extension. Median ask is 16.81, so pricing discipline matters less than fit, clarity, and avoidable legal risk.

- Prefer words that read cleanly before .insure
- Check if the term feels native to insurance use
- Watch for trademark risk in names like Sony.insure
- Use price, clarity, and recall to rank the set

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .INSURE One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .INSURE page](https://unique.domains/domains/tld/insure?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_insure_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
