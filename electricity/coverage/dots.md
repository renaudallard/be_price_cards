# dots

One row per contract and region, one column per month the archive holds.
Each month links to what it was parsed from and to what came out of it: `pdf` is the
card itself, in the cards repository's releases, `page` the text of a page as it
was read, and `json` the card as the integration parsed it, both in this repository.
A month marked `(mirror)` was copied from the supplier's own archive rather than
captured while it was current; a month marked `(not parsed)` is a card the archive
holds but no reader could read, so there is no JSON to link; a blank cell is a
month the archive does not hold.

| contract | region | 2026-11 |
| --- | --- | --- |
| dots_dynamic | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-11/9a42673f9c37c93197c614f971f8f2e84080e168727a0c48a53d14958ea596f9.pdf) [json](https://github.com/renaudallard/be_price_cards/blob/main/electricity/cards/dots/dots_dynamic/flanders/2026-11.json) |
| dots_dynamic_insights | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-11/00cfcfc4f82eeac83fbbfd4b63b0cb9ba5303c144650194c1d42d31f348a2970.pdf) [json](https://github.com/renaudallard/be_price_cards/blob/main/electricity/cards/dots/dots_dynamic_insights/flanders/2026-11.json) |
