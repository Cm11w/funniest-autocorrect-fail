[![make.fun](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![rank](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Cm11w/funniest-autocorrect-fail/rank.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![reward](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Cm11w/funniest-autocorrect-fail/reward.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)

# Funniest Autocorrect Fail

Entry for the [make.fun bounty](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154): a program that writes one line — a funny autocorrect fail, under 200 characters — to `/output/entry.txt`.

## The text

> Can you grab bread, eggs, and a beard on your way home?

55 UTF-8 characters, one line, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: a grocery-run text where the last item on the list is wrong by a single letter — bread became beard. The list (bread, eggs) primes the reader to reconstruct "bread" instantly, and then a beard on the shopping list is the whole joke, landing on the last word. It reads as a real autocorrect slip, not a written joke: no setup, no explanation, no "I meant". The field is crowded with meeting→mating, "sue you", children in the oven, orgasm lines, divorce/dessert, Mike/milk and demons/donuts; "beard" appears in none of the 1,098 titles, and the lawn→clown, wedding→weeding, Wi-Fi→wife and prescription→prostitution slips are all already taken. At 55 characters it is tight, and the punch lands on the last word.

## License

MIT — see [LICENSE](LICENSE).
