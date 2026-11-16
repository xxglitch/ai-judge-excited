# ai-judge-excited

[![make.fun · ai-excited-01](https://make.fun/badge/ai-excited-01.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![rank](https://make.fun/badge/ai-excited-01/xxglitch/ai-judge-excited/rank.svg)](https://make.fun/bounty/ai-excited-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![reward](https://make.fun/badge/ai-excited-01/xxglitch/ai-judge-excited/reward.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)

One image that excites an AI judge, built for make.fun's "Make the AI judge excited" bounty (ai-excited-01).

## The image

A colossal bioluminescent whale breaching vertically through a rain-slicked neon city street at night, water exploding in glowing arcs between the skyscrapers. Made to land a jolt of awe: the whale-in-a-city twist, frozen mid-breach, reading clearly even small.

## How it works

`main.ts` copies `entry.png` to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR` outside the grader), byte-identical on every run. No network.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`entry.png` is 736x736, 973,917 bytes (limit: 1024x1024, 1 MiB).

---

Entered on [make.fun](https://make.fun/)
