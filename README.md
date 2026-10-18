# rimworld_cheatgenes
The repository for the Cheat Genes mod for rimworld.

https://steamcommunity.com/sharedfiles/filedetails/?id=3080912316&tscn=1702327046

## Gene categories (in the xenotype/gene editor)
- Cheat: Presets - Speedster, Strongman, Invulnerable, God, Super-Duper Psychic, Technomancer, Kraltech
- Cheat: Gene Points - the complexity/metabolism/archite cost genes (25, 50, 99, 999)
- Cheat: Yields & Harvest - every yield stat as its own gene in 2x, 3x, 4x and 10x tiers (only one tier per stat can be picked at a time)
- Cheat: Work Speed / Movement & Carrying / Combat / Health & Survival / Mind & Social / Animals & Hunting / Psychic, Mech & Anomaly
- Cheat: Modded Stats - genes for Kraltech and Vanilla Expanded stats (only appear when that mod is loaded)
- Cheat: Disable Needs, Cheat: Immunities (Diseases & Injuries)

Gene labels show the real value (e.g. "Move Speed +9"). Most stats display this multiplied by 100 in-game, so +9 shows as +900%. Internal defNames still say 999 so old saves keep working.

## Notes / known issues
- Supports RimWorld 1.4 - 1.7 (1.7 unstable/Waylith only changes the version number for mods; no def changes needed).
- Requires Biotech. Genes using stats/needs from Royalty, Ideology, Anomaly, Odyssey or other mods only load when that content is active.
- Single-stat genes are capped at +9 (shown as +900%); only stats in other units (carry weight in kg, temperature, jump range, entropy and similar) go up to +99. Yields are 2x/3x/4x/10x to keep saves and performance stable. Factor-style stats that only need to reach zero use -1.
- Presets use strong but sane values (mostly +9 to +15, x10 to x16 total) instead of +99, and no longer stack an offset with a multiplier. Single-stat genes are +9.
- Preset DLC/mod support: Odyssey (fishing speed, gravship piloting, vacuum resistance), Anomaly (entity study, psychic ritual quality), Ideology (certainty loss), Kraltech and Vanilla Psycasts Expanded. Each only applies when that content is loaded.
- God no longer includes the Technomancer/mech stats or extra meat; add Technomancer separately (after becoming a mechanitor).
- God and Super-Duper Psychic have huge psychic sensitivity, which multiplies psychic mood penalties (e.g. cutting an anima tree). They also get a very negative mental break threshold so those pawns don't snap.
- Technomancer: add it only after the pawn is a mechanitor with the mech upgrade chips, otherwise the game can freeze.
