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
| Screen time (Mac) | 4.1h | 55.4h | 88.5h | /Users/andrew2485h* |
| Interactive human attention | 3.3h | 25.5h | 58.8h | 134.9h |
| Interactive AI generation | 12.5h | 71.3h | 111.5h | 211.9h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 0.5h | 15.0h | 22.7h | 94.7h |
| Additive observed work | 16.3h | 111.8h | 193.0h | 441.6h |
| Interactive sessions | 16 | 58 | 101 | 206 |
| Worker sessions | 8 | 153 | 262 | 598 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 120 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 12,357 | 103.4M | 3.3M | 1,507.6M | $1,413.72 | $4,070.59 | $3,248.21 |
| gpt-5.5 | 5,372 | 45.6M | 1.5M | 554.0M | $281.49 | $1,495.87 | $1,307.91 |
| claude-opus-4-8 | 195 | 386 | 155K | 26.7M | $65.28 | $360.98 | $0.00 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| gpt-5.6-terra | 15 | 456K | 1K | 1.1M | $1.48 | $3.16 | $6.95 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| **Total** | **18,856** | **157.8M** | **5.2M** | **2,210.4M** | **$1,802.46** | **$6,256.25** | **$4,822.92** |

_2,374.2M total tokens processed. 93.1% cache hit rate._

_$11,079.17 total saved ($6,256.25 caching + $4,822.92 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 12,357 | 103.4M | 3.3M | 1,507.6M | $1,413.72 | $4,070.59 | $3,248.21 |
| gpt-5.5 | 9,989 | 85.1M | 3.0M | 1,137.7M | $551.68 | $3,071.98 | $2,570.17 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-terra | 15 | 456K | 1K | 1.1M | $1.48 | $3.16 | $6.95 |
| gpt-5.3-codex-spark | 28 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **45,279** | **206.0M** | **22.7M** | **6,042.6M** | **$11,504.85** | **$49,744.60** | **$6,408.02** |

_6,467.2M total tokens processed. 93.4% cache hit rate._

_$56,152.62 total saved ($49,744.60 caching + $6,408.02 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-19 08:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
