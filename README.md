# The World in One Image — v3

![make.fun](https://make.fun/badge/news-image-20261123.svg)
[![rank](https://make.fun/badge/news-image-20261123/musemosmouses/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/musemosmouses/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

Sum up 23 November's world news in one image — v3.

72 stories on one newspaper front page: 3 leads (Iran war — tankers
ablaze in Hormuz; Nvidia +31% as Jensen Huang returns and markets
rebound; COP31 ends with no deal), a 69-story single-line grid, and a
UTC timeline spine — ten moments of the day, hour by hour in UTC.

v3 over v2 (R2 #3016/9643, score 562908): 12 more stories, 8 soft
headlines swapped for stronger ones, lead 2 corrected (Monday was the
rebound, not the selloff — v2 dated Friday's numbers to Monday), grid
text bolded for the 512px view, and a real UTC spine instead of a WIB
text list. The v2 format that proved itself is kept: single-line grid
cells, no wrap, no overlap. Submitted for round 3 (cutoff 24 Nov
12:00 UTC).

## Run

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024x1024, deterministic — two runs are
byte-identical). Pure Python standard library: a hand-rolled PNG
encoder, a 5x7 bitmap font, and fixed-seed grain.
