# Aeldari Index v1.2
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
  * **`Mandiblasters:`** *Wargear* <br> Enable the profile ability `Critical wound : mortal wounds equal to weapon damage`.

* #### Autarch Wayleaper:
  * **`Mandiblasters:`** *Wargear* <br> Enable the profile ability `Critical wound : mortal wounds equal to weapon damage`.

* #### Baharroth:
  * **`Cry of the Wind:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Corsair Voidreavers: 
  * **`Reavers of the Void:`** *Ability* <br> Enable the profile ability `Re-roll all possible failed hit rolls`.

  * **`Mistshield:`** *Wargear* <br> Change the Voidreaver Felarchs `Invuln` characteristic to **4**.

  * Included `Shuriken cannon` and `Wraithcannon`. (These cannot be taken in a squad of 5.)

* #### Corsair Voidscarred:
  *This unit will need to be heavily modified!*
  * This `Unit Composition` is set to the maximum squad size and the following roster:
    * 1 Voidscarred Felarch
    * 6 Corsair Voidscarred
    * 1 Shade Runner
    * 1 Soul Weaver
    * 1 Way Seeker

  * **`Piratical Raiders:`** *Ability* <br> Enable the profile ability `Critical hit : always wound`.

  * **`Channeller Stones:`** *Wargear* <br> Cannot be simulated.

  * **`Faolchú:`** *Wargear* <br> Enable the profile ability `Ignores Cover`.

  * **`Mistshield:`** *Wargear* <br> Change the Voidscarred Felarchs `Invuln` characteristic to **4**.

* #### Dark Reapers x5:
  * **`Tempest Launcher - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Tempest Launcher` to simulate `INDIRECT FIRE`.(Enable `Defender in Cover` from **Global Modifiers**)

  * **`Inescapable Accuracy:`** *Ability* <br> Disable all `-# to hit roll` & `Degrade BS by #` Modifiers to simulate this.

* #### Death Jester:
  * **`Cruel Amusement:`** *Ability*  <br> Use either the `Shrieker cannon - (Ignores Cover)` or `Shrieker cannon - (Sustained Hits 3)` to simulate this ability.

* #### Dire Avengers x5:
  * **`Shimmershield:`** *Wargear* <br> Increase the Dire Avenger Exarchs `Invuln` characteristic to **4**.

* #### Fire Prism:
  * **`Crystal Matrix:`** *Ability* <br> Just like the Detachment rule do the following: (This modifier does stack.)
    * Add `Re-roll one possible failed hit roll` to the weapon you want to simulate.
    * Add `Re-roll one possible failed wound roll` to the weapon you want to simulate.

* #### Fuegan:
  * **`Burning Lance:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Illic Nightspear:
  * **`Bringer of the True Death:`** *Leader Ability* <br> Enable the profile ability `Re-roll all possible failed wound rolls`.

* #### Jain Zar:
  * **`Storm of Silence:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Karandras:
  * **`Shadow Hunter:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

* #### Maugan Ra:
  * **`Harvester of Souls:`** *Leader Ability* <br> Enable the profile ability `+1 to hit roll`.

  * **`Face of Death:`** *Ability* <br>  Use the `The Maugetar - (Face of Death)` to simulate this ability.

* #### Night Spinner:
  * **`Doomweaver - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Doomweaver` to simulate `INDIRECT FIRE`. (Enable `Defender in Cover` from **Global Modifiers**.)

* #### Shining Spears x3:
  * **`Shimmershield:`** *Wargear* <br> Change the `Shining Spear Exarch` Invuln Characteristic to **5**.

  * **`4++ Invuln:`** *Ability* <br> Enable this profile ability.

* #### Shroud Runners x3:
  * **`Target Acquisition:`** *Ability* <br> Enable the profile ability `LETHAL HITS (RANGED)`.

* #### Skyweavers:
  * **`Scything Swipes:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers and adjust the weapon count per unit to the desired squad size.

* #### Solitaire:
  * **`Blitz:`** *Ability* <br> Enable the profile ability `Increase attacks by 3`.

* #### Spiritseer:
  * **`Spirit Mark:`** *Leader Ability* <br> Enable the profile abilities `LETHAL HITS` & `+1 to hit roll`.

* #### Striking Scorpions x5:
  * **`Mandiblasters:`** *Wargear* <br> Enable the profile ability `Critical wound : mortal wounds equal to weapon damage`.

* #### Support Weapons:
  * **`D-cannon - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `D-cannon` to simulate `INDIRECT FIRE`. (Enable `Defender in Cover` from **Global Modifiers**.)
  
  * **`Shadow weaver - (Indirect Fire):`** *Weapon* <br> Use this weapon profile instead of `Shadow weaver` to simulate `INDIRECT FIRE`. (Enable `Defender in Cover` from **Global Modifiers**.)

* #### The Visarch:
  * **`Champion of Ynnead:`** *Ability* <br> Instead of using `Asu-var, the Sword of Silent Screams` use one of the following:
    * Sustained Hits 2:  `Asu-var, the Sword of Silent Screams - SH2`    
    * Devastating Wounds:  `Asu-var, the Sword of Silent Screams - DW`
    * Lethal Hits:  `Asu-var, the Sword of Silent Screams - LH`

* #### Troupe Master:
  * **`Choreographer of War:`** *Leader Ability* <br> Enable the profile ability `Devastating wounds (melee)`.
  
  * **`Cegorach’s Favour:`** *Ability* <br> Use the same method shown above in the Army Rule `Strands of Fate`.

* #### Warlock Conclave x2:
  * **`Protect (Psychic):`** *Ability* <br> Enable the profile ability `-1 to wound roll`.

* #### Warlock Skyrunner:
  * **`Runes of Battle (Psychic):`** *Leader Ability* <br> Enable only one of the following profile abilities:
    * **Conceal:** `Stealth`.
    * **Reveal:** `Ignore cover`.

* #### Warlock Skyrunner Conclave x2:
  * **`Protect (Psychic):`** *Ability* <br> Enable the profile ability `-1 to wound roll`.

* #### Wave Serpent:
  * **`Wave Serpent Shield:`** *Ability* <br> Ranged weapon profile, when using disable all `Re-roll hit roll` modifiers.

* #### Windriders x3: 
    * **`Swift Demise:`** *Ability* <br> Enable one of the following profile abilities:
      * `Re-roll all hit roll results of 1`
      * `Re-roll all possible failed hit rolls`.

* #### Wraithblades x5: 
    * **`Forceshield:`** *Wargear* <br> Enable the profile ability `4++ invuln save`.

* #### Wraithknight: 
    * **`Scattershield:`** *Wargear* <br> Enable the profile ability `4++ invuln save`.

* #### Yvraine:
  * **`Herald of Ynnead:`** *Leader Ability* <br> Enable the profile ability `Feel no pain 5+`.

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