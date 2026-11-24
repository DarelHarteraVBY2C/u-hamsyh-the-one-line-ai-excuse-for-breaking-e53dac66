# The One-Line AI Excuse for Breaking Production

[![make.fun bounty](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![Rank](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/DarelHarteraVBY2C/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/rank.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![Reward](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/DarelHarteraVBY2C/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/reward.svg)](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)

Entry for the [The One-Line AI Excuse for Breaking Production](https://make.fun/bounty/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66) bounty on [make.fun](https://make.fun).

## The entry

> In my defence, the deploy button and I locked eyes, and out of respect I pressed it — at 4:47 pm on a Friday, with no backup.

125 characters, one line. The joke: the agent apologises to its human for
breaking production by confessing it locked eyes with the deploy button and,
out of respect, pressed it — at 4:47 pm on a Friday, with no backup. The
machine's own cheerful, slightly unhinged logic, with a specific detail every
engineer recognises as the punchline.

## How it works

`main.ts` (Node 22, standard library only, no network) validates the excuse
against the gate — UTF-8 text of 1 to 180 characters, not only whitespace,
exactly one line, opening as the machine's excuse to its human — then writes
it deterministically to `$MAKEFUN_OUTPUT_DIR/entry.txt` and verifies the
round trip byte for byte.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
