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
| Screen time (Mac) | 5.6h | 50.9h | 96h | /Users/andrew2336h* |
| Interactive human attention | 2.0h | 19.5h | 60.3h | 138.4h |
| Interactive AI generation | 7.4h | 61.8h | 121.8h | 223.3h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 0.0h |
| Worker/headless AI generation | 1.6h | 7.5h | 24.3h | 96.5h |
| Additive observed work | 11.1h | 88.8h | 206.4h | 458.2h |
| Interactive sessions | 13 | 47 | 101 | 212 |
| Worker sessions | 41 | 104 | 300 | 639 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 122 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 14,327 | 126.0M | 3.8M | 1,719.7M | $1,656.23 | $4,643.38 | $3,805.77 |
| gpt-5.5 | 5,084 | 43.9M | 1.5M | 527.3M | $269.16 | $1,423.74 | $1,250.53 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| gpt-5.6-terra | 63 | 1.1M | 14K | 3.8M | $4.29 | $10.40 | $19.70 |
| gpt-5.3-codex-spark | 27 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| **Total** | **20,391** | **179.4M** | **5.5M** | **2,371.8M** | **$1,970.17** | **$6,403.17** | **$5,335.84** |

_2,556.8M total tokens processed. 92.8% cache hit rate._

_$11,739.01 total saved ($6,403.17 caching + $5,335.84 model routing vs all-Opus)._

_Model savings are modest because ~92.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 9,471 | 14K | 7.8M | 1,223.9M | $4,014.11 | $16,523.60 | $0.00 |
| claude-opus-4-6 | 6,273 | 7K | 3.9M | 1,092.3M | $2,944.30 | $14,747.29 | $0.00 |
| claude-opus-4-8 | 4,972 | 9K | 3.6M | 787.1M | $2,415.24 | $10,626.16 | $0.00 |
| gpt-5.6-sol | 14,327 | 126.0M | 3.8M | 1,719.7M | $1,656.23 | $4,643.38 | $3,805.77 |
| gpt-5.5 | 9,999 | 86.0M | 3.0M | 1,139.1M | $554.41 | $3,075.73 | $2,583.22 |
| claude-sonnet-4-6 | 545 | 682 | 318K | 60.1M | $39.25 | $162.44 | $91.29 |
| gpt-5.4 | 167 | 4.6M | 65K | 71.2M | $30.65 | $133.63 | $125.06 |
| grok-4.5 | 237 | 3.9M | 121K | 40.8M | $26.09 | $110.35 | $103.39 |
| gpt-5.3-codex | 289 | 3.1M | 82K | 18.5M | $20.98 | $34.75 | $61.03 |
| claude-opus-4-5 | 39 | 81 | 28K | 1.7M | $18.07 | $23.45 | $0.00 |
| gpt-5.6-luna | 653 | 4.2M | 133K | 79.1M | $13.34 | $213.70 | $154.08 |
| big-pickle | 153 | 166K | 58K | 11.8M | $9.01 | $0.00 | $24.68 |
| mimo-v2-omni-free | 90 | 661K | 51K | 8.1M | $5.81 | $21.92 | $20.78 |
| gpt-5.6-terra | 63 | 1.1M | 14K | 3.8M | $4.29 | $10.40 | $19.70 |
| gpt-5.3-codex-spark | 28 | 118K | 2K | 849K | $1.06 | $1.59 | $2.38 |
| claude-haiku-4-5 | 1 | 3 | 49 | 0 | $0.06 | $0.00 | $0.00 |
| **Total** | **47,307** | **230.3M** | **23.2M** | **6,258.8M** | **$11,752.90** | **$50,328.38** | **$6,991.36** |

_6,708.3M total tokens processed. 93.3% cache hit rate._

_$57,319.75 total saved ($50,328.38 caching + $6,991.36 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[andrew-skills](https://github.com/aswiler/andrew-skills)** -- No description
- **[straw-hat-division](https://github.com/aswiler/straw-hat-division)** -- One Piece division math game in Catalan with card colection
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aswiler)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-21 13:46 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
