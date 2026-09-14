# Electricity cards

What homeassistant_be_electricity_prices read from each supplier's tariff card,
written daily by its `archive_cards.yml` workflow.

- `coverage.md`: the index of one sheet per supplier under `coverage/`; each
  sheet lists per contract and region the months held, each linking to its card
  and to what was parsed out of it.
- `cards/<supplier>/<contract>/<region>/<YYYY-MM>.json`: the card as the
  integration parsed it. This is what an installation reads for a past month.
- `texts/<YYYY-MM>/<sha256>.txt`: the document text a parse read, stored once
  and shared between the cards that read it. A card handed over inside another
  document is a `{{card:<sha256>}}` reference rather than a second copy of it.
- `pdfs.json`: which release holds each card, by SHA-256.
- `unparsed.json`: the cards kept that no reader could read, by the row they
  would have become.

The PDFs themselves are the assets of the `electricity-<YYYY-MM>` releases of
this repository, one release per month of cards, each file named by its SHA-256.
