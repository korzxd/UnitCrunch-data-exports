# User Guide

This guide will introduce the basics to using this repository with [UnitCrunch](https://www.unitcrunch.com/)

# Downloading the files
1. [Follow this link to the releases section.](https://github.com/korzxd/UnitCrunch-data-exports/releases)
2. Find the faction release you wish to use, in that section you'll see 3 downloadable files:
   * `Readme.md`
   * `Changelog.md`
   * `.txt` file with the faction name and version number.
3. The `.txt` file is the import file that contains all of that factions units, this is the file you need to download. Click the file to start the download.
4. If using a Space Marine chapter such as the Blood Angels you will have to download the Space Marines `.txt` file aswell.
5. Find the faction you wish to simulate against and repeat **steps 1-3** to download the `.txt` file.

# Importing the files

1. Now that you have all the files you wish to import go to UnitCrunch - [https://www.unitcrunch.com/](https://www.unitcrunch.com/)
2. Click `Manage Profiles` in the top right corner.
3. \**Optional*\* Select all of the demo profiles and delete those before importing.
4. Click `Import`
5. Click `Select File`
6. Browse and select the file you downloaded.
7. Tick `Add to Existing data`
8. `skip duplicates` should be ticked by default but make sure it's ticked.
9. Click `Import`
10. Repeat **steps 4-9** until all of the .txt files have been imported.

# Using the simulator

1. Click `Crunch` in the top right corner.
2. In the `Attacker` & `Defender` sections you'll see an area titled `Input:` with 2 buttons `Ad hoc` and `profile`. Click the `profile` button.
3. In the `Attacker` section you'll now have a new area below `Input:` that says `Attack type:` with 2 buttons `Melee` and `Ranged`. Use these buttons as a filter to switch between melee/ranged weapons.
4. In the `Attacker` section click `Saved Profiles`. This will list all of the profiles that you imported.
5. Select the profile you wish to simulate as the Attacker. Note: Profiles that **do not** have any ranged weapons will not appear if you set the attack type to `Ranged` in **Step 3**.
6. Repeat **step 4** for the Defending profile.

Now that you have 2 Profiles loaded as Attacker and Defender you can enable/disable different weapons and abilities.

# Adjusting weapon counts

The Profiles supplied are set to the maximum wargear choices requiring you to edit some of the profiles weapon counts. You can do this by clicking `edit profile` then click the edit symbol next to the weapon and you'll change the value in the `Count per unit` Inputbox.

# Adding army rules

Below the Defender section you'll see a `Global Modifiers` section. This is where I suggest you place Army Rules, Detachment Rules & other various buffs such as stratagems or auras etc.

Every factions Release contains a **[Readme.md](/Factions/Space%20Marines/)** file that lists the modifiers you should use for which abilities. You`ll be best browsing these through the online repository, just follow the breadcrumbs back to the Factions directory and then click on the faction to view the Readme file. Space Marine Chapters are located in the Space Marines Directory.

Most of these buffs are already listed as presets that can be accessed by clicking the `Preset Modifiers` button. If you cannot find them you'll have to create them yourself. Then you will be able to toggle these Global Modifiers on/off.

# Additional guides

For more advanced guides refer to the list below.
* [Mixing Profiles](/Guides/Mixing_Profiles.md)
* [Patches](/Guides/Patches.md)