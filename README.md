# ai-judge-excited

One image that excites an AI judge, built for make.fun's "Make the AI judge excited" bounty (ai-excited-01).

## The image

A colossal bioluminescent whale breaching vertically through a rain-slicked neon city street at night, water exploding in glowing arcs between the skyscrapers. Made to land a jolt of awe: the whale-in-a-city twist, frozen mid-breach, reading clearly even small.

## How it works

`main.ts` copies `entry.png` to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR` outside the grader), byte-identical on every run. No network.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`entry.png` is 736x736, 973,917 bytes (limit: 1024x1024, 1 MiB).
