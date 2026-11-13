# Crimson Desert Atlas

Public release hub for the Atlas Windows companion for Crimson Desert.

Atlas brings maps, quest and faction journals, an item catalog, and live game
information into a local companion app. Personal notes and imported saves remain
on your computer; this repository contains neither personal profiles nor private
source code.

## Download

Current beta: **[Betav0.1.18_1.0.0.3663](https://github.com/JayDubb85/Atlas-Releases/releases/tag/Betav0.1.18_1.0.0.3663)**.

**[Download Online Setup](https://github.com/JayDubb85/Atlas-Releases/releases/download/Betav0.1.18_1.0.0.3663/CrimsonAtlas-Betav0.1.18_1.0.0.3663-Online-Setup.exe)**

Setup downloads and verifies its content automatically. No GitHub login or manual
ZIP extraction is needed. Install over the previous beta; notes are preserved.
Restart the game once if an older native connector remains loaded.

This release updates live readers and native features for game **1.0.0.3663**,
fixes the Looter ownership check, and prevents exchanges of stacked equipped
items. It also improves update-dialog contrast and changes app updates to
download only the Setup EXE; Setup downloads missing content packages afterward.
All existing artwork, inventory, navigation, pin and diagnostic features remain.

Real-game checks cover pins, Insects at 25/200 meters, inventory in four menu
states, storage, equipment, native map/minimap routes and the golden trail.
The final connector's live Rest retest was explicitly waived; Rest passed on the
first 3663 connector and its source is unchanged. Active-storm visuals and Oongka
were not retested on this patch. See the release notes for full validation scope.

Beta17 and earlier may still pre-download content while updating to Beta18.
Installer-only downloads take effect once Beta18 is installed.

Tap Space to place a pin or remove a highlighted nearby pin; hold Space for
0.5 seconds to change its saved appearance. The existing maps, catalogs,
quest and faction journals, and game-version warnings are included.

The installed companion window now provides **Check for updates** and
**Export diagnostic logs**. Background logs are bounded and stay local. Export
a ZIP to share when troubleshooting; saves, inventory and full memory dumps are
excluded. Nothing uploads automatically. The website's Updates control remains.

Existing updater-equipped betas can find this release through **Updates > Check
for updates**. Download the update, choose **Install update**, complete Setup and
reopen Atlas.

This is unsigned beta software. Code signing and antivirus vendor review are
pending; this release does not claim antivirus clearance. Do not disable protection.

## Support

Report problems using [Issues](https://github.com/JayDubb85/Atlas-Releases/issues).
Include the Atlas/game version, steps and expected/actual behavior. Review the
exported diagnostic ZIP before sharing; do not post saves or credentials.

Atlas is an unofficial companion and is not affiliated with Pearl Abyss.
