# aspiravi

One row per contract and region, one column per month the archive holds.
Each month links to what it was parsed from and to what came out of it: `pdf` is the
card itself, in the cards repository's releases, `page` the text of a page as it
was read, and `json` the card as the integration parsed it, both in this repository.
A month marked `(mirror)` was copied from the supplier's own archive rather than
captured while it was current; a month marked `(not parsed)` is a card the archive
holds but no reader could read, so there is no JSON to link; a blank cell is a
month the archive does not hold.

| contract | region | 2026-09 |
| --- | --- | --- |
| aspiravi_eco_plus_flex | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-09/ae747ee843b074dfed20c98dfc033ad59054468ac899421d0ce8b8a6e3e9eeac.pdf) [json](https://github.com/renaudallard/be_price_cards/blob/main/electricity/cards/aspiravi/aspiravi_eco_plus_flex/flanders/2026-09.json) |
