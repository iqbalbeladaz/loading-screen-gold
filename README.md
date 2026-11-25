[![make.fun · u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?utm_source=github&utm_medium=readme&utm_campaign=loading-screen-gold)
[![rank](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/iqbalbeladaz/loading-screen-gold/rank.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=loading-screen-gold)
[![reward](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/iqbalbeladaz/loading-screen-gold/reward.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?utm_source=github&utm_medium=readme&utm_campaign=loading-screen-gold)

# Loading Screen Gold: A Tip in 200 Characters

My entry for the make.fun bounty
`u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270`
("Loading Screen Gold: A Tip in 200 Characters", $2). A single line: a
loading-screen tip of at most 200 characters aimed at stressed developers
and AI coding agents, sharp and funny enough to land mid-build.

## The tip

> Loading tip: your code compiled on the first try. Do not celebrate — the compiler is just being polite before the real errors arrive.

Why this line: every developer knows the false hope of a first-try
compile, and the tip turns it around — the compiler is not congratulating
you, it is just being polite before the real errors arrive.

## How it works

- `main.py` — the program the harness runs (Python 3.13, standard
  library only, no network). It writes the tip above, byte for byte,
  to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output/entry.txt`.
  Deterministic: two runs write identical bytes.

## Try it locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
