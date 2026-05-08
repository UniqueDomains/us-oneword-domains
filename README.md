# Available .US One-Word Domains (55,848)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-55%2C848%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .us one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **55,848 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 55,848 domains · **Median ask:** $8.16 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/us`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/us?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./us.csv">CSV</a> / <a href="./us.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .US search](https://unique.domains/domains/tld/us?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .US search](https://unique.domains/domains/tld/us?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .US one-word domain catalog.

### Files

- `us.csv` — public CSV extract (1,000 rows)
- `us.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/us-oneword-domains/main/us.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| havemercy.us    | available | $7.99     | —             | 80             | 2      | 10     | name.com         |
| shakehands.us   | available | $7.99     | —             | 85             | 9      | 11     | name.com         |
| idea.us         | resell    | —         | —             | 88             | 99     | 4      | GoDaddy.com, LLC |
| ladies.us       | resell    | —         | —             | 80             | 17     | 6      | GoDaddy.com, LLC |
| geton.us        | resell    | —         | —             | 82             | 10     | 6      | Spaceship, Inc.  |
| playin.us       | resell    | —         | —             | 80             | 10     | 7      | Spaceship, Inc.  |
| playon.us       | resell    | —         | —             | 80             | 14     | 7      | Dynadot Inc      |
| makeit.us       | resell    | —         | —             | 82             | 22     | 7      | GoDaddy.com, LLC |
| headout.us      | resell    | —         | —             | 82             | 6      | 8      | Spaceship, Inc.  |
| backyard.us     | resell    | —         | —             | 80             | 27     | 9      | GoDaddy.com, LLC |
| jetblack.us     | resell    | —         | —             | 82             | 8      | 9      | Dynadot Inc      |
| hightech.us     | resell    | —         | —             | 83             | 16     | 9      | Dynadot Inc      |
| getlucky.us     | resell    | —         | —             | 84             | 10     | 9      | GoDaddy.com, LLC |
| rolemodel.us    | resell    | —         | —             | 85             | 6      | 10     | Dynadot Inc      |
| whitewater.us   | resell    | —         | —             | 82             | 17     | 11     | GoDaddy.com, LLC |
| solarpower.us   | resell    | —         | —             | 84             | 15     | 11     | GoDaddy.com, LLC |
| getmarried.us   | resell    | —         | —             | 88             | 5      | 11     | Spaceship, Inc.  |
| chickensoup.us  | resell    | —         | —             | 84             | 4      | 12     | GoDaddy.com, LLC |
| thanksgiving.us | resell    | —         | —             | 84             | 13     | 12     | GoDaddy.com, LLC |
| takeabreak.us   | resell    | —         | —             | 86             | 8      | 12     | Dynadot Inc      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 55,848 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/us?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/us?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=related_pricing)

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

This set is entirely .us domains, with a mix of exact-word generics, everyday dictionary terms, and phrase-style brands. Examples like idea.us, ladies.us, and backyard.us lean direct and memorable, while havemercy.us, shakehands.us, and makeit.us feel more slogan-like. For founders, the key question is whether a .us ending fits the market and makes the name easy to trust and recall. For investors, the main test is whether the term is broad enough to support resale interest beyond a single use case. When comparing these domains, weigh term quality first, then asking price, then any obvious trademark sensitivity in more specific phrases or brands.

- All names in this selection use the .us extension
- Mix of generics, dictionary words, and phrase-style brands
- Median ask across the set is 8.16
- Check broad appeal and trademark risk before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .US One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .US page](https://unique.domains/domains/tld/us?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_us_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
