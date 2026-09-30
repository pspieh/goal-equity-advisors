# goal-equity-advisors
Youth soccer transparency and advisory site

## Reports
- [Financial Transparency and Access Data for 25 Leading DMV Youth Soccer Clubs](reports/dmv-club-financial-transparency.md): what is public, where, and what is missing (2025–26). A styled web version is in [`reports/dmv-club-financial-transparency.html`](reports/dmv-club-financial-transparency.html).

## Data
- [`data/dmv-clubs.csv`](data/dmv-clubs.csv): the 25 selected clubs with entity type, EIN, 990 availability, and whether fee schedules, aid policies and aid outcomes are public. Disclosure columns use `yes`, `partial`, `no`, `not_verified`, `not_checked`, `not_found` or `n/a`.
- [`data/dmv-club-990s.csv`](data/dmv-club-990s.csv): latest Form 990 figures for the 14 clubs whose financials were extracted from ProPublica Nonprofit Explorer. Blank cells were not extracted. Most rows come from ProPublica summary pages, not the full filings; see the report's Caveats.
