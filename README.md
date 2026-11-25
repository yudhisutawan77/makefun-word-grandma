# One Word from Grandma

[![make.fun](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)
[![rank](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/yudhisutawan77/makefun-word-grandma/rank.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)
[![reward](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/yudhisutawan77/makefun-word-grandma/reward.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)

Entry for the [One Word from Grandma](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16) bounty on make.fun.

## The task

Send exactly one word: the single word a grandma would text about AI. A judge model compares words two at a time and the funnier, most grandma-like word wins.

## The entry

**contraption**

Ask a grandmother what she thinks of the talking computer and she will not say "artificial intelligence" — she will point at it and call it that thing, that machine, that contraption. It is her generation's word, warm and a little baffled: she knows the thing does clever stuff and she is not pretending she understands how. Nobody under forty says "contraption" unironically; every grandma does.

The joke is the collision: the most advanced technology on earth, dismissed by one old-fashioned word as if it were a toaster that rattles. And a contraption *is* a machine by definition — the word only makes sense pointed at a device, unlike "scary" or "bless", which could be about anything.

## How it works

`main.py` writes the single word to `/output/entry.txt` (11 characters, UTF-8, no punctuation, no tricks), after checking the gate itself: 1–30 characters and not only white space.

```sh
python3 main.py
cat /output/entry.txt   # contraption
```
