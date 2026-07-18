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
| Screen time (Mac) | 15.4h | 53.2h | 84.4h | /Users/andrew2567h* |
| Interactive human attention | 6.6h | 24.9h | 55.5h | 131.5h |
| Interactive AI generation | 25.0h | 64.2h | 99.0h | 199.4h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 1.6h | 16.3h | 22.1h | 94.2h |
| Additive observed work | 33.2h | 105.4h | 176.7h | 425.1h |
| Interactive sessions | 21 | 56 | 99 | 204 |
| Worker sessions | 32 | 186 | 258 | 594 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 119 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 11,696 | 99.3M | 3.1M | 1,422.5M | $1,344.16 | $3,840.99 | $3,088.90 |
| claude-opus-4-8 | 915 | 1K | 623K | 142.8M | $381.97 | $1,928.46 | $0.00 |
| gpt-5.5 | 5,355 | 45.4M | 1.5M | 552.7M | $280.57 | $1,492.30 | $1,303.67 |
| grok-4.5 | 228 | 3.9M | 120K | 40.0M | $25.81 | $108.16 | $102.30 |
| gpt-5.6-luna | 460 | 2.3M | 76K | 55.6M | $8.58 | $150.23 | $99.14 |
| gpt-5.6-terra | 15 | 456K | 1K | 1.1M | $1.48 | $3.16 | $6.95 |
| gpt-5.3-codex-spark | 26 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| **Total** | **18,695** | **151.6M** | **5.5M** | **2,215.8M** | **$2,043.63** | **$7,524.88** | **$4,603.35** |

_2,379.4M total tokens processed. 93.1% cache hit rate._

_$12,128.23 total saved ($7,524.88 caching + $4,603.35 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 11,696 | 99.3M | 3.1M | 1,422.5M | $1,344.16 | $3,840.99 | $3,088.90 |
| gpt-5.5 | 9,972 | 84.9M | 3.0M | 1,136.4M | $550.76 | $3,068.40 | $2,565.93 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| grok-4.5 | 228 | 3.9M | 120K | 40.0M | $25.81 | $108.16 | $102.30 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| gpt-5.6-luna | 460 | 2.3M | 76K | 55.6M | $8.58 | $150.23 | $99.14 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-terra | 15 | 456K | 1K | 1.1M | $1.48 | $3.16 | $6.95 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **44,398** | **199.7M** | **22.4M** | **5,931.9M** | **$11,429.33** | **$49,445.76** | **$6,188.45** |

_6,350.1M total tokens processed. 93.4% cache hit rate._

_$55,634.21 total saved ($49,445.76 caching + $6,188.45 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-18 12:45 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
