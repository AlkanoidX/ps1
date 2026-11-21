# PlayTab PS1 discs

Disc images for the PlayTab PS1 site, one folder per game named with its initials.
Each disc is a CHD (`chdman createcd`, same disc once extracted) cut into 8 MiB pieces (`chd/00000.bin`, `00001.bin`, …)
with `chd/disc.json` (`name`, `size`, `piece`, `pieces`); the page streams it by 1 MB ranges while playing, never whole.
`cover.jpg` is the game's box art, taken from its IGDB entry (PlayStation game only).

| Folder | Game | Serial |
|---|---|---|
| `DRV/` | Driver (Europe) | SLES_01816 |
| `SDW/` | Sheep, Dog 'n' Wolf (Europe) | SLES_02895 |
| `CB1/` | Crash Bandicoot (Europe, Australia) | SCES_00344 |
| `CB2/` | Crash Bandicoot 2 - Cortex Strikes Back (Europe) | SCES_00967 |
| `CB3/` | Crash Bandicoot 3 - Warped (Europe, Australia) | SCES_01420 |
| `CBH/` | Crash Bash (USA) | SCUS_94570 |
| `SYD/` | Spyro - Year of the Dragon (Europe) | SCES_02835 |
| `TR/` | Tomb Raider (Europe) | SLES_00024 |
| `DC/` | Dino Crisis (Europe) | SLES_02207 |
| `YFM/` | Yu-Gi-Oh! Forbidden Memories (Europe) | SLES_03947 |
