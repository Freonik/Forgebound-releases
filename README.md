<h1 align="center">⚒ Forgebound</h1>

<p align="center"><b>Legendary weapons that exist only once. Forge them, defend them, don't let anyone take them.</b><br>
Paper 1.21.11 · Java 21</p>

<p align="center"><b>📖 <a href="https://freonik.github.io/Forgebound-releases/">Wiki (CZ / EN)</a></b></p>

This repository holds the **releases** of the Forgebound plugins. Download them from **[Releases](../../releases)**.

| Plugin | File | What it does |
|---|---|---|
| **Forgebound** | `Forgebound.jar` + `Forgebound-pack.zip` | Legendary weapons, relics and armor sets, forge rituals, stars, bounties, events, quests |
| **Forgebound Guard** | `ForgeboundGuard.jar` | Chat filter and AI moderator, mining watch, performance watchdog |
| **Forgebound Teams** | `ForgeboundTeams.jar` | Teams of up to 3, alliances, wars, team chat and a leaderboard |

## Install

1. Put the jars into `plugins/` and restart the server.
2. Point `server.properties` to the resource pack (this link always gives the newest one):
   ```
   resource-pack=https://github.com/Freonik/Forgebound-releases/releases/latest/download/Forgebound-pack.zip
   ```
   The plugin fills in `resource-pack-sha1` by itself.
3. Done. All three plugins update themselves: a new version is downloaded into `plugins/update/` and used after the next restart.

`latest.json` lists the newest version of every plugin; the updaters read it.

## License

© Freonik. All rights reserved. The plugins may be used on your server; redistributing or modifying them is not allowed.
