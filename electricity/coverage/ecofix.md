# ecofix

One row per contract and region, one column per month the branch holds.
Each month links to what it was parsed from and to what came out of it: `pdf` is the
card itself, in the cards repository's releases, `page` the text of a page as it
was read, and `json` the card as the integration parsed it, both on this branch.
A month marked `(mirror)` was copied from the supplier's own archive rather than
captured while it was current; a blank cell is a month the branch does not hold.

| contract | region | 2026-05 |
| --- | --- | --- |
| ecofix_flexy | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/612e345735fcb59ec1d3fcd44df339035e5a4fa00bbd8b10ec11191793ccc9df.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_flexy/flanders/2026-05.json) |
| ecofix_flexy | wallonia | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/612e345735fcb59ec1d3fcd44df339035e5a4fa00bbd8b10ec11191793ccc9df.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_flexy/wallonia/2026-05.json) |
| ecofix_motion | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/04fc42ae92765a26f6e90a9b7c6be47072c8eadb6371d6fb61a88a7ae884ac83.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_motion/flanders/2026-05.json) |
| ecofix_motion | wallonia | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/04fc42ae92765a26f6e90a9b7c6be47072c8eadb6371d6fb61a88a7ae884ac83.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_motion/wallonia/2026-05.json) |
| ecofix_motion_online | flanders | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/19dceb4dd7d07b58c4a3b2337a1e637093ef29b6d47d231242180cc7a2e38f11.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_motion_online/flanders/2026-05.json) |
| ecofix_motion_online | wallonia | [pdf](https://github.com/renaudallard/be_price_cards/releases/download/electricity-2026-05/19dceb4dd7d07b58c4a3b2337a1e637093ef29b6d47d231242180cc7a2e38f11.pdf) [json](https://github.com/renaudallard/homeassistant_be_electricity_prices/blob/archive/ecofix/ecofix_motion_online/wallonia/2026-05.json) |
