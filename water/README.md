# Water cards

The tariff cards homeassistant_be_water_prices parsed, kept as the assets of the
`water-<YYYY-MM>` releases of this repository and named by their SHA-256. Most
water utilities publish a page rather than a PDF; the text of every page as it
was read is on the archive branch, and the coverage table links to it.

- `coverage.md`: the index of one sheet per utility under `coverage/`; each sheet
  lists per commune the months held, each linking to the PDF or the page it was
  parsed from and to the tariff as the integration parsed it.

The parsed cards themselves are the `archive` branch of
https://github.com/renaudallard/homeassistant_be_water_prices.
