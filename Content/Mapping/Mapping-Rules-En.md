
# Mapping rules

This document contains all the rules that **must be followed when developing maps**. 
The rules may be caused by technical limitations, game design decisions, or just not obvious pitfalls that should be avoided. 

 The rules should be described in a sufficiently capacious and detailed way to work in particular as a **manual**, and a **checklist**. The mapper who has this document should be able to understand and correct all the mistakes made.

Changes to these rules that conflict with the currently created maps **must be duplicated with the creation of an issue in GitHub** to fix these conflicts in maps that do not follow these rules.

 Currently, the rules are not sorted in any way, and they can be added in any place or order. 
*TODO: add sorting when there are enough rules.*
*TODO: mapping checklists should be accompanied by examples.*
*TODO: should the checklists be in a separate document?


## Game maps are planetary maps.
We have abandoned grids, so the map on which the game settlement is located must be a planetary map.

 Generation outside of mapping allows you to play with it in various ways, allowing you to create both an infinite ocean and an infinite stone.

 You can find some map presets in the path `Maps/_CP14/Empties`, and if you have created a new biome for your map, don't forget to add it in the same path.

## Day and Night Cycle
The Day and Night cycle should be enabled on all maps. The sunlight mechanic, which goes along with the cycle, is gameplay-wise necessary for the Sylv race and the garden mechanics.
This restriction will likely be removed in the future, to support underground maps.

## Opportunities for Antagonists
There should be vampire shelters near all player spawn points (leitjoins or spawnjobs), which can be reached in 5-10 seconds. Either the spawners must be under shelters. Shelter is considered any place where there is no sun (roofs, or descent into caves).
Inconspicuous, unused passages, such as underground passages

## Distribution of keys from personal rooms
Adding personal rooms to the map (personal houses, alchemical shops, blacksmith shops), it is necessary to add the necessary components to the station prototype. 
TODO instruction

## General
- raid markers outside the city
- observer spawn marker
- essence node spawn markers
- filled crates
- all buildings must have a back door and lighting in the form of lamps in private buildings and torches in public places
- lighting and wells throughout the city
- public trading room
- variantize command at the end of work


## Craftsmen: General
Required:
- Specialized wardrobe
- Specialized chest of drawers
- bed
- tapestries
- a window with a tabletop grill for trading, an artisan must have easy access to the back side.
- The bell
Optional:
- basement
- ingredients for production products
Forbidden:
- finished products of production

## The Alchemist's Shop
Necessarily:
- Solution cleaner, oven
- 2 wall shelves for bottles
- water source
Optional:
- a cellar with empty barrels

## Blacksmith's shop
Necessarily:
- The anvil
- Melting furnace
- Workbench
- Several ready-made handles and tips for weapons of different types and materials

## Merchants
Necessarily:
- Shops:
- safe and display cases
- trading platforms

## The Tavern
Necessarily:
- Bulletin board
- A cellar filled with barrels of drinks
- a backyard with garden beds, a pond, and a couple of planted crops. A chest or sack of seeds
- an oven


## Guildmaster's Shop - temporarily unavailable. you can ignore some of the points
Required:
- a private room with a wardrobe, a chest, and a bed
- a chest with demiplane keys and shelves for them
- a box/chest with ready-made weapons for adventurers
- a demiplane crystal near the house or in the basement
- a tapestry
Optional:
- Scrolls for entering the demiplane and teleporting to the monolith.


## The Guard
- Barracks with beds and dressers
- A building site marked with decals
- A weapons storage room
- A separate room for the captain of the guard
- A bell on the street
- A tapestry
- A wall around the settlement with multiple exits (don't forget to add windows for checking passports)