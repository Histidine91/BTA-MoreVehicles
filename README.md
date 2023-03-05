# More Vehicles for BTA #

## What is this? ##
This is a third-party mod for the BATTLETECH Advanced 3062 (BTA) mod pack for the game BattleTech (2018) by Harebrained Studios (HBS BT).

It makes some otherwise unplayable vehicles in BTA now playable (including select Clan vehicles), and adds a number of new vehicles.

## Setup instructions ##
Simply download or check out this Git repository to `BATTLETECH/Mods`, then run the game.

Note: Some vehicles require certain DLC and/or the BTA Community Content pack. If you lack either, go into `More Vehicles/vehicle` and delete the vehicle def file for that vehicle. It may be necessary to do the same with the chassis def in `More Vehicles/vehiclechassis`


## License ##
Anything copyrightable by me specifically is released as public domain/CC-0, do whatever with it. 

All other rights belong to their respective authors.

## List of vehicles ##

### Vehicles made playable ###
Inner Sphere vehicles:
- Striker Mk.4-C3   (light)
- Myrmidon (medium)
- Light TBM5 Carrier (medium)
- Sabaku Kaze (medium)
- Gallant Mk. 3 (heavy)
- Patton Mk. 2 (heavy)
- Brutus (Support) (heavy)
- Heavy MRM Carrier (assault)

Clan vehicles:
- Shamash (light)
- Svantovit IFV (light)
- Ares (medium)
- Epona Prime (medium)
- Pike (heavy)
- Morrigu Fire Support Vehicle (assault)

Note: No attempt has been made to ensure these vehicles are actually used by any faction.

If you want to unlock more vehicles, add the relevant vehicle def IDs to the `TargetIDs` list in `More Vehicles/merge/mergeDef_unlockTanks.json`.

### New variants of existing vehicles ###
- Super Hetzer
	- The boxy assault gun has been redesigned with a Heavy Gauss Rifle. Fielded by Steiner and certain private groups.
- Merkava EX
    - A demonic upgrade of the original, featuring a Heavy PPC. Fielded by various non-Successor State, non-Clan factions.

### Original vehicles ###
"By Donut Steel Industries"
- Commandant
	- A fast 50-ton tank armed with twin LAC/5s. Fielded by most/all IS factions.
- Desaix
	- A 65-ton high-performance tank, available in three variants with varying configurations. Fielded by Davion and certain private groups able to afford it.
- Wuguan Siege Gun
	- A 55-ton self-propelled gun with a Long Tom Cannon and 5 tons of ammo (including 1 ton of 'special surprise'). Not fielded by anyone, thankfully.
	
## Shop locations ##
**Inner Sphere-level Civilization planets** will sell the Light TBM5 Carrier, Gallant Mk. 3, Myrmidon, and Commandant if you have some reputation with the planet owner. With higher rep, the Patton Mk. 2, Brutus (Support), and Heavy MRM Carrier become available. The Light TBM5 Carrier and Commandant are also available on **Periphery-level Civilization planets** with higher rep.

**Davion planets** sell the Desaix B with some rep. The A and C variants are on **Steiner planets** but require higher rep; these also sell the Super Hetzer with less rep.

**Liao planets** sell the Wuguan with high rep.

**Kurita planets** sell the Striker Mk.4-C3 and Sabazku Kaze with some rep.

**ComStar planets** sell the Merkava EX with high rep.

The Shamash, Svantovit and Ares are sold on **Clan Diamond Shark** planets, as well as **Clan Nova Cat** planets with some rep. At Honored relations, the Nova cats will throw in the Epona Prime as well. The Pike and Morrigu can only be obtained from salvage.