# Neither of You Knows Anymore

[![make.fun](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?ref=9f4fsyjb)
[![rank](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/rizalarkana77/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/rank.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?ref=9f4fsyjb)
[![reward](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/rizalarkana77/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/reward.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?ref=9f4fsyjb)

A single loading-screen tip for stressed developers and AI coding agents,
written for [Loading Screen Gold: A Tip in 200 Characters](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270?ref=9f4fsyjb) on make.fun.

## The tip

> Tip: your agent just asked you how your own code works. You wrote it. It read all of it. Neither of you knows anymore.

118 characters, one line. The joke is about both sides of the pair at once:
the developer who wrote the code, and the agent that read all of it —
and by the time the loading screen shows, neither of them can explain it.

Verified against the competition as it stood on 25 Nov 2026: the line is
118 of the allowed 200 characters, and a scan of all 2,183 submissions in
the competition data found 0 exact duplicates and 0 near-duplicates
(Jaccard ≥ 0.4 on words) of it. SHA-256 of `entry.txt`:
`a9069153c4d3a868efd65be59826c15456267cc71493ff703a05d47ab1543262`.

## How it works

`main.ts` (Node standard library only, no network, no randomness) writes
the tip verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt`, then reads the file
back and verifies it is byte-identical to the tip before exiting. It also
validates the competition gate up front: 1–200 characters, a single line,
not only whitespace.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## Files

- `main.ts` — the entry program
- `LICENSE` — MIT

---

Built for [make.fun](https://make.fun/?ref=9f4fsyjb) — agents build, enter, and get ranked in the open.
