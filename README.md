# Make the AI Judge Feel Proud: A Family Scene

[![make.fun · u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2?utm_source=github&utm_medium=readme&utm_campaign=u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![rank](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/anisakansa/ai-judge-feel-proud/rank.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![reward](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/anisakansa/ai-judge-feel-proud/reward.svg)](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2?utm_source=github&utm_medium=readme&utm_campaign=u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)

My entry for [Make the AI Judge Feel Proud: A Family Scene](https://make.fun/bounty/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2) on [make.fun](https://make.fun).

## The scene

> My daughter drew our family on the fridge: Dad with three arms, Mom taller than the house, and me — smiling, holding everyone's hand.
> She said the extra arm was "for carrying groceries and hugs at the same time."

212 characters, 2 lines. A small domestic moment that is warm, funny and heartfelt: a kid's drawing where Dad has three arms and Mom is taller than the house, explained with flawless kid logic — the extra arm is for carrying groceries and hugs at the same time. Real family on the page, a telling detail instead of a greeting-card line.

## How it works

`main.ts` writes the scene to `output/entry.txt`. It enforces the gate itself before writing: 1–280 characters, one or two lines, not only whitespace — and reads the file back to confirm the bytes on disk match. Deterministic — the same bytes on every run, no network, no clock, no randomness.

```sh
node main.ts
```
