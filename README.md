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
| Screen time (Mac) | 21.3h | 112.3h | 351.1h | ~1998h* |
| Interactive human attention | 0.9h | 19.5h | 93.9h | 358.8h |
| Interactive AI generation | 2.9h | 103.0h | 619.2h | 1427.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 2.5h |
| Worker/headless AI generation | 0.6h | 6.9h | 89.1h | 1343.4h |
| Additive observed work | 4.4h | 129.4h | 802.2h | 3,131.3h |
| Interactive sessions | 6 | 28 | 159 | 499 |
| Worker sessions | 53 | 299 | 1,544 | 3,948 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 218 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-6.1-sol | 52,660 | 228.4M | 11.7M | 6,130.6M | 0 | 96.4% | 1,299 | 483.9h |
| gpt-6-sol | 12,412 | 45.0M | 1.8M | 1,584.7M | 0 | 97.2% | 219 | 79.9h |
| gpt-6-astra | 11,797 | 30.1M | 1.9M | 1,677.9M | 0 | 98.2% | 20 | 85.9h |
| gpt-5.6-sol | 4,715 | 24.1M | 852K | 687.2M | 0 | 96.6% | 14 | 33.7h |
| gpt-6-luna | 3,223 | 49.5M | 1.4M | 142.0M | 0 | 74.1% | 283 | 16.7h |
| muse-spark-1.3-contributor-free | 946 | 4.3M | 219K | 140.7M | 0 | 97.0% | 5 | 7.4h |
| gpt-5.6-luna | 300 | 2.2M | 48K | 44.4M | 0 | 95.2% | 1 | 11.0h |
| gpt-5.6-terra | 186 | 2.2M | 53K | 9.9M | 0 | 81.8% | 20 | 0.9h |
| gpt-5.5 | 20 | 232K | 4K | 3.3M | 0 | 93.6% | 1 | 0.1h |
| **Total** | **86,259** | **386.3M** | **18.2M** | **10,421.3M** | **0** | **96.4%** | **1,735** | **719.6h** |

_10,825.8M total tokens processed. 96.4% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 133,970 | 793.2M | 30.8M | 17,248.4M | 0 | 95.6% | 1,158 | 1,552.5h |
| gpt-6.1-sol | 52,660 | 228.4M | 11.7M | 6,130.6M | 0 | 96.4% | 1,299 | 483.9h |
| gpt-6-sol | 16,175 | 60.7M | 2.4M | 2,088.1M | 0 | 97.2% | 273 | 97.0h |
| gpt-6-astra | 14,578 | 37.0M | 2.4M | 2,068.7M | 0 | 98.2% | 38 | 100.7h |
| gpt-5.5 | 10,025 | 86.6M | 3.0M | 1,142.8M | 0 | 93.0% | 219 | 68.7h |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | 84.5M | 93.5% | 112 | 59.6h |
| gpt-5.6-terra | 9,371 | 89.4M | 2.3M | 684.7M | 0 | 88.4% | 678 | 86.9h |
| gpt-5.6-luna | 9,019 | 77.4M | 2.2M | 1,033.2M | 0 | 93.0% | 279 | 147.1h |
| gpt-5.3-codex-spark | 7,250 | 23.3M | 1.5M | 374.5M | 0 | 94.1% | 23 | 40.5h |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | 53.8M | 95.3% | 119 | 30.0h |
| claude-opus-4-8 | 4,973 | 9K | 3.6M | 787.1M | 51.2M | 93.9% | 77 | 24.6h |
| gpt-6-luna | 3,650 | 51.5M | 1.5M | 169.6M | 0 | 76.7% | 303 | 17.9h |
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
| **Total** | **282,390** | **1,476.8M** | **75.6M** | **34,793.9M** | **195.9M** | **95.4%** | **4,379** | **2,738.0h** |

_36,542.3M total tokens processed. 95.4% cache hit rate._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-25 01:55 UTC by [aidevops](https://aidevops.sh) pulse._
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
