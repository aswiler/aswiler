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
| Screen time (Mac) | 7.7h | 49.6h | 69h | /Users/andrew2290h* |
| Interactive human attention | 1.5h | 23.3h | 51.0h | 124.9h |
| Interactive AI generation | 3.4h | 48.9h | 77.8h | 174.4h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.0h | 18.8h | 21.2h | 92.6h |
| Additive observed work | 4.9h | 91.0h | 149.9h | 391.9h |
| Interactive sessions | 17 | 56 | 98 | 198 |
| Worker sessions | 16 | 206 | 253 | 578 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 118 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 9,321 | 84.0M | 2.6M | 1,132.2M | $1,098.00 | $3,057.02 | $2,523.82 |
| claude-opus-4-8 | 963 | 1K | 658K | 151.5M | $409.07 | $2,046.03 | $0.00 |
| gpt-5.5 | 5,354 | 45.4M | 1.5M | 552.5M | $280.51 | $1,491.85 | $1,303.37 |
| gpt-5.6-luna | 175 | 443K | 28K | 21.1M | $2.81 | $57.21 | $32.46 |
| gpt-5.3-codex-spark | 26 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| gpt-5.6-terra | 8 | 101K | 705 | 292K | $0.37 | $0.79 | $1.62 |
| **Total** | **15,847** | **130.2M** | **4.8M** | **1,858.6M** | **$1,791.82** | **$6,654.49** | **$3,863.64** |

_2,000.7M total tokens processed. 92.9% cache hit rate._

_$10,518.13 total saved ($6,654.49 caching + $3,863.64 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 9,321 | 84.0M | 2.6M | 1,132.2M | $1,098.00 | $3,057.02 | $2,523.82 |
| gpt-5.5 | 9,971 | 84.9M | 3.0M | 1,136.2M | $550.70 | $3,067.95 | $2,565.63 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-luna | 175 | 443K | 28K | 21.1M | $2.81 | $57.21 | $32.46 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| gpt-5.6-terra | 8 | 101K | 705 | 292K | $0.37 | $0.79 | $1.62 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **41,502** | **178.3M** | **21.7M** | **5,566.0M** | **$11,150.42** | **$48,457.80** | **$5,448.74** |

_5,962.0M total tokens processed. 93.4% cache hit rate._

_$53,906.53 total saved ($48,457.80 caching + $5,448.74 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-17 10:17 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
