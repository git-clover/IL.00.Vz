# IL.00.Vz
Derrick scrubbed all his creations, and this project was almost forgotten.<br>
Pity me for my work trying to restore this, and thank you u/LookAtDaShinyShiny for NOT having me cry to flood my repositories.<br>
That's all because ```I'm a cyborg```, and I corrode to death if I cry too much.

## INTRODUCTION
This is a heavily modifed Creality K1/K1 Max inspired by [VzBoT](https://github.com/VzBoT3D).<br>
Better when paired with a new bed frame: [now on IL.00!](https://github.com/git-clover/IL.00)

## BOM
You can foresee the BOM if you understand VzBoTs really well.<br>
Or you can mix-and-match different mods yourself, such as:
- a Gantry V2 build on 48 V
- a K1Vz build with other boards (Stay aware! They often don't have double PSU mounts.)
- an FBG build on 60 V (Mine is double-shear! Coming soon.)
- trying to get 2000 mm/s out of a die-cast frame (Do it! You're SO ready if you know the entire BOM only from this sentence)
- any multi-voltage build you could think of

# BIG SAFETY HAZARD EVERYWHERE!!!!!!!!!!!!!!!!!!!!!!!!
If you plan to go beyond 30 V, dare to tweak around with 5160s.<br>
TMC2209s are very well-known for NOT supporting anywhere beyond 28 V.<br>
Other common traps include:
- TMC2240 (33 V)
- TMC222x (31 V)
- A4988 (Will not even work with the M8P!)
- DRV8825 (Will not work either!)
- TMC2130 (45 V)
- Random stepstick TMC5160 (Dangerous!)

**ALL** stepstick drivers, especially ones that have DuPont jacks, only can deliver juice up to 2 amps. Only 5160s can do 3 amps.<br>
You do NOT want your precious drivers melting just because you wanted to print like a rocket. It'll set your printer on fire.

If you still don't understand what those mean, **get out of here and come back later.**

## Print Settings
For ABS/ASA:
- 7 walls
- 5 top/bottom
- 40% infill
- Some require supports, but your eyes always know.
- Set brim to "mouse ears" and use it for any small parts. You can save filament and stick parts better.

If you have enough money for PC-CF:
- 5 walls
- 5 top/bottom
- 29% infill
- Some require supports, but your eyes always know.
- It tends to weld to PEI a little too well. PLEASE consider using release agents.

# I dare you ask questions about PETG...cuz why not?
If you were about to use PETG for the gantry parts, **don't.**<br>
Rather than melting at the spot, your gantry will first turn into jello. This is called glass transition.<br>
And what else will happen when the very thing fixing the motor turns into jello? It'll fall mid-print.<br>
You don't have a Voron 2.4. It's a VzBoT. You think your K1 could have flying gantry?<br>
I shouldn't have to explain more, but easily said, **just use ABS.**
