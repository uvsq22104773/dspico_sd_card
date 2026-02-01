# DS_Pico SD Card Resources (Pico Launcher)

Complete ready-to-use SD card image for **DS_Pico** with **Pico Launcher**. Everything is pre-configured to boot directly and launch your DS ROMs!

## File Structure

| Fichier/Dossier | Description |
|-----------------|-------------|
| `roms/` | Put your DS games here (.nds files) |
| `_pico/covers/user/` | Custom boxart images |

## Adding Boxart (Covers)
1. **Exact size**: 128x96 pixels (BMP format).
2. **Important**: Leave **22px empty on the right** (reserved for UI).
3. **Folder**: `_pico/covers/user/`
4. **Naming**: **Exact match to ROM** ex. `mario_kart.nds.bmp`
   - `SuperMario64DS.nds` → `SuperMario64DS.nds.bmp`
   - Case sensitive! No spaces, special characters.

## Prefer Twilight Menu++ instead?
Switch to the **`twilight`** branch of this repo for full Twilight Menu++ setup (nds-bootstrap + performance options).

**Legal**: Use only your own dumps. MIT License. Compatible with DS/DSi/3DS slot-1.
