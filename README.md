# Assault Fire Redeploy Update

Open **TCLS/client.exe → update inside the original launcher → login**. Your normal shortcut can point to that same client.

## Install the native patch once

1. Close the game and launcher.
2. Download [**AFR-Native-TCLS-Patch-v1.0.2.exe**](https://github.com/Maguri0922/Assault-Fire-Redeploy-Update/releases/download/stable-20261012-1/AFR-Native-TCLS-Patch-v1.0.2.exe) from the [latest release](https://github.com/Maguri0922/Assault-Fire-Redeploy-Update/releases/latest).
3. Run it once and select **client.exe** inside your existing game’s **TCLS** folder.
4. After installation, open that same **TCLS/client.exe** or its normal shortcut.

Future signed patches download and install inside the original TCLS window before login. The original client executable, game assets and accounts are preserved. Internal update components stay inside TCLS. The original game may show its usual Windows administrator prompt.

There is no separate daily updater or command. Native patch **v1.0.2** supersedes all earlier native patches and the old bootstrap / INSTALL / PLAY instructions. Direct startup and repeated quick restarts were verified in the main game.

## Publishing game updates

Current signed game version: **1.0.0.25**. Editing a local file does not publish it or change players’ versions. The developer packages the approved changes, signs a release manifest with its target version, and publishes the patch and manifest to GitHub. Players receive that published version the next time they open the launcher.

The manifest.json and stable patch ZIP release assets are read automatically by TCLS. Players only need the one-time v1.0.2 native patch above. Use the Assault Fire Redeploy community support channel for game downloads, announcements and update problems.
