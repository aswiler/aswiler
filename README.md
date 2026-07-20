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
| Screen time (Mac) | 1.9h | 54.9h | 90.4h | /Users/andrew2357h* |
| Interactive human attention | 1.5h | 24.6h | 60.0h | 136.4h |
| Interactive AI generation | 3.9h | 69.5h | 115.1h | 215.8h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.1h | 13.1h | 22.8h | 94.8h |
| Additive observed work | 5.5h | 107.2h | 197.9h | 447.1h |
| Interactive sessions | 15 | 55 | 101 | 208 |
| Worker sessions | 12 | 139 | 271 | 607 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 121 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 12,869 | 109.9M | 3.4M | 1,561.5M | $1,479.04 | $4,216.25 | $3,398.48 |
| gpt-5.5 | 5,102 | 43.7M | 1.5M | 529.7M | $269.38 | $1,430.23 | $1,251.48 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| gpt-5.6-terra | 20 | 591K | 4K | 1.2M | $1.91 | $3.42 | $8.87 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| **Total** | **18,908** | **162.6M** | **5.1M** | **2,213.4M** | **$1,790.82** | **$5,975.55** | **$4,918.68** |

_2,381.2M total tokens processed. 93% cache hit rate._

_$10,894.23 total saved ($5,975.55 caching + $4,918.68 model routing vs all-Opus)._

_Model savings are modest because ~93% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 12,869 | 109.9M | 3.4M | 1,561.5M | $1,479.04 | $4,216.25 | $3,398.48 |
| gpt-5.5 | 9,997 | 85.6M | 3.0M | 1,139.1M | $553.22 | $3,075.72 | $2,577.54 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-terra | 20 | 591K | 4K | 1.2M | $1.91 | $3.42 | $8.87 |
| gpt-5.3-codex-spark | 28 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **45,804** | **213.1M** | **22.8M** | **6,098.0M** | **$11,572.14** | **$49,894.26** | **$6,567.57** |

_6,529.9M total tokens processed. 93.4% cache hit rate._

_$56,461.84 total saved ($49,894.26 caching + $6,567.57 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-20 12:53 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
