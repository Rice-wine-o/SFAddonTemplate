# To do list
## Changes
----------
# Power requirements need total reworks
----------
# Many Slimefun Items are heads that should be changed to blocks/multiblocks 
----------
### Reskinned/revised blocks
 - GPS transmitter - Remodel with sunflower upper model, satellite dish texture

### Updated tools
 - Explosive pickaxe - ?? Potentially gunpowder/blaze powder ends
 - Lumber axe - "axe" model rather than a hatchet model, diamond/reinforced
 - Geo Scanner - PDA/GPS model rather than clock 

### GPS
 - Rework into Low Orbit Navigational Satellite
 - Change to multiblock with solar panels on sides
 - Minimum height y=248 
 
### Chest terminal
 - Wireless chest terminal renamed to local wireless CT, more expensive
 - Wireless access terminal now scales on complexity, limited to planets with Low Orbit Navigation Systems
 - Earth/Moon item transport requires 16 high earth orbit satellites
 - Local solar system item transport network requires 32-128 heliocentric orbit satellites (per jump, max 4 AU/jump)
 - Transdimensional access terminal requires 16 transdimensional satellites in the Alpha dimension

## New items/blocks

### Resources
#### Bismuth
 - Found on the moon
 - Emits very weak radioactivity (undetectable without advanced gear)
 - Used to make Polonium-210 via neutron bombardment in a Nuclear Breeder Reactor
#### Polonium-210
#### Enhanced Polonium-210
 - Alloy of Blistering ingot & Polonium-210
#### Plutonium-238
 - created via deuterium bombardment of Uranium-238
#### Enhanced Plutonium-238
 - Alloy of Blistering ingot & Polonium-210
### Power
#### Nuclear Breeder Reactor
 - Actually just an extended vanilla SF reactor
 - Add ability to charge fuels (Bismuth - 210Po)
#### Alpha Reactor 
 - Fuelled by alpha-emitters (Polonium-210, Plutonium-238)
 
|Fuel|Duration|Output|Total|
|--|--|--|--|
|Polonium-210|24hr/1728000 ticks|32 J/s|2.7648 MJ|
|Enhanced Polonium-210|3hr/216000 ticks|320J/s|3.456 MJ|
|Plutonium-238|28d/41472000 ticks|16J/s|33.1776 MJ|
|Enhanced Plutonium-238|84hr/6048000 ticks|160J/s|48.384 MJ|
 

### Fuel items
 - Fuel cell
 - Charged Plutonium-238 (blistering + plutonium 238)

### Rocketry parts (fuselage, aerodynamics, engines, life support, etc.)
 - Ship mainframe (acts as energy regulator/cargo manager/ship computer)
 - Fuselage wall (acts as connector nodes/ capacitors, reskinned iron blocks)
 - Viewing port (reskinned glass block)
 - internal airlock door (reskinned glass panes)
 - external airlock door 
 - external control panel (reskinned iron block)
 - Internal door (reskinned iron bars)
 - Navigation computer (reskinned enchanting table)
 - main engine (ideas?)
 - trim boosters (flower pots?)
 - oxygen recycler 
 - low temperature extended hibernation chamber (multiblock, airlock, requires several actions to enable (cryo brew, initialisation, seal, freeze, wake up, unseal, 30s recovery)
 - cargo hold (solid multiblock)
 - cargo interface (3*7 per page, 4th row 4th column input slot)
 - hydroponic micro farms (reskinned glass block with hologram inside of item being grown)
 - food refinery (creates refined food for extended hibernation)
 - waste recycling system
 - water recycling system


### high earth/solar orbit satellites
Multiblock structures in various worlds (high earth orbit, various solar orbit intervals)
Power system, module system

### GPS 
High earth orbit GPS satellites - allow earth/moon communication

Requires:
- Satellite mainframe (connected to frame, acts as energy regulator & cargo manager)
- Solar panels
- Satellite frame pieces (act as capacitors/connector nodes)
- Docking latch
- Control panel

Optional:
 - Chest terminal relay (requires teleportation relay)
 - Navigation relay
