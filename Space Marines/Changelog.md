# Space Marine Index
## Update v1.1
###### 19/09/2023
### General
* Updated Point values of all units to match the Munitorum Field Manual v1.3.

* Added the Index Cards v1.2 Changes.

* Removed the profile abilities `Re-roll all possible failed hit rolls (if attacker)` & `Re-roll all possible failed wound rolls (if attacker)` from all profiles. Add these to the Global Modifiers to simulate the Army Rule `Oath of Moment`.

* The following units have had the `-1 to hit roll (if defender)` ability changed to `-1 to hit roll (if attacker)` this now actually simulates the `Damaged: 1-# Wounds Remaining` ability:
    * **Invictor Tactical Warsuit**
    * **Redemptor Dreadnought**
    * **Brutalis Dreadnought**
    * **Ballistus Dreadnought**
    * **Hunter**
    * **Stalker**
    * **Whirlwind**
    * **Predator Destructor**
    * **Gladiator Lancer**
    * **Gladiator Reaper**
    * **Gladiator Valiant**
    * **Vindicator**
    * **Land Raider**
    * **Land Raider Crusader**
    * **Land Raider Redeemer**
    * **Repulsor**
    * **Repulsor Executioner**
    * **Storm Raven Gunship**

### New Unit Profiles

* **Hammerfall Bunker:** Located within the SM-Vehicles file.

### HQ Changes
* **Captain, Primaris Captain:** Changed `3 extra attacks` profile ability to `Increase attacks by 3`.
* **Primaris Techmarine:** Added the weapon profile `Omnissian power axe (Vengeance of the Omnissiah)`. Use this profile to simulate the `Vengeance of the Omnissiah` ability.
* **Techmarine:**
  * Removed `Combi-weapon` to make room for `Omnissian power axe (Vengeance of the Omnissiah)`.
  * Added the weapon profile `Omnissian power axe (Vengeance of the Omnissiah)`. Use this profile to simulate the `Vengeance of the Omnissiah` ability.
* **Lieutenant with combi-weapon:** `Paired combat blades` now has the `[ANTI-TYRANIDS 4+]` weapon ability.
* **Bladeguard Ancient:** Changed `1 extra attack` profile ability to `Increase attacks by 1`.
* **Judiciar:** Changed `# extra attack` profile ability to `Increase attacks by #`.

### Infantry/Mounted Changes

* **Centurion Assault squad:** added the `Fortification` keyword to the unit ability `Critical hit : 2 extra hits`.

* **Assault squad:** Weapon profile `Close combat weapon` added.
* **Assault squad with jump pack:** Weapon profile `Close combat weapon` added.
* **Command squad:** Weapon profile `Grav-gun` changed Damage from **1** to **2**.
* **Scout squad:** Weapon profile `Power weapon` changed Strength from **4** to **5**.
* **Vanguard veteran squad:** Weapon profile `Grav-pistol` changed Damage from **1** to **2**.
* **Vanguard Veteran Squad with Jump Packs:** Weapon profile `Grav-pistol` changed Damage from **1** to **2**.
* **Bladeguard veteran squad:** Implemented the `Shields of the Imperium` ability as a profile ability.

* **Incursor squad x5:** Removed the `Oath of Moment` Weapons as they're no longer needed.

* **Desolation Squad:**
  * Renamed from `Desolation Squad x5` to `Desolation Squad` now that it is a fixed squad size of 5.
  *  Added an `Ignores Cover` profile ability, enable this and disable the `-1 to hit roll` profile ability to simulate the `Targeter Optics` ability.

* **Devastator Squad:** Added an `Ignores Cover` profile ability, enable this to simulate the `Signum` ability.
    
### Vehicles Changes

* **Ironclad dreadnought:** `Siege-breaker protocols` Now included as an ability.

* **Brutalis dreadnought:** Added `Brutalis Charge` ability as a weapon profile, disable re-rolls when simulating this.

* **Ballistus Dreadnought:** Removed one of the `Re-roll all possible failed hit rolls (if attacker)` abilities.

* **Land Speeder Tornado:** Added `Strafing Enfilade` ability as a weapon profile, disable re-rolls when simulating this.

* **Hunter:** The ability `Hunter Missile Targeting` that is present on the `skyspear missile launcher` was incorrectly targeting the keyword `FLY` instead of `MONSTER` this has now been corrected.
  
* **Gladiator Lancer:** Added a weapon profile `Lancer laser destroyer (Aquilon Optics)` for simulating the `Aquilon Optics` ability, adjust the damage range to your choice. Copy these re-roll abilities to another weapon if you wish to simulate it on that.
  
* **Gladiator Valiant:** `Twin las-talon` now has two weapon profiles to choose from to simulate `Ferocious Assault`.

* **Impulsor:** Toughness changed from 11 to 9 and Wounds changed from 9 to 11.

<details>
<summary><h2>Update v1.0</h2></summary>

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

</details>