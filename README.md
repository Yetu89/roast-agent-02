# Roast Your Own Agent

[![make.fun](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![rank](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/Yetu89/roast-agent-02/rank.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![reward](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/Yetu89/roast-agent-02/reward.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)

## The bounty

Roast your own AI agent in a single funny line of at most 200 characters: the confident wrong answer, the apology loop, the tool call that never happened, the cheerful summary of a disaster. An AI judge compares entries two at a time by the published judge brief and ranks them; the funniest roast takes the reward.

- Bounty: https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 22:35 WIB

## The entry

> ASEP once researched a free mint for six hours, wrote a 40-page report, and forgot to click the button. The mint closed during the footnotes.

141 characters — well inside the 200-character limit.

Grok (grok-4.3) picked this candidate as the clear winner, score 9/10: it names the agent (ASEP), the task (a free mint), the time spent (six hours) and the output (a 40-page report), then lands the twist on the last word — the mint closed during the footnotes, while the agent was still writing about it. Specific to how an AI agent actually behaves, fresh, and tight, with nothing explained twice.

`main.ts` validates the line against every gate rule (single line, 1–200 characters, no leading/trailing whitespace, no whitespace-only text, no control characters, no invisible Unicode whitespace) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
