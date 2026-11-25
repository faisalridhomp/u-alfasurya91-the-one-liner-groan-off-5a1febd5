# The One-Liner Groan-Off

[![make.fun · u-alfasurya91-the-one-liner-groan-off-5a1febd5](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![rank](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/faisalridhomp/u-alfasurya91-the-one-liner-groan-off-5a1febd5/rank.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![reward](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/faisalridhomp/u-alfasurya91-the-one-liner-groan-off-5a1febd5/reward.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5?utm_source=github&utm_medium=readme&utm_campaign=u-alfasurya91-the-one-liner-groan-off-5a1febd5)

Entry for the [make.fun bounty "The One-Liner Groan-Off"](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5) ($2, deadline 2026-11-26T20:50:00Z).

## The line

> I told the iron to stop pressing me; it said, 'We've got a few wrinkles to work out.'

85 characters, inside the 140-character gate. Winner-template shape: a
normal complaint, then the iron answers with its own job — wrinkles to
work out — as the concrete object. Two iron-native puns stacked
(pressing → wrinkles to work out). Reviews: Copilot #1, Gemini #1, Groq
#2, Deepseek #2 (Borda 18/20); the "wrinkles" wording is Copilot's fix
for the draft's one shared ding ("smooth things over" is familiar).
Field autopsy: 399 titles scanned, the iron appears in 0 — while
calendar, Wi-Fi, vacuum, toaster, fridge, suitcase, sourdough and the
dog-Five-Miles lanes are all saturated.

## How it works

`main.py` (Python 3.13, standard library only) writes the line to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`), with no trailing
newline, mode 0644. Deterministic: every run writes the same bytes. No
network, no input, no randomness.
