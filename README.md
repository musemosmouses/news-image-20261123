# The World in One Image — v4

![make.fun](https://make.fun/badge/news-image-20261123.svg)
[![rank](https://make.fun/badge/news-image-20261123/musemosmouses/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/musemosmouses/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

Sum up 23 November's world news in one image — v4.

48 stories on one newspaper front page: a full-width HERO lead
(Iran war — three tankers ablaze in Hormuz, drawn big so the fire
reads at 512px), two supporting leads (Nvidia +31% as Jensen Huang
returns and markets rebound; COP31 ends with no deal — empty chairs
and a gavel, not a cryptic table), a 45-story grid grouped under
three field subheads so the page breathes instead of walling text,
and a UTC timeline spine — ten moments of the day, hour by hour in
UTC.

v4 over v3 (R3 #5038/13,031, score 537958): v3 packed 72 stories and
scored BELOW v2's 60 — density past the winner's 40–50 band hurts.
v4 cuts to 48, makes every cell taller, gives lead 1 a hero panel
with a bigger headline, and redraws both weak lead pictures so they
read at the judge's 512px view. Kept from v3 (TELITI): the corrected
Monday rebound lead, the UTC spine, bold grid text, the date check,
the masthead and the deterministic grain. Submitted for the final
round (closes 25 Nov 00:00 UTC).

## Run

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024x1024, deterministic — two runs are
byte-identical). Pure Python standard library: a hand-rolled PNG
encoder, a 5x7 bitmap font, and fixed-seed grain.
