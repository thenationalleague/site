# website

Data and embeds behind the historical pages on thenationalleague.org.uk:
the Stats Dashboard, league tables, results by club and head-to-head.

This repository is the **only** home of this data. Every page loads its JSON
from here, via `raw.githubusercontent.com/thenationalleague/site/main/...` or
`cdn.jsdelivr.net/gh/thenationalleague/site@main/...`.

`rckd-nl/website` is retired (14/11/2026). Nothing should point at it. If a
page on the live site still shows a season old, its code in the website's
content system is an old paste: re-paste it from `files/` here.

## Data files

| File | What it holds |
|---|---|
| `results.json` | Every result since 1979-80 |
| `league-tables.json` | Every final table, with `entity` linking renamed and merged clubs |
| `u19-league-tables.json` | U19 Alliance tables |
| `clubs-meta.json` | Club names, crests and lineage |
| `season-notes.json` | Notes per season (elections, expulsions, deductions) |
| `nltv.json`, `nlc-groups.json` | 2025-26 NLTV selections and National League Cup groups, kept from the retired repo |
