# UnitCrunch-data-exports
A collection repository of Warhammer 40k factions. These .txt files are Data Exports that can be imported into the popular web application UnitCrunch.

Below are some related links.
* https://www.unitcrunch.com/
* https://www.reddit.com/r/UnitCrunch/
* https://github.com/dixhuit/unitcrunch-issue-tracker

## :loudspeaker: Latest Changes

* **Astra Militarum**, **Space Marines**, **Drukhari** & **Chaos Daemons** Updated to be compatible with **Advanced Profiles** and includes the latest Dataslate changes.

## General Information
The Factions folder has a directory for each 40k Faction that we have a Data Export for, new Factions will be added over time.

Each Faction contains the following:
* `.txt` The Latest Data Export (import file for UnitCrunch)
* `Changlog.md` record of changes
* `readme.md` Information about the upload file(s)
* `/Patch` Folder that includes patches.

Once you have imported the Data Export the profiles will need to be configured by yourself. This will generally just be changing the `Model count` and the weapons `Count per unit`, but some profiles will need more configuration this is usually documented in the `readme.md` of that faction.

UnitCrunch's latest update v0.64 has introduced **Advanced Profiles**, this will now allow you to create mixed profiles. Refer to our guide on how to mix profiles - [Mixing_Profiles.md](/Guides/Mixing_Profiles.md).

Current list of Faction Data Exports that have been updated for use with **Advanced Profiles**:
* **Adeptus Mechanicus**
* **Aeldari**
* **Astra Militarum**
* **Chaos Daemons**
* **Drukhari**
* **Space Marines**
* **T'au Empire**

If you wish to update your existing Data Export take a look at that Factions Patches Folder and read the [Patches.md](/Guides/Patches.md) guide on how to import them.

> [!NOTE]
> There will be no Patches for just point changes.

## Contributing
If you wish to contribute please read the `contributing.md`, here we outline the file structure and formatting that can streamline creating the `readme.md`.
There are also quick start templates in the `Templates` directory.

## :clipboard: Todo list
- [ ] Update Existing Factions to be compatible with Advanced Profiles
- [ ] Dataslate Changes & MFM
- [ ] Genestealers Cults Codex Changes