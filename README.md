# Multisystem 2 Arcade – 6-Button Arcade Cabinet Input Maps

WORK-IN-PROGRESS
Per-core button mappings for a dedicated 6-button arcade cabinet running a Multisystem 2.
Horizontal games only.

## Hardware
- Multisystem 2 Arcade (MiSTer-based), 6-button JAMMA control panel
- Controller ID (VID:PID): `0fb6_3e05`. These maps only work with this input device.
- Tested on MiSTer update from: 28/9/26

## Button layout
```
[ 1 ] [ 2 ] [ 3 ]
[ 4 ] [ 5 ] [ 6 ]
```

## Credits and freeplay
- Most 6-button games are set to freeplay via their service mode or DIP switch settings.
- 6-button games without a freeplay option use Wizzo's MiSTer Remote to add credits.
  I also use the remote to open the OSD menu:
  https://github.com/wizzomafizzo/mrext/blob/main/docs/remote.md
- Games with fewer than 6 action buttons have **button 6 mapped as Coin/Credit**.

## Installation
1. Back up your existing `/media/fat/config/inputs/` folder.
2. Copy the `.map` files from this repo's `config/inputs/` folder into `/media/fat/config/inputs/` on your SD card.
3. Restart the MiSTer.

## Files
| File | Core / games covered | 
|------|----------------------|
| example_input_XXXX_XXXX_v3.map | Street Fighter II etc. | 

## Licence
CC0 – see LICENSE file.

