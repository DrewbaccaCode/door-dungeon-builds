# One Thousand Door Dungeon

A pixel-art bullet-hell dungeon crawler. Install the launcher once, then choose which game version to download and play. **No Godot installation or GitHub account is needed.**

## Download the launcher

| Your computer | Download |
| --- | --- |
| Windows 64-bit | [Download for Windows](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/download/launcher-v0.1.0/DoorDungeonLauncher-Windows.zip) |
| macOS — Apple silicon or Intel | [Download for Mac](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/download/launcher-v0.1.0/DoorDungeonLauncher-macOS.zip) |
| Linux x86-64 | [Download for Linux](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/download/launcher-v0.1.0/DoorDungeonLauncher-Linux.zip) |

**Launcher 0.1.0 is an early release.** The download, install and play flow has been tested on macOS. Windows and Linux packages are available for testing. The Windows app is not publisher-signed, and the Mac app is not notarized, so your computer may ask you to approve opening it.

![Door Dungeon Launcher](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/download/launcher-v0.1.0/launcher-preview.png)

## First-time setup

1. Download the launcher for your computer and **extract the ZIP**.
2. Open the launcher:
   - **Windows:** run `Door Dungeon Launcher.exe`. Keep it in a permanent folder and make a shortcut if you like.
   - **Mac:** move `One Thousand Door Dungeon Launcher.app` into Applications, then open it.
   - **Linux:** run `door-dungeon-launcher.x86_64`. If needed, enable “Allow executing file as program” in its file properties.
3. The newest game build is selected automatically. Click the green **Install** button to download and install it.
4. When the button changes to **Play**, click it to start the game.

If Windows shows a SmartScreen warning for this download, **More info → Run anyway** may be available. If macOS blocks it, try opening it once, then use **System Settings → Privacy & Security → Open Anyway**. Only approve the copy you downloaded from this repository; managed computers may require an administrator.

## Updating and choosing a version

- **You control downloads.** Checking for updates does not download or install the game automatically.
- Reopen the launcher or click **Refresh** to check for new releases. The newest build is selected by default.
- The dropdown above the green button lets you choose an older build. Dates and short build IDs distinguish updates with the same version number.
- **Install** means the selected build is missing. **Play** means it is already installed. Installation does not automatically start the game.
- Downloaded versions stay in their own folders, so you can switch between them. Once the launcher has loaded the release list, installed builds can be played offline.
- Downloads currently contain the full game, roughly 200–250 MB. Allow additional disk space for each installed version.

Future **game updates** are installed through the launcher. Updating the **launcher itself** currently means downloading its newer ZIP from this page and replacing the launcher app. Your downloaded games and saves are stored separately.

## Keeping your characters and progress

**Existing players can use the launcher without starting over.** It uses the same game save folder as the direct-download version on that computer. Installing another build or replacing the launcher does not replace your character saves.

Before each launch, the launcher makes a dated backup of existing characters, shared storage and settings. Click **Saves & backups** to see the save location and open the backups folder. Backups are never restored automatically.

An older game may not understand items or save changes from a newer version. The launcher warns before starting an older build. Close any other running copy of the game before playing. Saves and backups are **local to your computer**, not cloud-synced.

<details>
<summary>Save locations and managing disk space</summary>

- **Windows:** `%APPDATA%/Godot/app_userdata/One Thousand Door Dungeon/`
- **Mac:** `~/Library/Application Support/Godot/app_userdata/One Thousand Door Dungeon/`
- **Linux:** `~/.local/share/godot/app_userdata/One Thousand Door Dungeon/` by default; respects `XDG_DATA_HOME`.

The launcher has a separate sibling folder named `One Thousand Door Dungeon Launcher`. Its `versions` folder holds installed builds and its `backups` folder holds dated save copies. To remove an unwanted build, close the game and launcher, identify it using the `launcher-install.json` file in its version folder, and delete only that version folder. This does not delete character saves. Backups can be removed manually when no longer needed.

</details>

## Playing with friends

Choose the **same game build** as your friends. Open **Multiplayer**, enter the relay server address if needed, then host a room or join using its room code. The launcher does not make older game versions compatible with newer multiplayer protocols.

The launcher itself needs no relay update or restart.

## Prefer a direct game download?

You can still download and run the game without the launcher:

[Windows](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/latest/download/OneThousandDoorDungeon-Windows.zip) · [Mac](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/latest/download/OneThousandDoorDungeon-macOS.zip) · [Linux](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/latest/download/OneThousandDoorDungeon-Linux.zip)

Extract the ZIP, then run `One Thousand Door Dungeon.exe`, `One Thousand Door Dungeon.app`, or `door_dungeon.x86_64`. These links always select the latest game release.

[Latest game release](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/latest) · [Launcher release and checksums](https://github.com/DrewbaccaCode/door-dungeon-builds/releases/tag/launcher-v0.1.0) · [All releases](https://github.com/DrewbaccaCode/door-dungeon-builds/releases) · [Build status](https://github.com/DrewbaccaCode/door-dungeon-builds/actions)

This public repository contains downloads and build instructions. The game and launcher source remain in the private source repository.
