# SPT-LootingBots

This mod aims to add a bit more life to the scavs by enhancing some of the bot's base looting behaviors. 

**Base game behavior:**
  - When scavs are on patrol, they have a chance to inspect a nearby corpse and only loot their primary weapon
  - When scavs are on patrol, sometimes they stop in front of a lootable container and pretend to loot it
  
**Modded behavior:**
  - When a scav goes to loot the primary weapon of a corpse they now attempt to loot everything from the corpse, equipping things in empty slots and swapping out gear for better gear
    - Backpack will be swapped if backpack being looted has more slots
    - Bot will always swap to gear that has higher armor rating (helmets, armor vests, armored rigs)
    - When looting larger rigs, bots will swap if currently equipped rig is of equal or lower armor class
    

## Planned features:
- [x] Looting of every item on corpses
- [x] Equipment swapping
- [ ] Bot preference to use looted weapons that are "better"
- [ ] When swapping rigs/bags, transfer items from old item into new item
- [ ] Add corpse looting to pmc bots
- [ ] Enhance base logic for adding corpses to loot pool
- [ ] Apply same looting logic to patrol patterns where scavs stop in front of lootable containers
- [ ] Loose loot detection

## Unknowns:
- Sometimes bots will not loot corpses even after a large amount of time has passed. Need to investigate the base EFT logic and see if I can improve this check
- Do bots despawn after a certain amount of time has passed? Could be problematic if bots with loot randomly disappear mid raid
    