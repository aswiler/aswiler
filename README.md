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
| Screen time (Mac) | 5.6h | 41.7h | 90.4h | /Users/andrew2357h* |
| Interactive human attention | 2.0h | 19.5h | 60.3h | 138.4h |
| Interactive AI generation | 7.4h | 61.8h | 121.8h | 223.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 1.6h | 7.5h | 24.3h | 96.5h |
| Additive observed work | 11.1h | 88.8h | 206.4h | 458.2h |
| Interactive sessions | 10 | 44 | 99 | 210 |
| Worker sessions | 32 | 95 | 291 | 630 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 122 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 13,724 | 119.0M | 3.6M | 1,655.9M | $1,581.52 | $4,471.04 | $3,634.09 |
| gpt-5.5 | 5,104 | 44.2M | 1.5M | 529.7M | $270.56 | $1,430.24 | $1,257.16 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| gpt-5.6-terra | 59 | 761K | 13K | 3.8M | $3.22 | $10.39 | $14.57 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| **Total** | **19,804** | **172.3M** | **5.4M** | **2,310.3M** | **$1,895.79** | **$6,237.32** | **$5,165.67** |

_2,488.1M total tokens processed. 92.9% cache hit rate._

_$11,402.99 total saved ($6,237.32 caching + $5,165.67 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 13,724 | 119.0M | 3.6M | 1,655.9M | $1,581.52 | $4,471.04 | $3,634.09 |
| gpt-5.5 | 9,999 | 86.0M | 3.0M | 1,139.1M | $554.41 | $3,075.73 | $2,583.22 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-terra | 59 | 761K | 13K | 3.8M | $3.22 | $10.39 | $14.57 |
| gpt-5.3-codex-spark | 28 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **46,700** | **222.9M** | **23.0M** | **6,194.9M** | **$11,677.12** | **$50,156.03** | **$6,814.57** |

_6,636.8M total tokens processed. 93.3% cache hit rate._

_$56,970.60 total saved ($50,156.03 caching + $6,814.57 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-21 07:31 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
