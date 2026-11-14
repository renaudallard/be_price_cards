# Water cards

What homeassistant_be_water_prices read from each utility's tariff card,
written daily by its `archive_cards.yml` workflow running
`scripts/archive_cards.py`. Not edited by hand.

- `cards/<utility>/<commune>/<YYYY-MM>.json`: the tariff as the integration
  parsed it in that month, for the utility's no-commune fetch (`default`)
  or for one commune of a per-commune utility, named by the commune id the
  integration uses (`_commune_label` in the file says which commune that
  is). This is what an installation reads for a month its utility does
  not serve.
- `texts/<sha256>.txt`: every page, rendered PDF and picture read by OCR
  that a parse read, stored once and shared between the rows that read
  it. Each row lists its own under `_sources`, and names a PDF or a
  picture it read by SHA-256; a picture's source is marked `ocr`.
- `pdfs.json`: where each PDF or picture is kept, as
  `<release tag>/<sha256>.pdf` (`.jpg`, `.png`) in
  the `water-<YYYY-MM>` releases of this repository.
- `coverage.md` and `coverage/<utility>.md`: which months the archive
  holds for each utility and commune, each linking to the PDF or the page
  it was parsed from and to the JSON above; one sheet per utility, the
  index naming them.

To get the original card of a utility, commune and month: open
`coverage.md`, open the utility's sheet, find the row, click `pdf`,
`picture` or `page`; `json` is what the integration parsed out of it.
Months more than thirty-six before the running one are removed; a PDF or a
picture stays as long as a remaining month names it. Until November 2026
the archive was the `archive` branch of homeassistant_be_water_prices,
which older installations still read.
