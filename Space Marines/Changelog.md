# Space Marine Index
## Update v1.0
###### 25/07/2023
***NOTE: Some of the descriptions below could be inaccurate as this took a while to create and Unitcrunch has had updates since.***
### General
* Have not included any Forgeworld, Legends, Epic Heroes or faction specific units such as `Ultramarines`.
* All unit profiles have 2 abilities representing the army rule **`Oath of Moment`**:
    * Re-roll all possible failed hit rolls (if attacker)
    * Re-roll all possible failed wound rolls (if attacker)
* **`Leaders`** are all separate unit profiles acting as if they were a sole unit on the battlefield and thus, they do not include there **`Leader`** ability.
* All unit profile weapons have the default maximum count per unit.
* All units that have the **`Damaged: 1-X Wounds Remaining`** have a -1 to hit roll ability in their unit profile that can be turned on/off.
* All unit profiles have the weapons shown on their datasheet. If they have access to more weapons via the armoury these are generally not included if there is more than 1/2 as that would reach Unitcrunches 15 weapon limit.

This index is split into 3 categories:
1. HQ
1. Infantry/Mounted
1. Vehicles

### HQ
* **Captain, Primaris Captain:**
    * To simulate `Finest Hour` enable the two unit abilities `Critical wound` & `3 extra attacks`
    * Wounds characteristic needs to be changed to 6 if using the `Relic shield` wargear.

* **Captain (bike):** Wounds characteristic needs to be changed to 7 if using the `Relic shield` wargear.

* **Captain (Jump pack):** Wounds characteristic needs to be changed to 6 if using the `Relic shield` wargear.

* **Captain in Terminator Armour:** Wounds characteristic needs to be changed to 7 if using the `Relic shield` wargear.

* **Lieutenant:** Enable `4++ Invuln save` to simulate the wargear `Storm Shield`.

* **Chaplain on Bike:** Enable the unit ability DEVASTATING WOUNDS to simulate the `Catechism of Fire` ability.

* **Chaplain (Jump Pack):** `Exhortation of Rage` ability is a melee weapon on the unit profile, when using disable all reroll modifiers.

* **Techmarine:** Added the Storm bolter weapon.

* **Lieutenant with combi-weapon:** `Paired combat blades` excludes the `[ANTI-TYRANIDS 4+]` weapon ability, to simulate this add one of the `[ANTI-X 4+]` weapon abilities to that weapon and add the same keyword to the defending unit.

* **Primaris Company Champion:** `Martial Superiority` ability is included in the `Master-crafted power weapon` weapon profile.

* **Primaris Ancient:** Enable the unit ability `Feel no pain 4+` to simulate the `Unbreakable Duty` ability.

* **Bladeguard Ancient:** Enable the unit ability `1 extra attack` to simulate the `Deeds of Heroism` ability.

* **Ancient (Terminator):** `Terminator Storm shield` wounds characteristic of 6 needs to be added if using that wargear.

* **Judiciar:** Adjust the `Extra attacks #` unit ability to simulate the `Silent Fury` ability. Wounds characteristic needs to be changed to 6 if using the `Relic shield` wargear.

### Infantry/Mounted
* **Assault intercessor squad:**
    * The Ability `Shock Assault` is split into two unit abilities.
    * Enable the `Re-roll all possible failed wound rolls (melee only)` ability to simulate whether the target is within range of an objective marker.

* **Incursor squad:** Oath of the moment has been removed from this unit profiles abilities and placed onto cloned weapon profiles, this is so the `Haywire Mine` ability could be implemented as a weapon on this profile.

* **Bladeguard veteran squad:** Cannot implement the `Shields of the Imperium` ability as Unitcrunch cannot allow re-rolls on saving throws.

* **Command squad:** *This profile will need to be heavily adjusted to represent your unit!*
    * The Astartes shield wargear is present as a `4++ inv` ability but only 3 units can take this item, in your simulations after 3 models have been slain the accuracy drops and results after that will be inaccurate.

* **Terminator assault squad:** `Stormshield` wargear ability to increase wounds will have to be added manually.

* **Terminator squad, Relic Terminator squad:**
    * Not implemented the `ignore any or all modifiers to that attack’s Ballistic Skill or Weapon Skill characteristic and/or to the Hit roll.` part of the `Fury of the First` ability.
    * Have Implemented the part where this unit gets +1 to hit rolls if oath of the moment is the target, this ability can be turned on/off.

* **Centurion Devastator squad:**
    * The Ability `Decimator Protocols` is split into two unit abilities.
    * Enable the `Re-roll all possible failed hit rolls (ranged only)` ability to simulate whether the target is within range of an objective marker.

* **Assault Squad** *This profile will need to be heavily adjusted to represent your unit!*
    * The Astartes shield wargear is present as an `4++ inv` ability but only 1 unit can take this item, in your simulations after 1 model has been slain the accuracy drops and results after that will be inaccurate.
    * To apply the ability `Chainsword Doctrines` just add the weapon ability you want to your Astartes Chainsword.

* **Assault Squad (Jump Packs)** *This profile will need to be heavily adjusted to represent your unit!*
    * The Astartes shield wargear is present as an `4++ inv` ability but only 1 unit can take this item, in your simulations after 1 model has been slain the accuracy drops and results after that will be inaccurate.
    * The ability `Hammer of Wrath` has been added as a weapon, to simulate this ability you'll have to disable the re-roll hits unit ability on this profile and change the weapon count per unit to the desired squad size.

* **Outriders Squad:** Excluded `Invader ATV` and the weapons `Multi-melta` & `Onslaught cannon` from this unit as it has it's own profile.

* **Bike Squad:** Excluded `Attack Bike` and the weapons `Multi-melta` & `Heavy bolter` from this unit as it has it's own profile.

* **Eradicator Squad:**
    * The ability `Total Obliteration` is present as 3 unit abilities.
    * Change the `Re-roll all damage results of #-#` to the range you would like to simulate.

* **Desolation Squad:**
    * Due to this unit mostly using `[INDIRECT FIRE]` weapons a `-1 to hit roll` unit ability has been added which can be enabled/disabled when simulating those specific weapons, be sure to add a +1 save roll to the defending unit as well.
    * Disable the `-1 to hit roll` unit ability when simulating the `Targeter Optics` ability, you will also have to add [IGNORES COVER] to the weapons you want to simulate `Targeter Optics` with.

* **Devastator Squad:** 
    * Could not add the ability `Signum` as there is no effect for `[IGNORES COVER]` when choosing `remained stationary` as a condition.  
    * To simulate the `Armorium Cherub` ability; choose the desired weapon and click edit then from the preset abilities dropbox add the `Re-roll one possible failed hit roll`.
    
### Vehicles
* **Ironclad dreadnought:** `Siege-breaker protocols` Cannot include keyword Fortification.
* **Hunter:** The ability `Hunter Missile Targeting` has been included as a weapon ability on the `skyspear missile launcher`.
* **Gladiator Lancer:** Cannot simulate the ability `Aquilon Optics` these modifiers will have to be applied to the specific attack of your choosing.
* **Gladiator Reaper:** The ability `Rotating Death` has been included as a weapon ability on the `Twin heavy onslaught gatling cannon`.
* **Gladiator Valiant:** The ability `Ferocious Assault` has been included as a weapon ability on the `Twin las-talon`, this ability assumes you're attacking the closest eligible enemy unit so it will have to be deleted if you did not want to simulate that.
* **Vindicator:** Not included the `Siege Shield` ability.
* **Repulsor Executioner:** The `Executioner` ability is present in the unit abilities, as there's no condition for Below Half-strength this can be turned on/off to simulate that.
