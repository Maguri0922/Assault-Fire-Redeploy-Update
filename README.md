# Assault Fire Redeploy Update

Open **TCLS/client.exe → signed update inside the original launcher → login → server START → game**. Keep using your normal shortcut to that client. The game version stays **1.0.0.25**.

## Install native content updating once

1. Close the game and launcher.
2. Download [**AFR-Native-TCLS-Patch-v1.1.0.exe**](https://github.com/Maguri0922/Assault-Fire-Redeploy-Update/releases/download/content-20261015-r2/AFR-Native-TCLS-Patch-v1.1.0.exe).
3. Run it and select **client.exe** inside the existing game’s **TCLS** folder. A healthy **1.0.0.25** client with the signed AFR updater already installed is required.
4. Open that same **TCLS/client.exe** normally. It downloads and verifies the published content before login.
5. After the first content update, close and reopen the launcher once to load the new panels.

Use a simple folder path such as `C:\AssaultFirePH`. Original-launcher rendering from folders with non-ASCII or reserved characters has not passed acceptance. The original game may show its usual Windows administrator prompt.

Content revision 2 includes the Redeploy launcher panels, server-selection layout, splash and game UI. Internal integration version **1.1.0** is separate from game version **1.0.0.25**. No separate daily updater, command, scheduled task or Windows service is added.

Later approved content updates arrive through the original launcher; players do not rerun this installer for every content update. The original client executable and account data are preserved. The ZIP and signed manifest are read automatically; players download only the installer.

## Publishing changes

Editing a file on the developer PC does not publish it. The developer packages the approved client changes, assigns a new content revision, signs the manifest, and publishes the files and discovery feed to GitHub. The launcher verifies that published revision on the next start. Server-only changes stay on the server.

The content feed is `channels/native-v2/manifest.json`. The earlier stable feed remains available for existing integrations. Release downloads and checksums are on the [current release](https://github.com/Maguri0922/Assault-Fire-Redeploy-Update/releases/tag/content-20261015-r2).
