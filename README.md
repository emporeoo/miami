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
1. **Download & Install the Payload:** Grab the latest release from [illusionyy/ps-patch-system](https://github.com/illusionyy/ps-patch-system) and install/load it on your PS5.
2. **Transfer the Patch File:** Copy `patches/PPSA38500.xml` to your PS5 via FTP or USB file manager at:
   `/data/user/patches/xml_prospero/PPSA38500.xml`
3. **Enable Patches in the GUI:** Open the **ps-patch-system** GUI app on your PS5, switch to the **PS5** tab, select **`PPSA38500`**, and toggle on the patches you want. *(Enable only one resolution preset at a time.)*
4. **Launch the Game:** Start **Grand Theft Auto VI**—a notification will pop up confirming the patches are active.

## Credits
* **[illusionyy](https://github.com/illusionyy)** — Creator and maintainer of [ps-patch-system](https://github.com/illusionyy/ps-patch-system).
* 
