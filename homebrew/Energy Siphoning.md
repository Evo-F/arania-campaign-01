---
draft: true
---

> [!danger] Spoilers and WIP
> This page is simultaneously a spoiler and a work-in-progress. Just ignore it for now.
# Summary
**Energy siphoning** is a homebrewed mechanic whereby certain characters are able to draw energy directly from their current Plane, typically by utilizing some catalyzing artifact. In extraordinarily rare cases, characters may be able to siphon this energy directly.

Traditional magic draws on the supernatural and extraplanar force known as the Weave. By drawing energy directly from the Plane, those who are not necessarily trained or empowered magic users may still produce certain magical effects, or empower those they can already produce. 
# Planar Spell Slots
If a character is able, they may channel energy directly from the Plane they are currently standing on to generate a **Planar Spell Slot**. A character may only ever have a single Planar Spell Slot, and unused Planar Spell Slots are lost upon the character taking a Long Rest. 

The level of the Planar Spell Slot is determined by how much energy is channeled from the character's Plane. The maximum level of the Planar Spell Slot is determined by the below table. 

| **Character Level** | **Maximum PSS Level** |
| :-----------------: | :-------------------: |
|          1          |           1           |
|          3          |           2           |
|          5          |           3           |
|          7          |           4           |
|          9          |           5           |
|         11          |           6           |
|         13          |           7           |
|         15          |           8           |
|         17          |           9           |
Planar Spell Slots may be used to cast traditional spells, and in this way function identically to normal spell slots. However, casting a traditional spell using a Planar Spell Slot in this way will create unavoidable side effects which may be positive or negative. Refer to the page on [[Planar Spellcasting]] for details.
# Energy Absorption
In order to generate a Planar Spell Slot, a character must expend an Action and all of their remaining movement. This will cause the character to channel energy directly from the Plane they are standing on. 

Channeling in this fashion will create an area with a radius of `5 x PSS Level`. This area is considered **Deadened** and will take on a grayed and ashen appearance. Areas that are **Deadened** cannot be used to channel a Planar Spell Slot, and will limit the radius of future channeling attempts. 

The **Deadened** effect may compound on a given tile based on its neighbors:
- If a **Deadened** tile is completely surrounded by other **Deadened** tiles, it becomes a **Drained** tile. 
- If a **Drained** tile is completely surrounded by other **Drained** tiles, it becomes a **Void** tile. 
# Voids and Energy Dynamics
Tiles which are **Deadened** or **Drained** have the potential to eventually return to normal, given enough time and optional restorative efforts. Tiles which have become **Void**, on the other hand, cannot be restored by any normal means, and will continuously drain energy from the surrounding tiles. 
# Tile Effects
Depending on the state of a tile, any character standing on it may experience certain effects.
## Deadened
- Channeling Planar Spell Slots is not possible. 
- Concentration Saving Throws are rolled with Disadvantage.
## Drained
- All of the effects of **Deadened** tiles.
- Constitution and Wisdom Saving Throws are rolled with Disadvantage.
- Attempting to Long Rest on a **Drained** tile requires a DC 15 Constitution check. Failing this check requires a d4 roll on the below table:

| **d4 Roll** | **Effect**                                                                                                                         |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 1           | Character takes one point of exhaustion after the Long Rest.                                                                       |
| 2           | Character has -4 AC until next Long Rest.                                                                                          |
| 3           | Character HP restoration from Long Rest is capped at 80% of max HP, rounded down.                                                  |
| 4           | Character only restores spell slots as though they had taken a Short Rest. If the character has no spell slots, roll the d4 again. |
## Void
- All of the effects of **Drained** tiles.
- All Saving Throws are rolled with Disadvantage. 
- Casting a spell using a normal spell slot or scroll may result in a Miscast. Refer to [[Planar Spellcasting]] for more information.
- It is impossible to Long Rest on a **Void** tile.


