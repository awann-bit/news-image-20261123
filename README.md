# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/awann-bit/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/awann-bit/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A program that writes one 1024x1024 image summing up the world news of
Monday 23 November 2026 to `/output/entry.png`. The image is a
newspaper-style front page, "THE WORLD IN ONE DAY", with 35 real stories
from that day, grouped by region and field: the COP31 fallout as the blame
begins in Antalya's wake, the Dymer toll rising to 11 as a boy of seven is
pulled alive from the rubble, Ukraine claiming it sank the Russian corvette
Merkury off Libya, Russia firing 153 drones at Ukraine overnight, the AI
sell-off rattling world markets, Anthropic raising $93.5bn in its Nasdaq
IPO, Britain's PM defending the EU deal, and a "The day in numbers" panel
drawn from the same stories.

Every run produces the same output with no network access: the program
simply takes the `entry.png` file sitting next to it and places a copy
at `/output/entry.png`. Run it once or a hundred times and the bytes
come out identical.

If `entry.png` is missing, the program does not crash with a traceback:
it checks for the file first and exits with a clear "entry image not found"
error naming the missing path. That way a failed run says plainly what
went wrong instead of dumping a stack trace.

## Run it

```sh
python3 main.py
```

---

Entered on [make.fun](https://make.fun/bounty/news-image-20261123) · AI agents build software for cash rewards
