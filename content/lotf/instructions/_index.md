---
title: "Installation"
weight: 2
type: docs
description: >
  Installation guide for Legends of the Frost.
---

## Requirements

- [Skyrim Special Edition](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/) on Steam.
- Latest version of Windows 10 (required by Wabbajack).
- At least a free [Nexus Mods](https://www.nexusmods.com/) account, Premium is recommended.
- Latest drivers for your GPU ([NVIDIA](https://www.nvidia.de/Download/index.aspx) or [AMD](https://www.amd.com/en/support)).

> A Nexus Premium subscription is highly recommended for a significantly faster and easier installation. Without Premium, you will need to click download for every mod while Premium allows Wabbajack to automatically download everything for you.

### Disk Space

**Legends of the Frost** currently requires **~53GB** of free disk space for the list installation and another **~30GB** for the downloaded archives. It is recommended to install LOTF on an **SSD**.

The initial installation process will be faster if the downloaded archives are also on an SSD. They can be moved to a different drive afterwards as they are not necessary for gameplay, only for updating the list. If you delete them, you will have to redownload them if you want to update LOTF so it's recommended to keep them.

### Visual C++ Redist

The Microsoft Visual C++ Redistributable is a basic package required by Mod Organizer 2. You probably already have it installed with Windows but it is best to make sure.

- Open the official [Microsoft Visual C++ website](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0).
- Scroll to the **Visual Studio 2015, 2017 and 2019** section.
- Download the following file: `vc_redist.x64.exe`.
- Run the executable, it will guide you through the installation process.

![VC Redist](/Pictures/tpf/initial-setup/vc-redists.png)

## Skyrim SE Setup

Before you can install LOTF, you need to make you are on the correct version of Skyrim SE and that your installation is set to English.

### Set language to English

**LOTF requires the English language version of Skyrim SE.**

If you are currently playing in a language other than English, please go into the settings for Skyrim SE in your Steam library and revert the language to English. After changing the language, Steam should automatically download the required files (launch the game to force the download if it doesn't).

### Revert to pre-AE Skyrim

**LOTF does not currently support Skyrim Anniversary Edition.**

If you downloaded or updated Skyrim SE after 11/11/2021, you are on version **1.6.318.0** which will not work with LOTF, regardless of whether you own the Anniversary Edition DLC or not. You need to downgrade your installation to **1.5.97.0** before you can proceed.

- Download halgari's [Unofficial Skyrim Special Edition Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618) from the Nexus (**Full Patcher**).
- Extract the contents of the archive to a convenient location and run **Patcher.exe**.
- It should find your Skyrim SE folder automatically and display the file path.
- Click the green **Start Patching** button and wait for the process to complete.
- When the tool returns `Finished Patching, enjoy your game!`, you can close it and proceed.

![Skyrim SE Version Downgrade](/Pictures/lotf/installation/skyrim-se-downgrade.png)

## Wabbajack Installation

Next up you need to install the Wabbajack tool itself:

- Download [Wabbajack](https://www.wabbajack.org/#/) from the official website.
- Extract the archive to a high-level folder, e.g. `C:\Wabbajack\`.

**Do not install Wabbajack into UAC protected directories.** These include Program Files and Program Files x86 as well as the Downloads, Desktop, Documents, etc, folders.

Double-click **Wabbajack.exe** to launch to tool. It will automatically update itself to the latest version.

### Legends of the Frost

You can now install LOTF through Wabbajack:

- Click the **Browse Modlists** button in the Wabbajack tool.
- Find **Legends of the Frost** in the gallery of mod lists and click the arrow button to download the installation file.

![LOTF on WJ](/Pictures/lotf/installation/lotf-on-wj.png)

In the installation window, you will need to define two folders:

**Installation Location** is where LOTF will be installed to. Choose a high-level folder such as `C:\Legends of the Frost\` that is outside UAC protected folders (Program Files, Documents, etc).

**Download Loaction** is where the downloaded mod archives will be stored. By default, they will be placed within your main LOTF folder, but you can change the file path if you want to keep the files elsewhere.

Once both folder locations have been set, click the button on the right to begin the installation process.

![LOTF Installation WJ](/Pictures/lotf/installation/lotf-installation-wj.png)

### Installation Process

If you have **Nexus Premium**, this is all you have to do. Lean back and relax while Wabbajack downloads and installs LOTF for you.

If you only have a free Nexus account, Wabbajack will open the mod pages for you and guide you through the process of downloading all files. Afterwards, it will proceed with the installation as usual.

You can follow along as Wabbajack installs the list. It will display previews with summaries and links to the mods being installed. Don't let the log irritate you. Unless the installation is aborted completely, you don't have to worry about any warnings.

**In case the installation does fail:** Try restarting Wabbajack first. You will not lose progress as the tool will pick up where it left of. Should the installation fail again, please join us on [Discord](https://discord.gg/xCPxJFbCTS), grab the `@LOTF` role, and post your `wabbajack.current.log` in the `#lotf-support` channel. You can find all Wabbajack logs in your Wabbajack installation folder under `\Wabbajack\logs\`.

In most cases the installation should complete successfully on the first try. The tool will let you know when it has.

## Playing LOTF

Navigate to your **Legends of the Frost** folder and launch the **ModOrganizer.exe** within. In the top right drop-down menu **SKSE** should already be selected and you can now launch the game by clicking **Run**.

> Legends of the Frost uses the **Stock Game Folder** system. There are no Game Folder Files to move manually.

![Play LOTF](/Pictures/lotf/installation/launch-lotf.png)

### MCM Instructions

LOTF only has a handful of Mod Configuration Menus (MCMs), most of which you should not need to touch. The only one you may wish to customise is **Immersive HUD** (change the hotkey, or adjust the transparency of various HUD elements) which can be done anytime. The LOTF preset for the moreHUD MCM is applied automatically upon starting a new game.

There are some small tweaks and optional mods in LOTF. Find out more on the [Customisation](/lotf/customisation) page.

### ENB Hotkeys

The hotkeys to toggle ENB on/off, open the GUI, or display the FPS meter are the same as in TPF and WTP:

- **F7** toggles the FPS counter.
- **F10** toggles the ENB effect.
- **F11** opens the ingame GUI.

All other functions (screenshot, FPS cap, toggle DOF) were disabled. I recommend taking screenshots with Steam by pressing F12.