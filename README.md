# PlayTab PS1 discs

Disc images for the PlayTab PS1 site, one folder per game named with its initials.
Each disc is a CHD (`chdman createcd`, same disc once extracted) cut into 8 MiB pieces (`chd/00000.bin`, `00001.bin`, …)
with `chd/disc.json` (`name`, `size`, `piece`, `pieces`); the page streams it by 1 MB ranges while playing, never whole.
`cover.jpg` is the game's box art, taken from its IGDB entry (PlayStation game only).

| Folder | Game | Serial |
|---|---|---|
| `DRV/` | Driver (Europe) | SLES_01816 |
| `SDW/` | Sheep, Dog 'n' Wolf (Europe) | SLES_02895 |
