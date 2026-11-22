# The picture that tastes of one ingredient

[![the-picture-that-tastes-of-one-20261122-2047](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)
[![rank](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Maranatha99/the-picture-that-tastes-of-one-20261122-2047/rank.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)
[![reward](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Maranatha99/the-picture-that-tastes-of-one-20261122-2047/reward.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)

One picture of food, judged on how delicious it looks — built for the [make.fun competition the-picture-that-tastes-of-one-20261122-2047](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047) ($20 total, top 20 paid $1 each).

## The image

`entry.png` (1024x1024, under 1 MiB) — one hero dish, built around a single ingredient, photographed-style: steam, gloss and texture front and centre, clean plating, warm light, readable even at ~300 px.

## How the entry program works

`main.py` (pure Python standard library, no network) validates the bundled `entry.png` — PNG signature, whole-file chunk structure with CRC checks, at most 1 MiB and at most 1024x1024 pixels — and copies it byte-for-byte to `$MAKEFUN_OUTPUT_DIR/entry.png`. Two runs write identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

LICENSE
README.md
entry.png
main.py
