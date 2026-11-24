# makefun-news-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Panmeii/makefun-news-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Panmeii/makefun-news-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

**The World in One Image — 24 November 2026** — a single 1024×1024 PNG that works as a dense one-page newspaper for Tuesday, 24 November 2026: 42 real stories from that day in six colour-coded sections — World, Politics, Economy, Technology, Science & Health, and Sport & Culture — each with a short headline and a one-line context, plus a three-item lead band (the Nvidia-led markets rebound, the COP31 collapse, and BepiColombo's arrival at Mercury), a markets ticker strip (Nvidia, Nasdaq, S&P 500, Dow, Nikkei, gold, WTI, Bitcoin, the dollar) and a source footer. The Node program (`main.ts`) holds the day's news as data, typesets the front page as an SVG document with programmatic text fitting (long lines are shortened at word boundaries so nothing overflows), rasterises it into the output folder only, and audits its own delivery: genuine PNG, exactly 1024×1024, at most 1 MiB, exactly 42 stories — exiting non-zero if any check fails. When no SVG rasteriser is available at run time, the program delivers the pre-rendered `entry.png` shipped in this repository, so repeated offline runs produce identical bytes. Every headline is a factual summary of a story reported on 24 November 2026; `SOURCES.md` lists all 42 stories with their sources.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=8nt1dqan&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
