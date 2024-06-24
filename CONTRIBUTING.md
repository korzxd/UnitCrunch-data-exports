# Contribution Guidelines

## How you can help

* Submit Pull Requests for a new faction.
* Submit Issues or Pull Requests related to incorrect information, improvements, typos etc.. within the Data Export `.txt` file or the `readme.md` for that faction.

## File Structure

Folder structure and naming conventions for a faction.

    .
    ├── ...
    ├── faction name                            # Root folder for the faction, must be the full name.
    │   ├── *faction-name*-v*#*.txt             # Faction name & version. (This can be an abbreviation)
    │   ├── *faction-name*-Legends-v*#*.txt     # Legends file & version. (Optional)
    │   ├── readme.md                           # Contains information about the Data Export.
    │   ├── changelog.md                        # A recorded history of changes. (Does not have to be thorough)
    │   └── Patches                             # Folder containing the patches for previous versions.
    │       ├── readme.md                       # History and Details of Patches.
    │       └── *faction-name*-Patch-*#*.txt    # Faction name & Patch number.  
    └── ...

Space Marine Chapters will follow the same structure as above but they will be placed in the Space Marines directory rather than the Root.


## Readme Structure
Below is a guideline on how this file should be structured. More information about each section can be found below this example. <br> *The Brackets [] represent where you should write the information.*

A **Template** `Readme.md` can be found in the **Templates folder** for a quick start. 

```
# [faction name] v[#]                               # Faction Name & version
## General Information                              # General info Section
* [info item 1]                                     # General info list

## Army Rules                                       # Army Rules Section
* **`[rule name]:`** <br> [description]             # Rule name & description

## Detachment: [detachment name]                    # Detachment Section
### Rule                                            
* **`[rule name]:`** [desc]                         # Rule name & description
### Stratagems
* **`[stratagem name]:`** [desc]                    # Stratagem name & description
### Enhancements
* **`[enhancement name]:`** [desc]                  # Enhancement name & description

## Units - Standard                                 # Units Section
* #### [unit name]:                                 # Unit Name
    * **`[ability name]:`** *[type]* <br> [desc]    # Ability name, type & description

## Units - Legends                                  # Subcategory headers (Forgeworld, Legends etc..)
```


> [!NOTE]
> When replacing [desc] with a description, this should only describe how to interact with UnitCrunch and is not an actual written description of the ability. Refer to the [Snippets](#readme-snippets) section below or the other factions `Readme.md`.


### Formatting
Outlined below are the formatting requirements. <br> `x` represents the value.

| **Type** <br> _________________________ | **Markdown** <br> _________________________ | **Description** <br> _________________________ |
|---|---|---|
| Section headings | `## x` | Header for a new section: General, Units, Army, Detachment. |
| Section sub headings | `### x` | Header for sub sections: Detachment Rules, Enhancements, Stratagems. |
| Unit | `* #### x` | Listing a new unit under the Units Section. |
| Ability, Weapon, Wargear | ```  * **`x:`**``` | Listing a new Weapon/Ability/Wargear for a Unit, Army Rule, Detachment Rule, Stratagem, Enhancement. |
| Type | `*x*` | Followed directly after the above scenario we display the type of new list item: Weapon, Ability, Wargear. (only applies to units) |
| Reference | ``` `x` ``` | In description areas this is used when referencing weapons, units, files, UnitCrunch effects. |
| Important | `**x**` | Used for Characteristic values such as Wounds, Attacks, BS etc.. Also used when referencing **Global Modifiers**. |

### General Information Section
This bulleted list of items for the General Information are mostly generic and are shared across multiple Units, this information will provide an explanation of what to expect when using the Data Export.
Below is a list of things that could be mentioned, written examples of these can be found in the **Template** `Readme.md`
* Outline which units are included/excluded.
* Specify the role of leaders.
* Specify squad composition. (Max/Mixed squad sizes, Weapons have Default Count per unit etc..)
* Inclusion of whether shared abilities such as `Damaged` on Vehicle/Monster profiles are a profile ability or to use **Global Modifiers**.

### Army Rules Section
* Detail all of the relevant Army rules that can be implemented, it's best to try and include these in the **Global Modifiers**.

### Detachment Section
* Detail each detachment with their detachment rule and how it can be implemented into UnitCrunch, similar approach to the Army Rules.
* ***Optional!*** Add details on how to implement stratagems and enhancement rules. (This is a big job for factions that have multiple detachments and is not required by any means.)

### Units Section
This area will outline the unit profiles that need an explanation on how to interface with it. UnitCrunch is capable of creating most of the conditional situations but below are some examples that will need a description:
* Abilities that target the closest eligible unit.
* Abilities that target a unit that is below half strength.
* Abilities that target a unit that is within range of an objective marker.

UnitCrunch can simulate most of the passive abilities like those that target a specific Keyword or if a unit charged, these abilities can be left enabled and does not need to be documented.

Each unit profile will be listed with a h4 tag followed by an indented bullet point list of each ability. The abilities will need to have a name, the type of ability (ability, wargear, leader ability) followed by a line break `<br>` and then a description.
Below we show an example of the Space Marine Captain and their list of abilities along with the markdown.

* #### Captain:
  * **`Finest Hour:`** *Ability* <br> Enable the profile abilities `Critical wound : disable save` & `Increase attacks by 3`.
  * **`Relic Shield:`** *Wargear* <br> Change Wounds to **6**.

```
* #### Captain:
  * **`Finest Hour:`** *Ability* <br> Enable the profile abilities `Critical wound : disable save` & `Increase attacks by 3`.
  * **`Relic Shield:`** *Wargear* <br> Change Wounds to **6**.
```

For simplicity it's best to split the Legends away from the playable units and these should be placed under a separate header.

### Readme Snippets
Below is a list of snippets to quickly add into the `readme.md`.

*This area will be updated with more in the future. You can always refer to the other factions `Readme.md` for more examples.*

#### Standard Profile Ability
* Add a Profile Ability that needs to be toggled. <br> Replace the following: <br>
***'_name'*** with the ability name. <br> 
***'_type'*** with the type of ability: Ability/Leader Ability/Wargear. <br> 
***'_ref'*** with the UnitCrunch Description/Alias for that profile ability. <br> 
```
  * **`_name:`** *_type* <br> Enable the profile ability `_ref`.
```

#### Ability that affects a specific Weapon
* Add the ability to the weapon. <br> Replace the following: <br>
  ***'_name'*** with the ability name. <br> 
  ***'_ref'*** with the weapon name. <br> 
```
  * **`_name:`** *Ability* <br> Modifier already applied to the `_ref`.
```

#### Wargear that changes Wounds
* Replace the following: <br>
  ***'_name'*** with the wargear name. <br> 
  ***'_val'*** with the wounds characteristic. <br> 
```
  * **`_name_:`** *Wargear* <br> Change Wounds to **_val**.
```

#### Indirect Fire Weapon
* Create a duplicate weapon with a `-1 to hit roll` modifier. <br>
  Replace ***'_name'*** with the weapon name.
```
  * **`_name - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `_name` to simulate `INDIRECT FIRE`. (Enable `Defender in Cover` from **Global Modifiers**.)
```

## Changelog Structure
The Changelog structure is standard enough to follow, each update will need an update version and date then the list of changes. This does not have to be detailed, listing the unit's that are new/changed/removed is all that's needed.

A **Template** `Changelog.md` can be found in the **Templates folder** for a quick start. 