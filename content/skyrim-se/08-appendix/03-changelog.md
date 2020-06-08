---
title: "Changelog"
weight: 3
type: docs
description: >
  For all versions since the Github release (3.2 and later).
---


## Release 3.3

I re-added the mod installation instructions that I completely missed in the original website setup. Whoops! It's not like they're important or anything. You can find them [here](https://foreverphoenix.github.io/docs/02-setup/step-10/). It's not a straight copy-paste, I re-structured it and re-wrote parts as well. All "generic instructions" (using CAO, resaving plugins, etc) were moved to the [Basic Instructions](https://foreverphoenix.github.io/docs/07-resources/basic-instructions/) page under Resources.

The Mod Installation section itself was split up into four parts to avoid the ugly scrollbar.

The "Unpack Example.bsa" instructions previously contained instructions to delete the BSA afterwards. Some users missed this step and others got confused so I removed it and added instructions to delete the BSA directly to the mod instructions where appropriate. Should be pretty hard to miss now.

Some mods are now flagged as **(Conditional)**, meaning they are optional but depend on other mods. You must install a **(Conditional)** mod if you installed the mod that it depends on. Otherwise you must skip it.

And finally I added several new mods: **Immersive Sounds Compendium** with DylanJames' new AOS integration patch to the main guide and my favourite new music mods with a merged patch to the Customisation.

#### Setup

- **Step 7:** Removed the zEdit section. zEdit will be re-added to the guide once mator provides ESL support.

#### Mod Installation

- Removed Dwemer Spectres.
- Removed Dwemer Spectres - EBT No Bleeding and Other Fixes.
- Moved Adopt Aventus Aretino from Non-Player Characters (Step 26) to New Mechanics & Features (Step 36).
- **3.9:** Changed download instructions for Realistic Conversation (using a different main file).
- **8.5:** Arctic - Frost Effects Redux is no longer optional (conflict with ISC had to be resolved in the CRP).
- **36.8:** Re-added Irondusk's Saddlebags.
- **37.2:** Added Immersive Sounds - Compendium.
- **37.3:** Added Audio Overhaul - Immersive Sounds Integration.

#### Customisation

- **New Music:** Added this new section with five new music mods and a merged patch.

## Release 3.2.3

Maintenance update.

#### Mod Installation

- **8.1:** Updated download instructions for Frozen Electrocuted Combustion (file update).
- **10.1:** Updated FOMOD instructions for EVT Alternate Branch Textures (file update).
- **37.1:** Updated download instructions for Audio Overhaul for Skyrim, removed instructions to download the EBT Patch (now integrated into the CRP).
- **37.1:** Removed instructions to delete the SKSE folder (no longer preset) and added instructions to delete the modgroups file for Audio Overhaul for Skyrim.

## Release 3.2.3

Maintenance update.

#### Mod Installation

- **8.1:** Updated download instructions for Frozen Electrocuted Combustion (file update).
- **10.1:** Updated FOMOD instructions for EVT Alternate Branch Textures (file update).
- **37.1:** Updated download instructions for Audio Overhaul for Skyrim, removed instructions to download the EBT Patch (now integrated into the CRP).
- **37.1:** Removed instructions to delete the SKSE folder (no longer preset) and added instructions to delete the modgroups file for Audio Overhaul for Skyrim.

## Release 3.2.2

Just a small maintenance update. Realistic Water Two received a big update today, then got hidden to fix oversights. It's back up now. You can probably expect a CRP update soon, but for now here are the updated instructions.

For those who use Arthmoor's additional towns from Customisation, there are now instructions for the Lanterns of Skyrim II patches. I missed them previously.

**Wabbajack users:** Stop pestering Lively about fixing the installer. When mods are updated, he has to update his own setup and recompile, and that takes time. Consider the fact that he has a life that includes more than updating the installer the second a mod update drops. Plus when a mod is hidden, like RW2 was today, there is nothing anyone can do and we all have to wait for the mod author to unhide the mod page. 

#### Mod Installation

- 1.9 Added instructions to delete a textures from the Particle Patch (fixes a bug where water spray would look much darker than intended).
- 9.7 Updated instructions for Realistic Water Two.
- 9.8 Added Realistic Water Two Patch Hub.

#### Customisation

- Added missing Lanterns of Skyrim II patch instructions for Arthmoor's Towns.

#### Load Order TXT

- Added new RealisticWaterTwo - Resources.esm

## Release 3.2.1

This is a small update, fixing some 3.2 oversights as well as bringing the guide up-to-date with the latest mod updates (of which there were several).

Most notably, BethINI and the guide's instructions for it were updated. The process of re-doing BethINI is quite simple and detailed in a new FAQ section, [How to redo INI files from scratch](https://github.com/foreverphoenix/the-phoenix-flavour/blob/master/The-Phoenix-Flavour-3-2/06-FAQ.md#how-to-redo-ini-files-from-scratch).

**Late note:** I forgot to do this earlier, but the Enhanced Vanilla Trees section is all updated now. You will need to regenerate DynDOLOD.

#### Setup

- 2.9 Added section on what to do with 'creations' reinstalled alongside Skyrim SE.
- 6.3 Updated BethINI settings. Added screenshots.

#### Mod Installation

- Fixed some typos and duplicate instructions.
- Incremented version numbers for some updated files.
- Moved Bent Pines to Customisation.
- 1.9 Added a temporary direct link to the Particle Patch while ENB Forums are down.
- 8.1 Updated instructions for Frozen Electrocuted Combustion (file update).
- 8.2 Removed FEC Extra Crispy Burnt Corpses (now obsolete).
- 5.9 Updated instructions for AMB Dragonborn DLC (file update).
- 10.1 Updated the Enhanced Vanilla Trees instructions for the latest version.
- 10.3 Added instructions to remove snowy pine tree bark textures from Tree Bark in High Definition.
- 20.1 Updated instructions for AMB Unique Items (file update).
- 21.21 Added Realistic Skin and Hair Shaders - Falmer and Hagraven.
- 21.22 Added Realistic Skin and Hair Shaders - Giants.
- 29.1 Updated MM Hybrid Loot link (now available on the Nexus).

#### Customisation

- Split the tree tweaks section up into several smaller ones.
- Rewrote Large Trees and Aspen Trees sections for EVT 2.0.
- Removed support for Whiterun - Forest Borealis.
- Moved Bent Pines here.

#### FAQ

- Added How to regenerate INI files from scratch.
- Added Creation Club section.

#### Load Order TXT

- Removed left-over beta files (AMB Patches).
- Moved KarstaagReborn.esp to match mod order.
- Added HagravenSkinShaders.esp (new in 3.2.1).

## Release 3.2

**Disclaimer:** Release 3.2 is fairly substantial so I am bound to have missed some changes and not everything is fully documented. Installing the guide from scratch is required.

- Added many new screenshots and replaced outdated ones.
- Many instructions were similarly added or updated.
- Links now directly lead to the mod page's file section.
- Vanilla artifacts overhauled with a combination of three different mods.
- Fully integrated the highly requested Interesting NPCs.
- Expanded the Customisation section with multiple new categories.
- Removed Cutting Room Floor. It is not worth the gazillion patches it requires.
- Added an automated patcher to fix bugs in the XPMSSE scripts.
- Replaced Container and Levelled List Fixes with our own, custom loot overhaul.
- Major new additions:
  - Adamant - A Perk Overhaul
  - AI Overhaul SSE
  - Morrowloot Miscellania - Hybrid Loot
  - Reliquary of Myth - Artifact Overhaul
  - Interesting NPCs (3DNPC)
  - All Geared Up Derivative

#### Setup

- **3.6:** Split up instructions into two parts.
- **3.6.1:** Changed instructions, we are now unpacking the Vanilla scripts as we will need them later.
- **4.2.1:** Added Mod Order Fix section (correcting DLC mod order).
- **4.2.2:** Added instructions for three small changes in the MO2 settings.
- **4.5.1:** Added instructions to set the Default profile to use vanilla INIs and save games.
- **4.6.1:** Updated instructions for the latest version of Deorder's MO2 plugins.
- **4.6.1:** Re-added instructions to install Deorder's Sync Mod Order plugin since it appears to have been fixed.
- **4.6.2:** Added instructions to change the hide type for Deorder's Hide Merged Plugins.
- **6.3.4:** Removed Shadow Bias INI tweak.
- **6.3.6:** Contrast can now be tweaked in the Visuals tab, instructions were changed accordingly.
- **7.1.3:** Added instructions for the -DontCache argument to fix a bug.
- **8.4:** Added section with instructions to revert the deletion of a navmesh in Update ESM.
- Moved the Mod Installation Instructions to Setup, Step 10.
- Moved "Step 5 - Skyrim Realistic Overhaul" from the Mod Installation section to the Setup as Step 9.

#### Mod Installation

- Removed Havok Fix (replaced with SSE Display Tweaks).
- Removed Cutting Room Floor.
- Removed Multiple Floors Sandboxing (it can be toggled in the NFF MCM).
- Removed Sovngarde - Mist's Font Replacer (it was added to the new Interface Customisation section).
- Removed SkyUI - Flashing Savegame Fix (included in Remove QuickSave Button from SkyUI Systems Menu).
- Removed Extended UI. People constantly missed instructions to delete the BSA plus it seems a little buggy at times.
- Removed Cutting Room Floor - Lighting Overhaul.
- Removed Enhanced Landscapes - Solstheim 3D Trees (moved to the 3D Tree LOD Customisation section)
- Removed MD's Alternate Farmhouse Textures (replaced by newer version).
- Removed Trifle from Hiro - Solitude Gate (moved to Retextures Customisation section).
- Removed Real 3D Walls (doesn't blend well with other retextures).
- Removed Smithing Perk Overhaul (replaced by Adamant).
- Removed Spider Webs and Particles for ENB.
- Removed ElSopa HD - Meridia's Beacon (replaced with Meridia's Luxon Beacon Replacer).
- Removed HD Sabre Cat Tooth Mesh and Texture (included in HD Meshes and Textures for Animal and Creature Drops).
- Removed The Divine Amulets Retexture - Dragonborn Amulets (in favour of RUSTIC AMULETS).
- Removed Better Looking Amulets (in favour of RUSTIC AMULETS).
- Removed ElSopa HD - Akatosh Amulet (in favour of RUSTIC AMULETS).
- Removed ElSopa HD - Bonehawk Amulet (in favour of RUSTIC AMULETS).
- Removed Fangs and Eyes - A Vampire Appearance Mod (replaced with standalone version of the TRI files we need).
- Removed Encounter Zones Reborn (replaced with Arena - An Encounter Zone Overhaul).
- Removed College of Winterhold - Missing Apprentices Fix (requires Cutting Room Floor which was removed).
- Removed Container and Levelled List Fixes - Complete Loot Overhaul.
- Removed Lock Related Loot.
- Removed Helarchen Creek (moved to Customisation).
- Removed Telengard (moved to Customisation).
- Removed Keld-Nar (moved to Customisation).
- Removed Oakwood (moved to Customisation).
- Removed The Fall of Granite Hill (moved to Customisation).
- Removed Immersive Patrols - Plugin Replacer (replaced with Immersive Patrols Simplified).
- Removed Beast Skeletons (Bitter Edition) (replaced with custom replacer plugin).
- Removed AMB Content Addon Fixes (replaced with a scratch-made replacer plugin of our own).
- Removed Cloaks of Skyrim (they just look ugly).
- Removed Cloaks of Skyrim - MLU-Friendly Fixes.
- Removed Cloaks of the Nords.
- Removed Rally's Five Cities Cloaks.
- Removed Morrowloot Miscellania - Ancient Nord Hero Weapons (similar functionality included in Hybrid Loot).
- Moved Step 5 - Skyrim Realistic Overhaul to Setup. Now the separator numbers align with the Steps.
- Moved Quality of Life Improvements below Immersion.
- Moved Reduced Glow FX from Step 7 to Step 8.
- Moved Fire Halo Remover from Step 7 to Step 8.
- Moved Subtle Wind FX from Step 7 to Step 8.
- Moved Ruins Clutter Improved from Step 15 to Step 5.
- Moved Ruins Clutter Improved - Fixes from Step 15 to Step 5.
- Moved Karstaag - The Frost King Reborn from Step 21 to Step 30.
- Moved Bring Meeko To Lod from Step 27 to Step 30.
- Moved Keeper Carcette Survives from Step 27 to Step 30.
- **Step 7:** Renamed from "Lighting & Visual FX" to "Lighting"
- **Step 8:** Renamed from "Combat & Spell FX" to "Visual FX"
- **Step 8:** Updated order of mods to reflect recent changes.
- **Step 9:** Updated order of mods for better overwrite order.
- **Step 10:** Renamed from "Trees & Plants" to "Flora"
- **Step 18:** Renamed from "Clothes & Jewelry" to "Clothes & Jewellery" (because apparently that's the British spelling).
- Swapped Steps 9 and 10 around (now: Step 9 Landscape, Step 10 Flora).
- Removed the entirety of the ENB Particle Lights step (all added to the ENBSeries Customisation section now).
- **1.4:** Added SSE Display Tweaks.
- **1.6:** Updated download instructions for Performance Optimised Textures.
- **2.6:** Updated FOMOD instructions for Skyrim Landscape and Water Fixes.
- **2.7:** Updated FOMOD instructions for Landscape Fixes For Grass Mods - Patches for Arthmoor's Mods.
- **2.8:** Updated download instructions for NARC Remade (file update).
- **2.8:** Added instructions to select The Forgotten City patch in the NARC FOMOD.
- **2.23:** Added Bug Fixes (the mod, by meh321).
- **3.2:** Changed FOMOD instructions for Dwemer Gates Don't Reset (using the Dwemer Only USSEP version now).
- **3.3:** Added Andrealphus' Gameplay Tweaks.
- **3.5:** Added Helgen Keep Bandit Chief Executioner.
- **3.10:** Re-added No NPC Greetings (to replace the previously removed To Your Face which is suspected of causing crashes).
- **3.12:** Added note to Random Encounter Tweaks about which parts of the mod are actually used.
- **3.16:** Updated instructions for Simply Smaller Wolves (removed CRF related instructions, added screenshots).
- **4.3:** Added Remove QuickSave Button from SkyUI Systems Menu.
- **4.5:** Added Favorite Things - Extended Favorites Menu for SkyUI.
- **4.10:** Updated FOMOD instructions for Undiscovered Means Unknown.
- **4.11:** Updated Download Instructions and added Additional Instructions for moreHUD (file update).
- **4.12:** Now downloading the regular (BSA-packed) version of moreHUD Inventory Edition.
- **4.14:** Added my personal preset for A Matter of Time.
- **5.5:** Updated FOMOD instructions for Ruins Clutter Improved (no longer installing two options).
- **5.5:** Removed additional instructions to delete files (no longer necessary).
- **5.8:** Added instructions for the new FOMOD for High Poly Project, and removed now obsolete Additional Instructions.
- **5.9:** Updated FOMOD instructions for aMidianBorn - Dragonborn DLC.
- **5.10:** Updated download instructions for CBBE.
- **7.6:** Changed FOMOD instructions for STAC to use the "Optimized" option for candles and prevent FPS drops.
- **8.1:** Updated download instructions and removed CTD warning for Frozen Electrocuted Combustion.
- **8.3:** Now using the full version of Enhanced Blood Textures.
- **8.13:** Added Glow Be Gone - Updated.
- **9.1:** Updated instructions for Majestic Mountains.
- **9.2:** Updated additional instructions for Cathedral Landscapes (deleting the entire textures\plants folder for Cath Plants).
- **9.3:** Added The Elder Scrolls - Veydosebrom.
- **9.4:** Added Cathedral Landscapes - Veydosebrom Swamp Grass Addon.
- **9.5:** Added Pfuscher's Rapid Rocks.
- **9.6:** Updated FOMOD instructions for Majestic Mountains - Northside (now selecting the Rapid Rocks option).
- **9.7:** Added instructions to Realistic Water Two to delete one mesh that should not be overwriting Rapid Rocks.
- **9.19:** Updated FOMOD instructions for Lanterns of Skyrim II (no longer selecting patches for some removed mods).
- **10.1:** Slightly changed FOMOD instructions for Enhanced Vanilla Trees (now using Lush Trees (small) and SFO Branches v4).
- **10.3:** Added Tree Bark in High Definition.
- **10.8:** Added Cathedral Plants.
- **10.9:** Added Realistic HD Mushrooms Remastered.
- **11.1:** Added MD's Farmhouses.
- **11.6:** Removed CAO processing instructions from RUSTIC MONUMENTS AND TOMBSTONES (optimisation not required).
- **11.7:** Added instructions to download the new, optional Blue Palace Floor file for HQ Solitude.
- **11.7:** Fixed file paths for files to be deleted from HQ Solitude.
- **11.19:** Updated download instructions for Soul Cairn HD (file update).
- **13.13:** Updated FOMOD instructions for Obscure's College of Winterhold and moved them here.
- **14.2:** Added Hall of the Dead - Stained Glass Windows.
- **15.1:** Updated Underground FOMOD instructions (no longer installing the Dwemer textures).
- **15.1:** Added instructions to remove certain files from Underground.
- **15.2:** Added instructions to remove certain files from Rudy HQ - Nordic Ruins.
- **15.3:** Added Ice Cave Parallax Improved.
- **15.11:** Re-added CC's Enhanced Ore Veins - Fixed Iron Ore Cubemap.
- **15.15:** Removed CAO processing instructions from Ancient Dwemer Metal (not actually required).
- **16.16:** Added instructions to merge main and optional files.
- **16.17:** Added instructions to merge main and optional files.
- **16.18:** Added Rally's Werewolf Totems.
- **16.19:** Added Meridia's Luxon Beacon Replacer.
- **17.5:** Added True Homecooked Meal.
- **17.6:** Added HD Meshes and Textures for Animal and Creature Drops.
- **17.7:** Removed instructions to download Hagraven Claw file (included in previous mod).
- **17.8:** Added Improved Dragonfly.
- **18.3:** Updated the FOMOD instructions for Gemling Queen Jewelry (merely updated to use the same logic as all others).
- **18.3:** Added a screenshot to the Additional Instructions section for Gemling Queen Jewelry.
- **18.5:** Added RUSTIC AMULETS.
- **19.2:** No longer installing the AMB Content Addon Patch with Practical Female Armors (will be installed separately later).
- **19.4:** Removed CAO processing instructions from AMB Armors (all processed meshes will be replaced by the SSE Patch).
- **19.4:** AMB Armors is no longer optional.
- **19.6:** Added instructions to remove the empty meshes folder for AMB Weapons.
- **19.8:** Updated FOMOD instructions for LeanWolf's Better-Shaped Weapons (file update).
- **19.13:** Removed instructions to download the Better-Shaped Weapons patch for Frankly HD Imperial Weapons and Armor.
- **19.13:** Added instructions to delete two conflicting meshes from Frankly HD Imperial Weapons and Armor.
- **19.26:** Replaced CAO processing instructions with SSE NIF Optimizer instructions for Dragon Priest Weapons Improved.
- **20.5:** Better Shrouded Armor - Ancient Replacer Only is no longer optional.
- **20.6:** Better Shrouded Armor - Ancient Replacer Only - Plugin Replacer is no longer optional.
- **23.1:** Simplified instructions for Vanilla NPCs Ruhmastered.
- **23.8:** Updated FOMOD instructions for Simple Children - Patches.
- **24.3:** Added Optimised Body Meshes for SkySight Skins.
- **24.10:** Added instructions to delete a normal map from Natural Eyes that overwrote Eye Normal Map Fix.
- **24.14:** Added Just Fangs From BVFE (to replace the full mod we used and butchered for the fang TRIs previously).
- **24.16:** Changed FOMOD instructions for Beards (selecting Vanilla Only instead of Full).
  - The "full" version adds some braided beards that were clearly cut for a reason from the vanilla game. Most of them look strange. One of the braids has some transparency issues.
- **25.2:** Added Adamant - A Perk Overhaul.
- **25.4:** Added Complete Crafting Overhaul Remastered - JS Circlet Replacer Patch.
- **26.1:** Added AI Overhaul.
- **26.2:** Added AI Overhaul - Windsong Immersive Character Overhaul Patch.
- **26.3:** Added AI Overhaul - Ethereal Elven Overhaul Patch.
- **26.4:** Updated instructions for Relationship Dialogue Overhaul (CRF Patch is no longer needed).
- **26.6:** The Autorun.txt is located in the Text Files tab, not the INI Files tab (fixed typo).
- **26.6:** Fixed customisation instructions (console command syntax) for Guard Dialogue Overhaul.
- **26.9:** Added Hunters Not Bandits.
- **26.10:** Added Thugs Not Assassins.
- **26.10:** Updated FOMOD instructions for Nether's Follower Framework (now selecting the Interesting NPCs Patch).
- **27.2:** Updated FOMOD instructions for Even Better Quest Objectives (selecting the BCS Patch, skipping CRF Patch).
- **27.5:** Added Save the Icerunner - Lights Out Alternate Routes.
- **27.15:** Updated FOMOD instructions for Finding Velehk Sain (no selecting College Apprentices Fix option).
- **28.3:** Added Arena - An Encounter Zone Overhaul.
- **29.1:** Added Morrowloot Miscellania - Hybrid Loot.
- **29.3:** Added Morrowloot Miscellania - Dremora Bound Weapons.
- **29.10:** Added Reliquary of Myth - Artifact Overhaul
- **29.11:** Re-added Zim's Artifacts (not using all modules).
- **29.12:** Added Unique Items Tweaks - Improved Less Known Artifacts.
- **31.4:** Added Bounty Preview.
- **31.10:** Added additional instructions to Copy and Paste in Console.
- **33.3:** Added Interesting NPCs.
- **33.3:** Added Interesting NPCs - Zora Fair-Child Voice Enhanced.
- **33.4:** Added Cuyima - Interesting NPCs.
- **33.6:** Added missing FOMOD instructions for Immersive College NPCs.
- **33.8:** Added Morrowloot Ultimate - INIGO Patch.
- **34.1:** Updated download instructions for Immersive Patrols (now using the new Lite version without warzones).
- **34.2:** Added Immersive Patrols Simplified.
- **34.4:** Added numbers to the overview picture for the DWC Player Werewolf Replacer FOMOD.
- **34.10:** Added Beast Skeletons - Plugin Replacer.
- **35.4:** Updated AMB Content Addon (LE version) instructions.
- **35.5:** Added aMidianBorn Content Addon - SSE Port.
- **35.6:** Added Practical Female Armors - aMidianBorn Content Addon as a separate file.
- **36.6:** Added Choose Your Own Arch-Mage.
- **37.1:** Added instructions to download the Enhanced Blood Textures patch for Audio Overhaul Skyrim.
- **38.1:** ENB Light is no longer optional.
- **38.2:** Removed AOS+ENB Light+Mysticism patch (conflicts are resolved in the guide's CRP now).
- **39.3:** Added XPMSSE Fixes - Automated Patcher.
- **39.4:** Added All Geared Up Derivative - AllGUD.

#### Finalisation

- Moved FNIS instructions to Step 2.
- Added Step 3 for All Geared Up Derivative.
- Split the ENBSeries setup instructions into two steps (4 and 5).
- Expanded Step 7 a little (the ingame testing section).
- Clarified instructions in Step 4 (mod order and waiting for scripts to finish before closing xEdit).
- **1.1:** Moved FOMOD instructions for Obscure's College of Winterhold to the mod's instructions.
- **1.1:** Expanded and updated FOMOD instructions for Misc College of Winterhold Tweaks.
- **1.5.2:** Updated and expanded list of plugins that should be ESL-ified.
- **5.4:** Added installation instructions for the performance-friendly The Truth ENB preset.
- **6.3:** Removed change to texture compression in TexGen.
- **6.4:** Clarified instructions on where to place TexGen Output in the mod order.
- **6.6:** Users now need to choose between the three profiles in DynDOLOD. Updated the screenshot.
- **6.7:** Updated recommendations to rename the Output mod folder.

#### Customisation

- Basically re-did this section and expanded it at least with WIP directories.
- Updated list of of rougeshot's skeleton replacers.
- Added several new Interface related sections.
- Added Tree Tweaks section.
- Added Arthmoor's New Towns section.

#### New Game

- Split up instructions.
- Moved ENB Shader Cache instructions to Step 1.
- Instructions to turn down the DOF slider ingame were moved to the Finalisation.
- Add / updated MCM recommendations for multiple mods:
  - All Geared Up Derivative
  - Complete Crafting Overhaul Remastered
  - moreHUD
  - Realistic Water Two
  - Relationship Dialogue Overhaul
- Added more screenshots.
- Removed recommended change for the Lanterns of Skyrim II MCM.
  - We previously changed the script to check only every 60s instead of every 5s whether the lanterns are on and what time of day it is but with the Always On option, the script shouldn't check in the first place (since lanterns aren't disabled during the day.)
