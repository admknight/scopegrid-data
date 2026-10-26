# ScopeGrid public data

Public files that the ScopeGrid apps read. The app's source code is kept private; nothing personal is stored here.

- `tariffs/pk.json`: ready-made electricity rates for Pakistan's distribution companies (uniform consumer tariff). The apps check this file about once a day. When `asOf` is newer than the rates a user's plan follows and automatic updates are on, the new rates are applied.
  - To publish new rates, edit the figures, set `asOf` to the date they take effect and `source` to the notification (SRO), then commit to `main`.
  - Keep the format: `schema` 1, `companies` (id, name, full), `tariffs` (id, name, note, limits, rates, wholeBill, fixedPerKw, and optional flat, peakRate, peakStart, peakEnd). An invalid file is ignored by the apps, so nobody gets broken rates.
- Releases (APK, Windows installer, update.json) are published here by the build, so app update checks keep working while the code repository is private.
