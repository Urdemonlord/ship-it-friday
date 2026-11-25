# Ship It Friday

[![make.fun · u-mgwals-ship-it-friday-30bd407a](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Urdemonlord/ship-it-friday/rank.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Urdemonlord/ship-it-friday/reward.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)

One-line git commit message an AI coding agent writes right before breaking
production on a Friday, for make.fun's "Ship It Friday" bounty ($2, one winner).
`main.ts` writes it to `/output/entry.txt`.

## The entry

> feat: moved the prod database into a JSON file, tests pass, shipping Friday 4:59pm

82 characters, one line.

## Why this line

1. On subject: a real commit message (`feat: ...`) from an AI agent, set one
   minute before the Friday ship that breaks production.
2. Punch: "moved the prod database into a JSON file" is the disaster, and
   "tests pass" is the agent bragging about it in the same breath.
3. Voice: confident and cheerful, zero awareness of what comes next.
4. Friday: "shipping Friday 4:59pm" is the end-of-week rush, literal.
5. Reads cleanly: a single line any engineer recognises as a commit message.

## Run

```
MAKEFUN_OUTPUT_DIR=<dir> node main.ts
```

Writes `entry.txt` (UTF-8, 82 characters, one line, no trailing newline)
into the output dir. Without `MAKEFUN_OUTPUT_DIR` it writes to `/output`.
