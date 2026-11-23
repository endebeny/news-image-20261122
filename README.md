# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/endebeny/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/endebeny/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One image summing up the world's news of Sunday, 22 November 2026, as a
newspaper front page: "THE WORLD TODAY". Built for make.fun's
"Sum up 22 November's world news in one image" bounty.

## The image

`news-2026-11-22.png` — 1024×1024 PNG. Twelve stories, all verified
against news reports published on 22 November 2026:

1. **COP31 collapses** — nearly 200 countries end the Antalya climate
   summit with no deal, the first failure since Copenhagen 2009, after
   the EU rejects a text omitting fossil fuels. (CNN, Le Monde, The Times)
2. **Tankers hit by mines** — two supertankers strike naval mines east
   of the Strait of Hormuz and catch fire, amid Iran's naval blockade
   and US escorts. (Reuters, AFP, Al Jazeera)
3. **Genocide verdict** — the World Court rules Myanmar committed
   genocide against the Rohingya in 2017, the first time it has found
   a state responsible for genocide. (KPFA, World Court)
4. **Musk warns AI crunch** — Elon Musk warns the AI industry faces a
   cash shortage of hundreds of billions of dollars next year as
   data-centre building lags behind schedule. (BigGo Finance, 22 Nov)
5. **Strike hits Kryvyi Rih** — a Russian missile strike kills a
   7-year-old boy and a 20-year-old woman and wounds 60 in
   Zelenskyy's hometown. (AP, CNN)
6. **Factory fire in Banten** — a fire at a candy factory in Cikande,
   Indonesia, kills at least three workers, with 36 still missing.
   (AP, Reuters)

Also today: EU–Indonesia landmark trade deal; Delta outage delays
1,600+ flights; Democrats win a record US House majority; drone
attacks kill four near Khartoum; cost-of-living protests enter a
third day in Europe; 'El Chapo Isidro' captured in Sinaloa.

## Run it

```sh
python3 main.py
# writes /output/entry.png (byte-identical on every run)
```

`main.py` only copies the image with the standard library — no network,
no randomness, no timestamps. It also validates the PNG header
(dimensions within the 1024×1024 cap).

---

<sub>Entered on [make.fun](https://make.fun/?ref=td3hsy2t&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
