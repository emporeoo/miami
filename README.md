# Miami Patches

Performance, visual, and gameplay patches for **Grand Theft Auto VI** on PS5.

## Supported Game
* **Title:** Grand Theft Auto VI
* **Title ID:** `PPSA38500`
* **Game Version:** `v01.002.001`

## Available Patches
* **60 FPS Unlock:** Unlocks the frame rate target to 60 FPS (16.67 ms minimum timestep). *Experimental; requires testing for gameplay speed.*
* **1080p / 900p / 720p Internal Resolution:** Scales internal rendering resolution to `1920x1080`, `1600x900`, or `1280x720` at 4K output. *Enable only one resolution preset at a time; compatible with 60 FPS.*
* **First Person Toggle (Triangle + Circle):** Press `Triangle + Circle` during gameplay to switch between first- and third-person views. *Experimental; keep Touchpad bound to Map.*
* **Low Screen-Space Shadow Samples:** Forces minimum screen-space shadow sample counts, reducing shadow detail. *Experimental; FPS impact untested.*
* **Reduced Moving Traffic (75% Multiplier):** Lowers moving ambient traffic density to 75% while keeping parked cars unchanged. *Experimental; may affect free-roam gameplay.*
* **Disable Vignette:** Zeroes environmental vignette intensity to remove dark screen edges (visual only).
* **Low Local Shadows:** Forces the lowest local-shadow quality tier for nearby light sources. *Experimental; FPS impact untested.*
* **Low Volumetric Lighting:** Forces the lowest volumetric-lighting preset, altering fog and light shafts. *Experimental; FPS impact untested.*

## How to Use
1. **Install Patch System:** Ensure the PS5 Patch System payload (e.g., *etaHEN* / *ps5_patch_system*) is loaded and active on your console.
2. **Transfer Patch File:** Copy `patches/PPSA38500.xml` to your PS5 storage via FTP or USB file manager at:
   ```text
   /data/user/patches/xml_prospero/PPSA38500.xml
   ```
3. **Enable Patches:** Open the Patch System menu on your PS5, select **Grand Theft Auto VI (`PPSA38500`)**, toggle your desired patches, and launch the game.
