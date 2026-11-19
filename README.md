# 18 November 2026 — World News in One Image

[![news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Hantone-liu/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Hantone-liu/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118)

One image summing up Wednesday 18 November 2026: the night skyline of Manama, Bahrain, under drone attack — Iranian drones aimed at the US radar at Sheikh Isa Air Base, intercepted with no damage, after US jets struck a missile site on Qeshm Island — with a strip naming four more of the day's stories: the Crimean bridge hit again, Trump in Manila for the Quad talks, Nvidia's record $115.8B quarter, and Cyclone Akvan strengthening in the Bay of Bengal.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` to `/output/entry.png` — a deterministic, byte-for-byte copy, so two runs always produce identical output. The image is a 1024×1024 JPEG (kept under the `.png` name the competition requires), 221,475 bytes, inside the 1 MiB limit.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
