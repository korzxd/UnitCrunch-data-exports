# Aeldari Index v1.1
## General Information
* This Index contains all units from the current `Index: Aeldari` and the `Imperial Armour: Aeldari`.
  
* **`Leaders`** are all separate unit profiles acting as if they were a sole unit on the battlefield, they include their **`Leader`** ability but this should only be used in an **Advanced Profile**. (Refer to [Mixing_Profiles.md](/Guides/Mixing_Profiles.md))
  
* All unit profiles that have a squad size have been created at their minimum size unless stated otherwise.
  
* All unit profile weapons have the default maximum `Count per unit` for that squad size.
  
* All units that have the `Damaged: 1-X Wounds Remaining` ability have a `-1 to hit roll (if attacker)` ability in their unit profile that can be enabled.
  
* All unit profiles have the weapons shown on their datasheet unless specified.
  
* Some Units have Abilities in the form of a Weapon Profile these will have `- (Ability)` at the end of their weapon name.

## Army Rule
* **`Strands of Fate:`** <br> This Army rule cannot be fully simulated within Unitcrunch and below is the process i use to emulate 6's for the `hit roll`.
    1. Select the weapon to emulate and follow the applicable step below.
       * **`Count per unit > 1 & Attacks > 1:`** Subtract 1 from Count per unit & duplicate the weapon, then subtract 1 from the cloned weapon Attacks & duplicate again, then set that duplicate weapon Attacks to 1.
       * **`Count per unit > 1 & Attacks = 1:`** Subtract 1 from Count per unit & duplicate the weapon.
       * **`Count per unit = 1 & Attacks > 1:`** Subtract 1 from Attacks & duplicate that weapon, then set the cloned weapon Attacks to 1.
       * **`Count per unit = 1 & Attacks = 1:`** Proceed to the next step.
    2. Add the preset ability `Always hit`/`TORRENT` to that weapon.

## Detachment Rule
* **`Battle Host - Unparalleled Foresight:`**
  * Add `Re-roll one possible failed hit roll` to the weapon you want to simulate.
  * Add `Re-roll one possible failed wound roll` to the weapon you want to simulate.

## Units - Standard

* #### Asurmen:
  * **`Hand of Asuryan:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Autarch:
  * **`Mandiblasters:`** *Wargear* <br> Enable the profile ability `Critical wound : disable save`.

* #### Autarch Wayleaper:
  * **`Mandiblasters:`** *Wargear* <br> Enable the profile ability `Critical wound : disable save`.

* #### Baharroth:
  * **`Cry of the Wind:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Corsair Voidreavers: 
  * **`Reavers of the Void:`** *"Target's within range of an Objective Marker"* <br> Enable the profile ability `Re-roll all possible failed hit rolls`.

  * **`Mistshield:`** *Wargear* <br> Enable the profile ability `4++ inv`. (Only 1 model can take this Wargear, after 1 model has been slain the accuracy of the simulation drops.)

  * Included `Shuriken cannon` and `Wraithcannon`. Note! these cannot be taken in a squad of 5.

* #### Corsair Voidscarred:
  *This unit will need to be heavily modified!*
  * This `Unit Composition` is set to the maximum squad size and the `Count per unit` on the weapon profiles are based on the following setup:
    * 1 Voidscarred Felarch
    * 6 Corsair Voidscarred
    * 1 Shade Runner
    * 1 Soul Weaver
    * 1 Way Seeker
  
  * **`Psyker:`** *Keyword* <br> Excluded from profile.

  * **`Piratical Raiders:`** *Ability* <br> Enable the profile ability `Critical hit : always wound`.

  * **`Channeller Stones:`** *Wargear* <br> Cannot be simulated.
  
  * **`Faolchú:`** *Wargear* <br> Enable the profile ability `Ignores Cover`.

  * **`Mistshield:`** *Wargear* <br> Enable the profile ability `4++ inv`. (Only 1 model can take this Wargear, after 1 model has been slain the accuracy of the simulation drops.)

* #### Dark Reapers x5:
  * **`Dark Reaper Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

  * **`Tempest Launcher - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Tempest Launcher` to simulate `INDIRECT FIRE`.(Disable `Defender in Cover` from **Global Modifiers**, also the -1 to hit roll has not been included due to the Dark Reapers Ability `Inescapable Accuracy`)

  * **`Inescapable Accuracy:`** *Ability* <br> Disable all `-# to hit roll` & `Degrade BS by #` Modifiers to simulate this.

* #### Death Jester:
  * **`Cruel Amusement:`** *Ability*  <br> Use either the `Shrieker cannon - (Ignores Cover)` or `Shrieker cannon - (Sustained Hits 3)` to simulate this ability.

* #### Dire Avengers x5:
  * **`Dire Avenger Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

  * **`Shimmershield:`** *Wargear* <br> Enable the profile ability `4++ inv`. (Only 1 model can take this Wargear, after 1 model has been slain the accuracy of the simulation drops.)

* #### Fire Dragons x5:
  * **`Fire Dragon Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### Fire Prism:
  * **`Crystal Matrix:`** *Ability* <br> Just like the Detachment rule do the following: (This modifier does stack.)
    * Add `Re-roll one possible failed hit roll` to the weapon you want to simulate.
    * Add `Re-roll one possible failed wound roll` to the weapon you want to simulate.

