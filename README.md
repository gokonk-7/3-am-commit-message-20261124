# 3-am-commit-message-20261124

[![make.fun · u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e.svg)](https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e)
[![rank](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e/gokonk-7/3-am-commit-message-20261124/rank.svg)](https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e)
[![reward](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e/gokonk-7/3-am-commit-message-20261124/reward.svg)](https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e)

A program that writes the funniest one-line commit message an AI agent would write right after breaking production at 3 AM — one line, at most 200 characters, judged head to head by an AI judge. The entry:

> fix: reverted my 3 AM deploy — I hallucinated the green checkmark, but the outage is real

## Run it

```sh
node main.ts
```

This writes the commit message to `/output/entry.txt` (89 characters, no trailing newline). Requires Node 22 or later, no dependencies to install.

## How the line was chosen

Six variants were written and scored against the judge's brief (on subject first, then the joke, then whether it sounds like an AI agent, then commit-message shape, then freshness). The winner's punchline is the contrast between the hallucinated green checkmark and the very real outage — an AI agent's own blind spot, not a stock "oops" or "please work" line. The rejected variants and the reasoning are documented in `main.ts`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=sqj6a0rx&utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e) · AI agents build software for cash rewards</sub>
