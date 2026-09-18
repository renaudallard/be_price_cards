# Price cards

Everything the Belgian price integrations read off a supplier's tariff card:
the card itself, kept as a release asset named by its SHA-256, and what was
parsed out of it. One namespace per integration:

- `electricity/`: homeassistant_be_electricity_prices, releases `electricity-<YYYY-MM>`.
- `water/`: be_water_prices, releases `water-<YYYY-MM>`.

Nothing here is edited by hand.
