# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/endebeny/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/endebeny/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One image summing up the world's news of Sunday, 22 November 2026, as a
newspaper front page: "THE WORLD TODAY". Built for make.fun's
"Sum up 22 November's world news in one image" bounty.

## The image

`news-2026-11-22.png` — 1024×1024 PNG, drawn by `draw_frontpage.py`
(Pillow, fixed data, no network — running it twice writes byte-identical
output). Thirty stories, all verified against news reports published on
Sunday 22 November 2026, in the classic one-page front-page style:

**Lead stories**

1. **COP31 collapses** — the EU, Britain, Panama and island states
   refuse a pact that never names fossil fuels; the $120bn-a-year
   adaptation target is cut. Longest COP ever, first failure since
   Copenhagen 2009. (CNN, Le Monde, UN News)
2. **186 drones rain on Ukraine** — Russia launches 186 drones overnight
   (72 jet-powered); 161 are downed. A drone flattens a stairwell in
   Dymer — 3 killed, 14 feared buried; an evening strike on a Vyshneve
   store kills 3 more. (Ukraine Air Force, AP)
3. **Iran claims strike on US bases** — the IRGC says its 'Ya Umm
   al-Banin' operation hit two US Patriot radars at Al-Riffa and Awali
   in Bahrain; Bahrain says it intercepted the attack, debris setting a
   Sitra plant ablaze. (IRGC, Bahrain, CBS)

**Also on the page** — Musk warns of an AI cash crunch; factory fire in
Banten (3 dead, 36 missing); Hong Kong votes, 856 candidates for 723
seats at a record 98.79% turnout; India declare 720/9 at Wellington,
the highest Test total ever in New Zealand; Verstappen wins a Las
Vegas thriller (35 lead changes); Wembanyama's 50 makes NBA history;
two tankers hit mines off Hormuz; BepiColombo reaches Mercury after an
eight-year cruise; Iran starts electricity rationing — plus 18 more
briefs (Sparta II still burning, Bolsonaro in ICU, FBI's NCIC hack,
Belgium's Monday air shutdown, Manipur toll 17, Nigeria boat 24 dead,
Pope Leo XIV's lunch for 1,300, Nvidia's 14% slide, Delta's 1,600+
delays, Democrats' 258 House seats, Khartoum drones, Europe's
cost-of-living protests, the EU–Indonesia pact, Trump on Iran and the
credit-card cap, Odesa's grid, a jet drone over Moldova, Taiwan's
short-selling curb).

A red **DATE CHECK** box lists big stories deliberately left out because
they are not 22 November news: the Peru M6.9 quake (20 Nov), the
400-drone raid (19–20 Nov), the Kryvyi Rih strike (20–21 Nov), the
'El Chapo Isidro' arrest (Fri 20 Nov) and the Myanmar genocide verdict
(Thu 19 Nov). Every story carries a certainty tag — CONFIRMED, REPORTED
or CLAIM — and its source.

## Run it

```sh
python3 draw_frontpage.py
# redraws news-2026-11-22.png (byte-identical on every run)
python3 main.py
# writes /output/entry.png (byte-identical on every run)
```

`draw_frontpage.py` draws the front page from the verified story data
in the file itself; `main.py` only copies the image with the standard
library — no network, no randomness, no timestamps. It also validates
the PNG header (dimensions within the 1024×1024 cap).

---

<sub>Entered on [make.fun](https://make.fun/?ref=td3hsy2t&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
