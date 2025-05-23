# UnitCrunch-data-exports
A collection repository of Warhammer 40k factions. These .txt files are Data Exports that can be imported into the popular web application UnitCrunch.

If you need any help interacting with the repository and UnitCrunch we have a basic [User Guide which you can find here.](/Guides/User_Guide.md)

Below are some related links.
* https://www.unitcrunch.com/
* https://www.reddit.com/r/UnitCrunch/
* https://github.com/dixhuit/unitcrunch-issue-tracker

## :loudspeaker: Latest Changes
* Updated all of the Data exports to be exported from version 0.72.1 of UnitCrunch, this should now fix any import issues.
* Due to the update all of the latest releases have been cleared. You can find each factions Data Export within their sub folder.

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
* **Adeptus Custodes**
* **Aeldari**
* **Astra Militarum**
* **Chaos Daemons**
* **Drukhari**
* **Genestealer Cults**
* **Orks**
* **Space Marines**
  * **Blood Angels**
* **T'au Empire**

If you wish to update your existing Data Export take a look at that Factions Patches Folder and read the [Patches.md](/Guides/Patches.md) guide on how to import them.

> [!NOTE]
> There will be no Patches for just point changes.

## Contributing
If you wish to contribute please read the `contributing.md`, here we outline the file structure and formatting that can streamline creating the `readme.md`.
There are also quick start templates in the `Templates` directory.

## :clipboard: Todo list
- [ ] Next Faction - Leagues of Votann
- [ ] Update existing factions to match latest codex releases & dataslate
- [ ] Update **Imperial Agents** with the new Codex changes and to become compatible with **Advanced Profiles**