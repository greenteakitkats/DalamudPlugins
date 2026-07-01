# Dalamud Plugins

This is a custom [Dalamud](https://github.com/goatcorp/Dalamud) plugin repository
for [@greenteakitkats](https://github.com/greenteakitkats)'s FFXIV plugins. Add it
once and every plugin here, now and in the future, shows up in-game.

## Install

1. In-game, open `/xlsettings`, go to **Experimental**, then **Custom Plugin Repositories**.
2. Add this URL and enable it:
   ```
   https://raw.githubusercontent.com/greenteakitkats/DalamudPlugins/main/repo.json
   ```
3. Open `/xlplugins` and install any plugin below.

## Plugins

- **[Housing History](https://github.com/greenteakitkats/HousingHistory)**: a
  read-only log of the furniture you place, remove, move, rotate, and dye while
  decorating, with coordinates and a look at what changed since your last visit.

## How it stays current

`repo.json` is rebuilt automatically by
[`update.yml`](.github/workflows/update.yml), which reads each plugin's latest
GitHub release (listed in [`plugins.txt`](plugins.txt)) for its version and API
level. To add a plugin, put its `owner/repo` on a new line in `plugins.txt`.
