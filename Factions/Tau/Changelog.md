# T'au Index

## Update v1.2
###### 30/05/2024
### General

* Created a `Readme.md` similar to the other factions, this also includes how to setup the Army & Detachment rules.

* A Legends Data Export has been created. This is currently acting as storage for the units that have moved from the old Data export and will be reviewed at a later date.

* Updated Point values of all units to match the Munitorum Field Manual v1.10.

* Removed the Leader Squad profiles as these will soon become redundant.

* Removed the Kauyon & Army Rule Modifiers from all profiles.

* New Unit Profiles
  * Kroot Flesh Shaper
  * Kroot Lone-Spear
  * Kroot Trail Shaper
  * Kroot War Shaper
  * Krootox Rampagers
  * Crisis Fireknife Battlesuits 
  * Crisis Starscythe Battlesuits
  * Crisis Sunforge Battlesuits
  * Tidewall Shieldline (Defence Platform)
  
* Removed Unit Profiles
  * Kroot Shaper
  * *Leader & Squad Profiles*

* Moved to Legends Data Export
  * Aun'shi
  * Aun'va
  * Barracuda
  * Commander in Crisis Battlesuit
  * Longstrike
  * Crisis Battlesuits
  * R'varna Battlesuit
  * Tactical Drones
  * Tetras
  * Y'vahra Battlesuit
  * Remora Stealth drones

* Modified Unit Profiles
  * Broadside Battlesuits - matches codex
  * Devilfish - matches codex
  * Kroot Carnivores - matches codex
  * Kroot Hounds - matches codex
  * Krootox Riders - matches codex
  * Hammerhead Gunship - matches codex
  * Sky Ray Gunship - matches codex
  * Commander Farsight - matches codex
  * Tidewall Shieldline - Removed Strike team simulating firing deck
  * Tidewall Droneport - Removed Strike team simulating firing deck
  * Tidewall Gunrig - Removed Strike team simulating firing deck
  * Ethereal - added leader ability
  * Darkstrider - added leader ability
  * Cadre Fireblade - added leader ability
  * Commander in Enforcer Battlesuit - matches codex, added leader ability
  * Commander in Coldstar Battlesuit - matches codex
  * Hammerhead Gunship - removed `LETHAL HITS`
  * Riptide Battlesuit - removed `-1 to hit roll`


<details>
<summary><h2>Update v1.1</h2></summary>

###### 28/07/2023
### General

* Added Squads with **`Leader`** all set to the minimum unit count.
  * The **`Leader`** keywords will not be included in the profile.
  * The **`Leader`** weapons will be tagged with their name and maximum count per unit.
  * Any **`Leader`** that has an invul/FNP that is different from their attached unit will not be included as this cannot be simulated. (Note Leader abilities that grant the whole unit the same invul/FNP characteristic has been implemented)

* Included changes from the recently released Index cards v1.2, these are listed below.

* The following units have a number of weapons that exceed the 15 weapon limit in unitcrunch. The attached **`Leader`** ranged weapons are not included in the profile unless stated below, the missing weapons will need to be added manually:
	* **Crisis Battlesuits x3 (CRISIS COMMANDER)**
	* **Crisis Battlesuits x3 (ENFORCER)**
	* **Crisis Battlesuits x3 (COLDSTAR)**
		* Added weapon profile **`High output burst cannon`**
	

### Changes
* **Crisis Battlesuits x3:** 
	* **`Airbursting fragmentation projector`**
		* BS changed to 4+
		* Count per unit changed to 3
* **Hammerhead Gunship:**
	* Added the Longstrike buff as the Unit ability **`LETHAL HITS`** that can be enabled/disabled. 
* **Breacher Team:**
	* Changed unit ability **`Re-roll all possible failed wound rolls (if attacker)`** to **`Re-roll all possible failed wound rolls (ranged only) (if attacker)`**.
	* Changed unit ability **`-1 to wound roll (if defender)`** to **`-1 to wound roll (ranged only) (if defender)`**.
* **Strike Team:**
	* Changed unit ability **`-1 to wound roll (if defender)`** to **`-1 to wound roll (ranged only) (if defender)`**.
* **Devilfish:**
	* **`Accelerator burst cannon`**: AP changed to -1
* **Longstrike:**
	* **`Accelerator burst cannon`**: AP changed to -1
* **Razorshark Strike Fighter:**
	* **`Accelerator burst cannon`**: AP changed to -1
* **Sun Shark Bomber:**
	* Added **`Missile pod`** weapon profile.

### New Unit Profiles

* **Crisis Battlesuits (FARSIGHT):**
	* Enable/disable the unit ability **`+1 to wound roll`** to simulate the **`Way of the Short Blade`** ability.
	* To simulate **`Aggressive Offensive`** on **`Commander Farsight`** add re-roll all hit and wound rolls to all of his weapons.
* **Crisis Battlesuits x3 (CRISIS COMMANDER)**
  * Does not contain any **`Leader`** ranged weapons.
