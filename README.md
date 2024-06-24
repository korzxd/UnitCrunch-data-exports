# UnitCrunch-data-exports
A collection repository of Warhammer 40k factions. These .txt files are Data Exports that can be imported into the popular web application UnitCrunch.

Below are some related links.
* https://www.unitcrunch.com/
* https://www.reddit.com/r/UnitCrunch/
* https://github.com/dixhuit/unitcrunch-issue-tracker

## General Information
Each directory contains the following:
* `.txt` The Latest Data Export (import file for UnitCrunch)
* `Changlog.md` record of changes
* `readme.md` Information about the upload file(s)
* `/Patch` Folder that includes patches.

Once you have imported the Data Export the profiles will need to be configured by yourself. This will generally just be changing the `Model count` and the weapons `Count per unit`, but some profiles will need more configuration this is usually documented in the `readme.md` of that faction.

## Contributing
If you wish to contribute please read the `contributing.md`, here we outline the file structure and formatting that can streamline creating the `readme.md`.
There are also quick start templates in the `Templates` directory.

## :loudspeaker: Latest Changes
* The following Data Exports have been modified to include the `PSYCHIC` keyword:
    * Aeldari
    * Agents of the Imperium
    * Astra Militarum
    * Genestealer Cult
    * Space Marines
    * Blood angels

* Data Exports have been renamed to follow the same naming convention.

* **Patches have been introduced!** <br> Each Faction Directory will now include it's own Patch folder. In that folder there will be `patch-#.txt` files and a `Readme.md` detailing which patch is compatible with each Data Export and what has changed in that Patch. This should prevent current users that have modified there Data Export from overwriting the whole thing.

## :clipboard: Todo list
- [ ] Next Faction: Adeptus Mechanicus
- [ ] Dataslate Changes & MFM
- [ ] Genestealers Cults Codex Changes