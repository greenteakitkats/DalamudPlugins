# Dalamud Plugins

A custom [Dalamud](https://github.com/goatcorp/Dalamud) plugin repository for
[@greenteakitkats](https://github.com/greenteakitkats)'s FFXIV plugins. Add it
once and every plugin here (now and future) is available in-game.

## Install

1. In-game: `/xlsettings` → **Experimental** → **Custom Plugin Repositories**.
2. Add and enable:
   ```
   https://raw.githubusercontent.com/greenteakitkats/DalamudPlugins/main/repo.json
   ```
3. Open `/xlplugins` and install any plugin below.

## Plugins

- **[Housing History](https://github.com/greenteakitkats/HousingHistory)** — a
  read-only log of furniture placed, removed, moved, rotated, and dyed in your
  house, with coordinates and a "since last visit" diff.

## How it stays current

`repo.json` is regenerated automatically by
[`update.yml`](.github/workflows/update.yml), which reads each plugin's latest
GitHub release (listed in [`plugins.txt`](plugins.txt)) for its version and API
level. To add a plugin, append its `owner/repo` to `plugins.txt`.