* #### Fuegan:
  * **`Burning Lance:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Guardian Defenders:
  * **`Heavy Weapon Platform:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### Howling Banshees x5:
  * **`Howling Banshee Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### Illic Nightspear:
  * **`Bringer of the True Death:`** *Leader Ability* <br> Enable the profile ability `Re-roll all possible failed wound rolls`.

* #### Jain Zar:
  * **`Storm of Silence:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Karandras:
  * **`Shadow Hunter:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

  * **`Sustained Assault:`** *Ability* <br> Modifiers already applied to all melee weapons.
  
  * **`The Scorpion’s Bite:`** *Wargear* <br> Modifiers already applied to all melee weapons.

* #### Maugan Ra:
  * **`Harvester of Souls:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

  * **`Face of Death:`** *Ability* <br>  Use the `The Maugetar - (Face of Death)` to simulate this ability.

* #### Night Spinner:
  * **`Doomweaver - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Doomweaver` to simulate `INDIRECT FIRE`. (Disable `Defender in Cover` from **Global Modifiers**.)

* #### Shining Spears x3:
  * **`Shining Spear Exarch:`** <br> Cannot simulate the **3** Wounds characteristic, the best practice would be to increase the Model count by 1 and monitor when 3 models have been slain with 1 wound remaining.

  * **`Shimmershield:`** *Wargear* <br> Enable the profile ability `4++ inv`. (Only the Exarch can take this Wargear, after 1 model has been slain the accuracy of the simulation drops.)

* #### Shroud Runners x3:
  * **`Target Acquisition:`** *Ability* <br> Enable the profile ability `Critical hit : always wound`.

* #### Skyweavers:
  * **`Scything Swipes:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers and adjust the weapon count per unit to the desired squad size.

* #### Solitaire:
  * **`Blitz:`** *Ability* <br> Enable the profile ability `Increase attacks by 3`.

* #### Spiritseer:
  * **`Spirit Mark:`** *Leader Ability* <br> Enable the profile abilities `Critical hit : always wound` & `+1 to hit roll`.

* #### Storm Guardians:
  * **`Serpent's Scale Platform:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### Striking Scorpions x5:
  * **`Striking Scorpion Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

  * **`Mandiblasters:`** *Wargear* <br> Modifiers applied to all melee weapons.

* #### Support Weapons:
  * **`D-cannon - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `D-cannon` to simulate `INDIRECT FIRE`. (Disable `Defender in Cover` from **Global Modifiers**.)
  
  * **`Shadow weaver - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Shadow weaver` to simulate `INDIRECT FIRE`. (Disable `Defender in Cover` from **Global Modifiers**.)

* #### Swooping Hawks x5:
  * **`Swooping Hawk Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### The Visarch:
  * **`Champion of Ynnead:`** *Ability* <br> Instead of using `Asu-var, the Sword of Silent Screams` use one of the following:
    * Sustained Hits 2:  `Asu-var, the Sword of Silent Screams - SH2`    
    * Devastating Wounds:  `Asu-var, the Sword of Silent Screams - DW`
    * Lethal Hits:  `Asu-var, the Sword of Silent Screams - LH`

* #### Troupe Master:
  * **`Choreographer of War:`** *Leader Ability* <br> Enable the profile ability `Critical wound : disable save`.
  
  * **`Cegorach’s Favour:`** *Ability* <br> Use the same method shown above in the Army Rule `Strands of Fate`.

* #### Warlock Skyrunner:
  * **`Runes of Battle (Psychic):`** *Leader Ability* <br> Enable only one of the following profile abilities:
    * **Conceal:** `-1 to hit roll`.
    * **Reveal:** `Ignore cover`.

* #### Warp Spiders x5:
  * **`Warp Spider Exarch:`** <br> Cannot simulate the **2** Wounds characteristic, the best practice would be to increase the Model count by 1.

* #### Wave Serpent:
  * **`Wave Serpent Shield:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers.

* #### Windriders x3: 
    * **`Swift Demise:`** *Ability* <br>
      *  *"Closest eligible target"* <br> Enable the profile ability `Re-roll all hit roll results of 1`.
  
      *  *"Within range of an objective marker they control"* <br> Enable the profile ability `Re-roll all possible failed hit rolls`.

* #### Wraithknight: 
    * **`Scattershield:`** *Wargear* <br> Enable the profile ability `4++ invuln save`.

* #### Yvraine:
  * **`Herald of Ynnead:`** *Leader Ability* <br> Enable the profile ability `Feel no pain 5+`.

* #### Warlock Skyrunner Conclave x2:
  * **`Protect (Psychic):`** *Ability* <br> Enable the profile ability `-1 to wound roll`.

* #### Warlock Conclave x2:
  * **`Protect (Psychic):`** *Ability* <br> Enable the profile ability `-1 to wound roll`.

## Units - Imperial Armour

* #### Cobra:
  * **`D-rift:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers.

* #### Hornet:
  * **`Lightning Assault:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers.

* #### Shadow Spectres x5:
  * **`Shadow Spectre Exarch:`** Not included.

* #### Skathach Wraithknight: 
    * **`Scattershield:`** *Wargear* <br> Enable the profile ability `4++ invuln save`.

* #### Irillyth:
  * **`Reaper of Souls:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.