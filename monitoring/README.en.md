<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Valais only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:25 UTC, Valais: systematic collection (lex.vs.ch): 296 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Valais: systematic collection (lex.vs.ch)](https://lex.vs.ch/) | `<act>/` | daily | 2026-11-28 08:25 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:19](checks/2026-11.md#ch-lexwork-valais-20261128t081953z) | lexwork-valais | 296 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-28 07:09](checks/2026-11.md#ch-lexwork-valais-20261128t070915z) | lexwork-valais | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:39](checks/2026-11.md#ch-lexwork-valais-20261128t063957z) | lexwork-valais | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 06:57](checks/2026-11.md#ch-lexwork-valais-20261127t065712z) | lexwork-valais | 270 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-26 07:00](checks/2026-11.md#ch-lexwork-valais-20261126t070014z) | lexwork-valais | 273 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-25 08:04](checks/2026-11.md#ch-lexwork-valais-20261125t080442z) | lexwork-valais | 322 | 0 | 0 | 0 | 2 (0) | no change `verify-differ` | — |
| [2026-11-24 12:36](checks/2026-11.md#ch-lexwork-valais-20261124t123604z) | lexwork-valais | 319 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
