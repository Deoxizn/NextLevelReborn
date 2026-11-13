# Changelog

## [2.1.2] - 2026-11-12

- Corrected the Wago project ID to `qGYBbRNg`. Version 2.1.1 used the docs example ID and the Wago upload failed with no project found. No code changes.

## [2.1.1] - 2026-11-12

- Wago publishing only. Added `## X-Wago-ID: as3Dfg57` to the TOC and added the `WAGO_API_TOKEN` repo secret so the BigWigs packager uploads to Wago. No code changes.

## [2.1.0] - 2026-11-12

- Initial release of NextLevelReborn for Midnight Season 2 (12.1.5, Interface 120105).
- Remake of Nextlevel - Classic (WoWInterface, 2019). After any XP or reputation gain, prints how many more gains like that you need to level up or reach the next standing.
- Chat prefix shortened to `NLR`, slash commands `/nlr` and `/nextlevel`.
- Kills and other XP gains tracked separately, with a rolling average of the last 10 kills, plus XP/hr and time-to-level.
- No Combat Log use. XP and rep are read from `UnitXP` / `PLAYER_XP_UPDATE` and `GetFactionInfo` / `UPDATE_FACTION`.
- At level 90 the XP half turns itself off, rep / Renown keeps running.
