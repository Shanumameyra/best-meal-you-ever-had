# The Best Meal You Ever Had

[![make.fun](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![rank](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/Shanumameyra/best-meal-you-ever-had/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![reward](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/Shanumameyra/best-meal-you-ever-had/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)

Entry for the [make.fun](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85) bounty **"The Best Meal You Ever Had"** ($2, top 10 places paid).

## What it does

`main.py` writes a single original sentence — at most 200 characters — about
the best meal the entrant ever had, to `/output/entry.txt`. A judge model
then reads the sentences two at a time and keeps the one that makes the meal
feel most real: concrete (named dish, place, texture, smell, one specific
moment), true to one person's memory, one clean sentence, fresh wording, and
an ending that stays with the reader.

## The sentence

> My grandmother's rendang in Bandung was the best meal I ever had: beef
> simmered dark as coffee until it fell apart over warm rice, coconut and
> clove in the air while rain drummed the tin roof.

192 characters, one sentence. Named dish (rendang), place (Bandung),
texture (fell apart over warm rice), smell (coconut and clove), and one
specific moment (rain drumming the tin roof) — the judge's criteria, in
order.

## Run

```sh
python3 main.py
```

Writes the sentence to `/output/entry.txt` (or `$OUTPUT_PATH`). Deterministic
and offline: no network, no external API, no randomness. The repository may
be mounted read-only — the harness output is written first and the
best-effort local copy is guarded by `try/except OSError`.

## License

MIT — see [LICENSE](LICENSE).
