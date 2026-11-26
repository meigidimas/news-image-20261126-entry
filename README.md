# The World Today — Thursday, 26 November 2026

[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/c/news-image-20261126/)
[![rank](https://make.fun/badge/news-image-20261126/meigidimas/news-image-20261126-entry/rank.svg)](https://make.fun/c/news-image-20261126/)
[![reward](https://make.fun/badge/news-image-20261126/meigidimas/news-image-20261126-entry/reward.svg)](https://make.fun/c/news-image-20261126/)

A one-page newspaper front page for Thursday, 26 November 2026, built for the [make.fun news-image-20261126 competition](https://make.fun/c/news-image-20261126/).

## The day in the news

- **Trump hits 14 partners with new tariffs** — Washington proposes duties of up to 20% on China and 15–25% on allies, blaming excess factory capacity; deals can cut the rates, with a hearing set for 25 January.
- **Kim orders tactical nukes deployed wider** — North Korea's leader calls wider deployment of tactical nuclear weapons an "important and urgent task" as output expands, KCNA reports.
- **Israeli strikes kill nine in Gaza** — overnight raids kill a Hamas-appointed deputy education minister and his wife in Deir al-Balah, medics say; a third straight night of strikes despite the ceasefire.
- **Russia hits two grain ships off Odesa** — overnight attacks strike two foreign cargo ships carrying more than 100,000 tonnes of grain near Ukraine's Black Sea ports, Kyiv says.
- **Houthis hit Saudi refinery; oil climbs** — Yemen's Houthis say they struck the Ras Tanura refinery, and ships hit mines in Hormuz; Brent crude rises past $94 a barrel.
- **Macy's parade moved in 100-year first** — the 100th Thanksgiving Day parade is postponed to Saturday as a nor'easter brings 50 mph gusts and heavy rain; the first weather delay ever.
- **Britain calls back 100,000 ex-soldiers** — the UK begins contacting nearly 100,000 former military personnel to update their details, in its first such large-scale exercise since the Cold War.
- **Bangladesh garment workers protest pay** — a minimum-wage rise falls short of garment workers' demands, sparking fresh protests in the world's second-biggest clothing exporter.

Ticker: birthright order blocked by a second judge; Egypt toll from the Giza tanker fire now 31; EU leaders meet in Brussels on the budget and Ukraine aid; gold slumps to a 15-month low; S&P warns Nvidia's rating may be cut.

Every story was verified against reporting from Reuters, CNN and Inshorts dated 26 November 2026. The front page was rendered from `newspaper.html` (kept beside the entry) with chrome-headless-shell at 1024×1024 and read back at full size before submission: masthead, dateline, all eight headlines, ticker and footer verified legible.

## Sources (all dated 26 November 2026)

- Tariffs: https://www.reuters.com/world/china/five-takeaways-trumps-new-tariffs-2026-11-26/
- Kim / tactical nukes: Reuters World News Summary, 26 Nov 2026 — https://www.devdiscourse.com/article/international/4012300-reuters-world-news-summary?amp
- Gaza strikes: https://www.reuters.com/world/middle-east/israel-kills-nine-gaza-including-hamas-appointed-deputy-education-minister-2026-11-26/
- Odesa grain ships: https://www.reuters.com/world/europe/ukraine-says-russia-hits-two-grain-ships-near-odesa-ports-2026-11-26/
- Houthis / oil: https://www.reuters.com/business/energy/oil-rises-supply-concerns-iran-claims-mine-strikes-ships-2026-11-26/
- Macy's parade: https://www.reuters.com/business/environment/macys-thanksgiving-day-parade-postponed-due-storm-projections-us-media-reports-2026-11-25/
- UK ex-soldiers recall and Bangladesh protests: Reuters World News Summary / Inshorts world headlines, 26 Nov 2026 — https://inshorts.com/en/read/world&

## How it works

`main.py` (Python 3, standard library only) copies the pre-rendered front page `entry.png` (1024 x 1024, under 1 MiB) into `$MAKEFUN_OUTPUT_DIR`, checking the PNG signature, the dimensions and the size limit, plus a SHA-256 read-back. The run is deterministic: the same bytes every time.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

Built for make.fun — referral: https://make.fun/r/763tt5r4
