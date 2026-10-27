# aswiler

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 9.9h | 107.9h | 379.7h | ~2070h* |
| Interactive human attention | 0.6h | 19.1h | 84.3h | 359.9h |
| Interactive AI generation | 17.7h | 87.2h | 597.5h | 1448.8h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 2.5h |
| Worker/headless AI generation | 0.7h | 6.2h | 84.8h | 1344.9h |
| Additive observed work | 19.0h | 112.5h | 766.6h | 3,155.5h |
| Interactive sessions | 8 | 31 | 141 | 503 |
| Worker sessions | 29 | 292 | 1,502 | 4,009 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 220 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 54,175 | 235.3M | 12.0M | 6,301.1M | 0 | 96.4% | 1,358 | 507.7h |
| gpt-6-astra | 11,775 | 29.4M | 1.9M | 1,673.9M | 0 | 98.3% | 21 | 85.2h |
| gpt-6-sol | 10,860 | 38.8M | 1.6M | 1,372.0M | 0 | 97.2% | 195 | 70.9h |
| gpt-5.6-sol | 4,559 | 23.0M | 828K | 662.3M | 0 | 96.6% | 11 | 32.5h |
| gpt-6-luna | 3,205 | 49.7M | 1.4M | 139.6M | 0 | 73.7% | 285 | 16.3h |
| gpt-5.6-luna | 300 | 2.2M | 48K | 44.4M | 0 | 95.2% | 1 | 11.0h |
| gpt-5.5 | 20 | 232K | 4K | 3.3M | 0 | 93.6% | 1 | 0.1h |
| gpt-5.6-terra | 14 | 225K | 1K | 802K | 0 | 78.1% | 1 | 0.0h |
| muse-spark-1.3-contributor-free | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **84,909** | **379.2M** | **17.9M** | **10,197.8M** | **0** | **96.4%** | **1,752** | **723.6h** |

_10,595.0M total tokens processed. 96.4% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 133,970 | 793.2M | 30.8M | 17,248.4M | 0 | 95.6% | 1,158 | 1,552.5h |
| gpt-6.1-sol | 54,175 | 235.3M | 12.0M | 6,301.1M | 0 | 96.4% | 1,358 | 507.7h |
| gpt-6-sol | 16,175 | 60.7M | 2.4M | 2,088.1M | 0 | 97.2% | 273 | 97.0h |
| gpt-6-astra | 14,579 | 37.0M | 2.4M | 2,068.7M | 0 | 98.2% | 39 | 100.7h |
| gpt-5.5 | 10,025 | 86.6M | 3.0M | 1,142.8M | 0 | 93.0% | 219 | 68.7h |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | 84.5M | 93.5% | 112 | 59.6h |
| gpt-5.6-terra | 9,371 | 89.4M | 2.3M | 684.7M | 0 | 88.4% | 678 | 86.9h |
| gpt-5.6-luna | 9,019 | 77.4M | 2.2M | 1,033.2M | 0 | 93.0% | 279 | 147.1h |
| gpt-5.3-codex-spark | 7,250 | 23.3M | 1.5M | 374.5M | 0 | 94.1% | 23 | 40.5h |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | 53.8M | 95.3% | 119 | 30.0h |
| claude-opus-4-8 | 4,973 | 9K | 3.6M | 787.1M | 51.2M | 93.9% | 77 | 24.6h |
| gpt-6-luna | 3,682 | 52.2M | 1.5M | 170.2M | 0 | 76.5% | 307 | 18.0h |
| muse-spark-1.3-contributor-free | 1,758 | 8.8M | 435K | 255.3M | 0 | 96.7% | 8 | 11.0h |
| grok-4.5 | 1,530 | 10.0M | 668K | 278.9M | 0 | 96.5% | 28 | 12.2h |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | 4.3M | 93.2% | 28 | 1.8h |
| gpt-5.6-terra-fast | 383 | 1.2M | 65K | 43.3M | 0 | 97.2% | 5 | 1.2h |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | 0 | 85.4% | 13 | 0.9h |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | 0 | 93.8% | 1 | 0.9h |
| big-pickle | 153 | 166K | 58K | 11.8M | 1.0M | 90.4% | 5 | 0.4h |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | 0 | 92.5% | 2 | 0.2h |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | 711K | 71.0% | 4 | 0.2h |
| pool-account-management | 9 | 0 | 0 | 0 | 0 | 0.0% | 8 | 0.0h |
| gpt-5.5-pro | 7 | 0 | 0 | 0 | 0 | 0.0% | 6 | 0.0h |
| gpt-5.6-sol-pro | 2 | 0 | 0 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | 57K | 0.0% | 1 | 0.0h |
| claude-opus-4-6-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| grok-build-0.1 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **283,938** | **1,484.4M** | **75.9M** | **34,965.1M** | **195.9M** | **95.4%** | **4,443** | **2,761.9h** |

_36,721.3M total tokens processed. 95.4% cache hit rate._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-27 00:55 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/aswiler?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="aswiler's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/aswiler?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
