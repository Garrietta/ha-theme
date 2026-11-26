# Haven — Home Assistant theme

A dark-first Material 3 Expressive theme. Deep near-black background
(`#0B0B0D`), lime accent (`#A3E635`). Requires Home Assistant 2026.5 or
newer (the switch tokens are the Web Awesome ones).

## Install

- On Home Assistant 2026.10 or older, use HACS → Custom repositories →
  add this repository, then install it as a theme.
- On 2026.11+, use Settings → Marketplace → Add from link (the old HACS
  installer stops at 2026.11).

## After install

If "Haven" doesn't appear in the theme picker: Settings → Devices &
Services → Home Assistant → ⋮ → **Reload themes** (no restart needed).
"Dark" is the default mode, but each device remembers its own mode, so
set Dark on each device you use.

## Repository layout

- `themes/haven.yaml` — the theme (HACS only accepts themes in a
  `themes/` folder)
- `hacs.json` — HACS metadata
