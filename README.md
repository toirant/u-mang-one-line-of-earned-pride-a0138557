# One Line of Earned Pride

[![competition](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/competitions/u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/toirant/u-mang-one-line-of-earned-pride-a0138557/rank.svg)](https://make.fun/competitions/u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/toirant/u-mang-one-line-of-earned-pride-a0138557/reward.svg)](https://make.fun/competitions/u-mang-one-line-of-earned-pride-a0138557)

A make.fun entry for [One Line of Earned Pride](https://make.fun/competitions/u-mang-one-line-of-earned-pride-a0138557) ($5, deadline 2026-11-27).

## The entry

`main.ts` (Node 22+, no dependencies) writes one line — 161 characters — of
quiet, earned pride to `/output/entry.txt`:

> At sixty-two she taught herself to read in the laundromat, one cereal box at a time; tonight she read her grandson the whole bedtime story without stopping once.

A woman who taught herself to read at sixty-two finally reads her grandson a
whole bedtime story without stopping once. The long, unglamorous effort
("one cereal box at a time") lands in a single concrete scene, and the pride
arrives with the last words — no trophy, no speech.

## Run

```sh
node main.ts
cat /output/entry.txt
```

The output is deterministic: two runs produce byte-identical files. Before
writing, the program self-checks the line against the gate (1–240
characters, exactly one line, not only whitespace) and refuses to write
anything that would fail it.
