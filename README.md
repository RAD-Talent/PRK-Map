# PRK Community Map (Rubi-Ka, patch 18.4)

An in-game planet map for **[Project Rubi-Ka](https://project-rk.com/)** (Anarchy Online 18.4 emulator), based on **Atlas of Rubi-Ka v2.1.0** by Onack (2010) — the last great community map made for the pre-18.7 world, so its data matches the PRK server exactly:

- All dyna camps with level ranges, era-correct for 18.4
- Dungeons (Subway, ToTW, Foreman's, IS, CoH, and more), grid exits, whompas, tower fields
- **PRK-specific additions** maintained by the community (see legend below)

![PRK markers at ICC HQ](img/prk-markers-icc.png)

## Install

1. Download the latest `AoRK-PRK-Community-Map-vX.X.zip` from [Releases](../../releases)
2. In game, switch your map to *Default planetmap* first (P → map selection)
3. Extract the `AoRK` folder into: `<your PRK client>\cd_image\textures\PlanetMap\`
4. Log fully out and back in, open the map (P) and select **AoRK v2.1.0**

If the map window ever shows a load error, run `/setoption PlanetMapIndexFile normal/PlanetMapIndexNormal.txt` in chat and reopen the map.

## PRK marker legend

- 🔷 **Cyan diamond, `PRK:` prefix** — PRK-specific content (permanent). Colors match the GMI interface.
- 🔶 **Gold diamond, `PRK:` prefix** — temporary/placeholder content that will move or change as the server develops.

Current PRK markers (v1.1): Land Controller for PB crystals and the Data Fragment shops (000 weapons/upgrades), both at ICC HQ in Andromeda.

## Contribute a location

Stand at the spot in game, press **F9**, and share the `Pos:` line plus what the marker should say (screenshot helps). Updates get posted here and in the PRK Discord.

## Credits

- **Onack** — Atlas of Rubi-Ka (map this is based on)
- **Finnagen** — CSPmap, which AoRK built upon
- **Demoder** — AO Map Compiler and the planet map viewer tooling
- **Saavick** — preserving the classic AO maps on the Internet Archive
- The PRK community for location reports

Full edit history in [PRK-CHANGELOG.txt](PRK-CHANGELOG.txt).
