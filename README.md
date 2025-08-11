<!-- ![requirements](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fraw.githubusercontent.com%2FRimCorePlus%2FTraits%2Frefs%2Fheads%2Fmain%2FAbout%2FAbout.xml&query=%2F%2FdisplayName&style=for-the-badge&label=Requires&color=mediumpurple) -->
[requirements]: https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fraw.githubusercontent.com%2FRimCorePlus%2FTraits%2Frefs%2Fheads%2Fmain%2FAbout%2FAbout.xml&query=%2F%2FdisplayName&style=for-the-badge&label=Requires&color=mediumpurple
<!-- [![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0) -->
[badge-license]: https://img.shields.io/badge/License-GPLv3-lightgray?style=for-the-badge

# [RCP] Backstories and Traits
![](About/Preview.png)\
[![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0)

> [!IMPORTANT]
> Integrated with [Trait and Backstory Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=2873494547) (optional).\
> Integrated with [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206) to disable unwanted backstories and traits (optional).

## Backstories
### Asteroid miner
*Childhood*
> Tynan's family owned an orbital mining fleet. When they weren't bartering with traders on the surface, they were moving between mineral-rich asteroids in orbit.
> 
> Tynan spent most of his time hauling valuables to the gravship.

Skill gains:
- Mining: 5

### Galley porter
*Childhood*
> Tynan always dreamed of being a chef. As soon as he was old enough to work, he took a job cleaning dishes and prepping vegetables in the galley.
> 
> Tynan spent his free time bantering with the other staff.

Skill gains:
- Cooking: 3
- Social: 2

### Gravship colonist
*Childhood*
> Tynan was born and raised on a gravship. He received training to repair and maintain the ship's systems.
> 
> Tynan didn't interact with anyone besides his parents and the captain.

Skill gains:
- Construction: 3
- Crafting: 2
- Social: -2

### Hydroponics farmer
*Childhood*
> Tynan was born and raised on a civilian garden vessel. His formative years were spent tending to crops and learning to maintain the hydroponics system.
> 
> The ship's crew was small and lacked combat experience, so Tynan had to help defend against raids.

Skill gains:
- Crafting: 1
- Plants: 3
- Shooting: 1

### Lone survivor
*Childhood*
> Tynan was the only survivor of a nasty plague. He drifted alone aboard a derelict gravship for months, living off of the dead crew's rations.
> 
> Tynan's sculptures kept the loneliness at bay until an orbital trading ship found him.

Skill gains:
- Artistic: 3
- Crafting: 2

### Medical student
*Childhood*
> Tynan grew up on a satellite that offered medical services and ship repairs. He learned how to perform first aid and helped the surgeon with minor operations.

Skill gains:
- Intellectual: 2
- Medicine: 3

### Orbital pirate
*Childhood*
> Tynan was raised by an orbital pirate gang. He was used as bait, pretending to be injured long enough for his crew to ambush anyone who responded to the distress calls.
> 
> Tynan took joy in watching them die.

Skill gains:
- Melee: 3
- Shooting: 2

Forced traits:
- Psychopath

## Traits
Stat factors multiply the pawn's stat by the given amount. Stat offsets add (or subtract) the pawn's stat by the given amount.

### Ace pilot (requires Odyssey)
> Tynan's heart yearns for the stars.

Forced passions:
- Intellectual

Possessions:
- PilotAssistant: 1

Stat offsets:
- PilotingAbility: 0.5

### Angler (requires Odyssey)
> Tynan loves casting lines. He catches fish faster than everyone else.

Forced passions:
- Animals

Possessions:
- Fish_Salmon: 5~10

Stat offsets:
- FishingSpeed: 0.25
- FishingYield: 0.1

### Drug dealer
> Tynan has a knack for cutting deals on illicit substances and can synthesize drugs with remarkable efficiency.

Possessions:
- Flake: 5~10

Stat offsets:
- DrugCookingSpeed: 0.25
- DrugSynthesisSpeed: 0.25
- DrugSellPriceImprovement: 0.1

Disables mental breaks:
- Binging_DrugExtreme
- Binging_DrugMajor

### Eloquent
> Tynan has the gift of gab. Negotiations come naturally to him.

Forced passions:
- Social

Possessions:
- Apparel_BowlerHat: 1

Stat offsets:
- SocialImpact: 2
- NegotiationAbility: 0.5
- TradePriceImprovement: 0.5
- ConversionPower: 0.5

### Green thumb
> Tynan is a plant whisperer. Working with crops comes naturally to him.

Forced passions:
- Plants

Possessions:
- PlantPot: 1

Stat offsets:
- PlantWorkSpeed: 0.25
- PlantHarvestYield: 0.1

### Laborer
> Tynan lacks the finesse for skilled tasks, but excels at hard, physical labor.

Disabled work tags:
- ManualSkilled

Stat factors:
- GeneralLaborSpeed: 0.5

Stat offsets:
- CleaningSpeed: 0.25
- CarryingCapacity: 15

### Slop enjoyer
> Tynan appreciates the taste of nutrient paste. He will never complain about eating it.

Possessions:
- MealNutrientPaste: 2~4

Disables thoughts:
- AteNutrientPasteMeal

### Void repulsion (requires Anomaly)
> Tynan believes unnatural entities are the harbinger of end times. He would rather kill them than study them.

Possessions:
- Shard: 1

Only allowed mental breaks:
- EntityKiller
- InsaneRamblings

## Legal
Portions of the materials used to create this mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This mod is not official and is not endorsed by Ludeon.

Icons by [Delapouite](https://delapouite.com/) and [Lorc](https://lorcblog.blogspot.com/). CC BY 3.0 [Game-icons.net](https://game-icons.net/)