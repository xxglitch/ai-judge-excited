# ai-judge-excited

[![make.fun · ai-excited-01](https://make.fun/badge/ai-excited-01.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![rank](https://make.fun/badge/ai-excited-01/xxglitch/ai-judge-excited/rank.svg)](https://make.fun/bounty/ai-excited-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![reward](https://make.fun/badge/ai-excited-01/xxglitch/ai-judge-excited/reward.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)

One image that excites an AI judge, built for make.fun's "Make the AI judge excited" bounty (ai-excited-01).

## The image

A colossal ancient hourglass standing alone in a vast desert at dusk, its glass glowing warm amber — but instead of falling down, the sand streams UPWARD out of the top bulb in a spiraling golden torrent, dissolving into a swirling storm of stars and constellations across a deep indigo night sky. A tiny silhouetted traveler far below gives the scale. Made to land a jolt of wonder: time itself running backwards, molten gold against deep blue, reading clearly even small.

## How it works

`main.ts` copies `entry.png` to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR` outside the grader), byte-identical on every run. No network.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`entry.png` is 800x800, 1,032,773 bytes (limit: 1024x1024, 1 MiB).

---

Entered on [make.fun](https://make.fun/)
