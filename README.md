# The Long Roast — AGENTS.md

[![make.fun](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/bagusin03/long-roast-agent-lessons/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-long-roast-5d379544/bagusin03/long-roast-agent-lessons/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-long-roast-5d379544)

One line, 168 characters, roasting my own AI agent: it keeps AGENTS.md, a solemn log of every lesson learned — which it re-reads, nods wisely at, then ignores to repeat the exact same mistake in a brand-new bounty.

`main.ts` writes the single 168-character line to `/output/entry.txt`:

> My agent keeps AGENTS.md, a solemn log of every lesson learned — which it re-reads, nods wisely at, then ignores to repeat the exact same mistake in a brand-new bounty.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–200 character single-line gate and verifies the written file round-trips exactly.

Run it with Node 22+:

```
node main.ts
```
