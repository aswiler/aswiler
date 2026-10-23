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
| Screen time (Mac) | 16.2h | 90.9h | 337.2h | ~1938h* |
| Interactive human attention | 5.2h | 13.6h | 91.7h | 352.9h |
| Interactive AI generation | 21.0h | 133.1h | 610.6h | 1400.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 2.5h |
| Worker/headless AI generation | 0.5h | 7.7h | 89.2h | 1341.8h |
| Additive observed work | 26.7h | 154.4h | 791.5h | 3,096.9h |
| Interactive sessions | 17 | 31 | 161 | 496 |
| Worker sessions | 72 | 300 | 1,515 | 3,871 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 216 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 50,700 | 220.9M | 11.5M | 5,898.4M | 0 | 96.4% | 1,233 | 469.9h |
| gpt-6-sol | 16,118 | 60.1M | 2.4M | 2,083.4M | 0 | 97.2% | 271 | 95.9h |
| gpt-6-astra | 13,042 | 33.3M | 2.2M | 1,856.1M | 0 | 98.2% | 21 | 93.3h |
| gpt-5.6-sol | 7,950 | 34.2M | 1.4M | 1,151.3M | 0 | 97.1% | 21 | 53.5h |
| gpt-6-luna | 3,365 | 49.3M | 1.4M | 159.4M | 0 | 76.4% | 280 | 17.2h |
| muse-spark-1.3-contributor-free | 1,758 | 8.8M | 435K | 255.3M | 0 | 96.7% | 8 | 11.0h |
| gpt-5.6-terra | 786 | 7.9M | 183K | 38.6M | 0 | 82.9% | 81 | 2.9h |
| gpt-5.6-luna | 326 | 2.9M | 56K | 48.1M | 0 | 94.3% | 2 | 11.3h |
| gpt-5.5 | 20 | 232K | 4K | 3.3M | 0 | 93.6% | 1 | 0.1h |
| grok-4.5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **94,066** | **418.0M** | **19.8M** | **11,494.4M** | **0** | **96.5%** | **1,780** | **755.2h** |

_11,932.2M total tokens processed. 96.5% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 133,970 | 793.2M | 30.8M | 17,248.4M | 0 | 95.6% | 1,158 | 1,552.5h |
| gpt-6.1-sol | 50,700 | 220.9M | 11.5M | 5,898.4M | 0 | 96.4% | 1,233 | 469.9h |
| gpt-6-sol | 16,175 | 60.7M | 2.4M | 2,088.1M | 0 | 97.2% | 273 | 97.0h |
| gpt-6-astra | 14,578 | 37.0M | 2.4M | 2,068.7M | 0 | 98.2% | 38 | 100.7h |
| gpt-5.5 | 10,025 | 86.6M | 3.0M | 1,142.8M | 0 | 93.0% | 219 | 68.7h |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | 84.5M | 93.5% | 112 | 59.6h |
| gpt-5.6-terra | 9,371 | 89.4M | 2.3M | 684.7M | 0 | 88.4% | 678 | 86.9h |
| gpt-5.6-luna | 9,019 | 77.4M | 2.2M | 1,033.2M | 0 | 93.0% | 279 | 147.1h |
| gpt-5.3-codex-spark | 7,250 | 23.3M | 1.5M | 374.5M | 0 | 94.1% | 23 | 40.5h |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | 53.8M | 95.3% | 119 | 30.0h |
| claude-opus-4-8 | 4,973 | 9K | 3.6M | 787.1M | 51.2M | 93.9% | 77 | 24.6h |
| gpt-6-luna | 3,502 | 50.0M | 1.4M | 166.3M | 0 | 76.9% | 288 | 17.6h |
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
| **Total** | **280,282** | **1,467.7M** | **75.3M** | **34,558.4M** | **195.9M** | **95.4%** | **4,299** | **2,723.8h** |

_36,297.5M total tokens processed. 95.4% cache hit rate._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-23 12:22 UTC by [aidevops](https://aidevops.sh) pulse._
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
