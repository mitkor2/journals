# journals

Curated, individually verified shortlist of **129 journals** in applied
science, computer science, and engineering — plus forensic sciences, engineering & science
education, and data journals — with 50+ no-fee (diamond/subsidized)
routes. Each journal lists its **accepted article types** (research,
reviews, letters, short communications, case reports, data papers,
surveys/tutorials, technical notes — audited from author guidelines),
filterable on both pages. Publisher rule: journals owned by big commercial houses (MDPI,
Springer Nature, Elsevier, Wiley, Taylor & Francis, etc.) are excluded.
Allowed owners: universities, national academies, scientific societies,
government institutes, nonprofits — marked † when a big house merely
distributes them — plus a few small independent publishers (OmniaScience,
Scientia Socialis, Tempus), each flagged as such. Civil-engineering,
transport, and energy venues are deliberately out of scope (17 previously
verified entries removed by scope decision; they remain in git history).

## Contents

- **`index.html`** — interactive one-pager (works offline, no dependencies):
  - two tiers by best current quartile: **Tier 1 (Q2 or better)** in at least
    one of SCImago SJR / Scopus CiteScore / Clarivate JCR, **Tier 2 (Q3)**
  - full-text search across names, publishers, countries, fees, and notes
  - filters: tier, field, best quartile, country, publisher type,
    no-fee (diamond OA) only, hide ⚠-flagged, official speed data
  - sorting by SJR score, name, or JCR impact factor
  - responsive: data table on desktop, stacked cards on mobile; light/dark
- **`match.html`** — "match my paper": paste a title and/or abstract (or load
  a plain-text file) and get the journals ranked by scope fit, with matched
  keywords shown; runs fully client-side, nothing is uploaded
- **`data/journals.csv`** — the same 60 journals as flat data

## Verification

Data verified 17–18 July 2026 against SCImago, official journal/publisher sites,
DOAJ, and WoS-linked sources. Where ranking systems disagree, all quartiles
are shown. Integrity flags (⚠) mark high volume, high self-citation,
anomalous citation metrics, or advertised ultra-fast review.

Excluded after verification (Q4-only): Facta Universitatis, Series:
Electronics and Energetics; Mechanika (KTU); Informacije MIDEM; JDFSL.
Excluded for commercial ownership: J. of Baltic Science Education, JOTSE,
Int. J. of Engineering Education (Tempus).

## GitHub Pages

The page is ready to serve as-is. After merging to `main`, enable it once in
**Settings → Pages → Build and deployment**: Source = *Deploy from a branch*,
Branch = `main`, folder = `/ (root)`. The site will be available at
<https://mitkor2.github.io/journals/>.
