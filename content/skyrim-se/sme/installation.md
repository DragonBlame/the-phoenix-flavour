---
title: "Installation"
weight: 2
type: docs
description: >
  How to install Skyrim Modding Essentials.
---

## Requirements

- [Skyrim Special Edition](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/) on Steam.
- [Skyrim Special Edition: Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) on Steam.
- Latest version of Windows 10 (required by Wabbajack).
- At least a free [Nexus Mods](https://www.nexusmods.com/) account, Premium is recommended.
- Latest drivers for your GPU ([NVIDIA](https://www.nvidia.com/Download/index.aspx) or [AMD](https://www.amd.com/en/support)).

### Disk Space

By itself, **Skyrim Modding Essentials** is tiny: The mods folder is about 2.5GB and the downloads folder smaller than a gigabyte. However, since the list uses the Stock Game folder system (a standalone copy of the base game), that will add another ~13GB to the final folder size.

However, you should keep in mind that a decently sized mod setup can easily exceed 50 or even 100GB in size. It is recommended to install any mod setup on an **SSD** for improved performance and faster loading times.

### MO2 Prerequisites

Mod Organizer 2 requires the Microsoft Visual C++ Redistributable and .NET Framework 4.8, two basic packages. Chances are you already have them installed, but please grab the two installers linked below and run them. If the packages are already present on your system, the installers should notify you.

- Download and install [Visual C++ 2019](https://aka.ms/vs/16/release/vc_redist.x64.exe).
- Download and install [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net48-web-installer).

If either of them were missing on your system, they will be installed now. Afterwards, you may be required to restart your PC.

## Skyrim SE Setup

**SME requires the latest version of Skyrim SE.** For clarification, this latest version is a post-AE release (currently `1.6.353.0`) and unrelated to the Anniversary Edition DLC which is NOT required. If you are on any older version of Skyrim SE, please verify files through Steam to install the update. You can check the version by right-clicking the **SkyrimSE.exe** in your game folder and going to the **Details** tab.

**Please make sure to launch the game at least once before running Wabbajack.** If you just updated or (re)installed the game, this is necessary for setting up registry keys as modding tools will otherwise be unable to recognise the game. You can quit from the main menu.

### Set language to English

**SME requires the English language version of Skyrim SE.**

If you are currently playing in a language other than English, please go into the settings for Skyrim SE in your Steam library and revert the language to English. After changing the language, Steam should automatically download the required files (launch the game to force the download if it doesn't).

After updating the game language, please launch the game once and quit from the main menu.

> This requirement is necessary for Wabbajack. You can change the language after install SME, but remember to also update your SME Game Root folder if you do.

## Creation Kit

In order for Wabbajack to be able to incorporate the Creation Kit properly, you need to install it first through Steam.

- Find the [Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) Steam page (I recommend just using the search function in the Store).
- Click install. The files will be placed into your default game folder.

## Wabbajack Installation

Next up you need to install the Wabbajack tool itself:

- Download [Wabbajack](https://www.wabbajack.org/#/) from the official website.
- Extract the archive to a high-level folder, e.g. `C:\Wabbajack\`.

**Do not install Wabbajack into UAC protected directories.** These include Program Files and Program Files x86 as well as the Downloads, Desktop, Documents, etc, folders.

Double-click **Wabbajack.exe** to launch to tool. It will automatically update itself to the latest version.

### Skyrim Modding Essentials

You can now install SME through Wabbajack:

- Click the **Browse Modlists** button in the Wabbajack tool.
- Find **Skyrim Modding Essentials** in the gallery of mod lists and click the arrow button to download the installation file.

In the installation window, you will need to define two folders:

**Installation Location** is where LOTF will be installed to. Choose a high-level folder such as `C:\Skyrim Modding Essentials\` that is outside UAC protected folders (Program Files, Documents, etc).

**Download Loaction** is where the downloaded mod archives will be stored. By default, they will be placed within your main SME folder, but you can change the file path if you want to keep the files elsewhere.

Once both folder locations have been set, click the button on the right to begin the installation process.

### Installation Process

If you have **Nexus Premium**, this is all you have to do. Lean back and relax while Wabbajack downloads and installs SME for you.

If you only have a free Nexus account, Wabbajack will open the mod pages for you and guide you through the process of downloading all files. Afterwards, it will proceed with the installation as usual.

You can follow along as Wabbajack installs the list. It will display previews with summaries and links to the mods being installed. Don't let the log irritate you. Unless the installation is aborted completely, you don't have to worry about any warnings.

**In case the installation does fail:** Try restarting Wabbajack first. You will not lose progress as the tool will pick up where it left off. Should the installation fail again, please join us on [Discord](https://discord.gg/xCPxJFbCTS), grab the `@SME` role, and post your `wabbajack.current.log` in the `#sme-support` channel. You can find all Wabbajack logs in your Wabbajack installation folder under `\Wabbajack\logs\`.

In most cases the installation should complete successfully on the first try. The tool will let you know when it has.

## Tool Setup

Almost all tools included with SME are automatically configured for you. However, there are exceptions as some tools cannot be shipped with custom profiles so you will have to create them for yourself.

### LOOT

If you want to configure LOOT for SME, follow these steps:

- Run **LOOT** through Mod Organizer 2.

This should load your default game installation folder instead of your SME Game Root folder because it uses the registry path to find the game. Updating that for SME is possible, but also inconvenient because it breaks Creation Organizer and would force you to constantly update the path when switching between different mod setups. It is easier to just modify the LOOT settings.

- Open the **Settings** in LOOT.

![Open LOOT Settings](/Pictures/sme/open-loot-settings.png)

- Go to the **TES V: Skyrim Special Edition** settings.
- Change **Install Path** to your SME Game Root folder.
- Click **Apply** and restart LOOT.

![LOOT Update Path](/Pictures/sme/loot-update-path.png)

This will update the game path for SME only thanks to [LOOT Config Loader for Mod Organizer](https://www.nexusmods.com/skyrimspecialedition/mods/60864) which created a separate `settings.toml` for SME under `\Mod Organizer 2\Loot Config Files\`. Any global instance of LOOT or installations in different mod setups will be unaffected.

### zEdit

If you want to configure zEdit for SME, follow these steps:

- Run **zEdit** through Mod Organizer 2.
- Click the gears icon to open the settings.

![zEdit Profiles Settings](/Pictures/sme/zedit-profiles-settings.png)

- Create a new profile with **Skyrim SE** as the game.
- Point **Path** at the **Game Root** folder within your SME installation.
- Make sure this profile is selected when using any zEdit module with SME.

![zEdit Profiles Settings](/Pictures/sme/zedit-sme-profile.png)

