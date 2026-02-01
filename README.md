# DS_Pico SD Card Resources (Twilight Menu++)

Complete ready-to-use SD card image for **DS_Pico** with **Twilight Menu++**. Pre-configured to boot Twilight directly and launch DS/GBA ROMs!

## File Structure

| Fichier/Dossier | Description |
|-----------------|-------------|
| `roms/` | Put your DS games here (.nds files) |
| `_gba/` | GBA BIOS files (gba_bios.bin) for GBARunner2 |
| `_nds/` | Twilight Menu++ files + nds-bootstrap |
| `_pico/` | **REQUIRED** Pico Loader firmware (.bin files) |
| `_picoboot.NDS` | Twilight Menu++ bootloader |

## ⚡ Speed Boost: Set Games to "Pico Loader" Mode
Twilight uses **nds-bootstrap** by default (slower). Switch to **Pico Loader** for **much faster** loading:

1. Boot Twilight Menu++
2. Go to **Settings** → **Per-Game Settings**
3. Select your game → **Game Loader** → **pico** 
4. **Save** changes
5. Game now boots via DS_Pico hardware (faster, better compatibility!)

**Note**: Pico mode disables cheats/in-game menu but loads 2-3x faster.

## Adding GBA Support
Place `gba_bios.bin` in `_gba/` for GBA games via GBARunner2.

## Prefer Pico Launcher instead?
Switch to the **`pico`** branch for pure Pico Launcher setup (no Twilight).

**Legal**: Use only your own dumps. MIT License. Compatible DS/DSi/3DS slot-1.