* **Crisis Battlesuits x3 (ENFORCER)**
  * Does not contain any **`Leader`** ranged weapons.
* **Crisis Battlesuits x3 (COLDSTAR)**
  * Does not contain any **`Leader`** ranged weapons (Except **`High output burst cannon`**).
* **Breacher Team (CADRE FIREBLADE)**
* **Breacher Team (ETHEREAL)**
* **Breacher Team (AUN'SHI):**
	* Aun'Shi unit ability **`Martial Warrior`** has been added as 3 different weapon profiles, only select 1 when simulating.
* **Strike Team (CADRE FIREBLADE)**
* **Strike Team (ETHEREAL)**
* **Strike Team (AUN'SHI)**
	* Aun'Shi has 3 weapon profiles for Fidelity: Standard, Forceful Strike & Whirling Stance. Only select 1 when simulating.
* **Kroot Carnivores (AUN'SHI)**
	* Aun'Shi unit ability **`Martial Warrior`** has been added as 3 different weapon profiles, only select 1 when simulating.
* **Kroot Carnivores (KROOT SHAPER)**
	* **`Ritualistic Feeding`** Ability added to the weapon **`Shaper’s ritual blade`**.
* **Pathfinders (DARKSTRIDER)**
* **Tidewall Shieldline (Strike Team x20):** 
  * **`-1 to hit roll`** ability to simulate shooting into engagement.
  * By default it contains 20 Strike Team Fire Warriors with Pulse rifles, change this to the unit you want to simulate.
  * Change the points to 105 and the wounds to 15 to simulate the wargear **`Tidewall Defence Platform`**.
* **Tidewall Gunrig (Strike Team x10), Tidewall Droneport (Strike Team x10):**
  * **`-1 to hit roll`** ability to simulate shooting into engagement.
  * By default it contains 10 Strike Team Fire Warriors with Pulse rifles, change this to the unit you want to simulate.
</details>

<details>
<summary><h2>Update v1.0</h2></summary>

###### 25/07/2023
***NOTE: Some of the descriptions below could be inaccurate as this took a while to create and Unitcrunch has had updates since.***
### General
* All eligible unit profiles have 3 abilities representing the beneficial moments of the army rule **`For the Greater Good`** (**FTGG**) and the detachment rule **`Kauyon`**:
	* **`Improve BS by 1`** (Guided shooting spotted unit)
	* **`Critical hit: 1 extra hit`** (Kauyon)
	* **`Critical hit: 2 extra hits`** (Kauyon & Guided shooting spotted unit)
* I have not included the negative ability for guided units not shooting at there spotted unit in any of the unit profiles.
* Also the **`[IGNORES COVER]`** gained from being observed by a unit with **`Markerlights`** has not been added to any of the unit profiles.

* **`Leaders`** are all separate unit profiles acting as if they were a sole unit on the battlefield and thus they do not include there **`Leader`** ability.

* All unit profile weapons have the default maximum count per unit.

* Some Drone wargear is present on eligible Unit profiles:
	* Gun Drone - Maximum amount of gun drone weapons added to that unit.
	* Shield Drone - Not included, you will need to manually increase the Wounds of your unit.
	* Marker Drone - Not needed
	* Guardian Drone - As a unit ability.
	* Missile Drone - Maximum amount of missile drone weapons added to that unit.

All units that have **`Damaged: 1-X Wounds Remaining`** have a -1 to hit roll ability in there unit profile that can be turned on/off.

### Units
#### Current Range
* **Aun'va:** has several profiles due to different characteristics
* **Longstrike:** **`Targeting array`** has not been included, this will need to be added to one individual weapon profile manually.
* **Commander in Crisis Battlesuit, Commander in Enforcer Battlesuit, Commander in Coldstar Battlesuit, Crisis Battlesuits x3:** Have not included **`Weapon support System`** for ignoring hit roll modifiers.
* **Ghostkeel Battlesuit:** Stealth drones cannot be simulated.
* **Riptide Battlesuit:** Have not included **`Weapon support System`** for ignoring hit roll modifiers, Nova Charge is not present on any weapons and will need to be added if you wish to simulate it.
* **Hammerhead Gunship:** Targeting array has not been included, this will need to be added to one individual weapon profile manually.
* **Tidewall:** Excluded from unit profiles.
* **Stormsurge:** Have not included **`support System`** as i cannot make an ability for this.
* **Kroot Farstalkers:** Have not included **`Pech'ra`** wargear ability as this would need to added to each weapon individually.
#### Forgeworld Range
* **Y'vahra Battlesuit, R'varna Battlesuit:** Have not included **`Weapon support System`** for ignoring hit roll modifiers.
* **AX-1-0 Tiger Shark:** The **`Titan Hunter`** ability is already baked into the weapon profiles.
* **Manta:** Points value is incorrect as 2000 is the maximum.
</details>