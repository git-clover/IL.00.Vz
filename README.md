# IL.00.Vz
Derrick scrubbed all his creations, and this project was almost forgotten.<br>
Pity me for my work trying to restore this, and thank you u/LookAtDaShinyShiny for NOT having me cry to flood my repositories.<br>
That's all because ```I'm a cyborg```, and I corrode to death if I cry too much.

## INTRODUCTION
This is a heavily modifed Creality K1/K1 Max inspired by [VzBoT](https://github.com/VzBoT3D).
You might want to support Derrick [by giving him money.](https://ko-fi.com/derrickdarrell)

## BOM
You can foresee the BOM if you understand VzBoTs really well.<br>
Or you can mix-and-match different mods yourself, such as:
- a Gantry V2 build on 48 V
- a K1Vz build with other boards (Stay aware! Some don't support anywhere beyond 24 V at all.)
- an FBG build on 60 V (Mine is double-shear!)
- trying to get 2000 mm/s out of a die-cast frame
- any multi-voltage build you could think of

# BIG SAFETY HAZARD BEFORE GOING >30 V!!!!!!
If you plan to go beyond 30 V, step back from this mod.<br>
TMC2209s are very well-known for NOT supporting anywhere beyond 28 V.<br>
Other common traps include:
- TMC2240 (33 V)
- TMC222x (31 V)
- A4988 (Will not even work with the M8P!)
- DRV8825 (Will not work either!)
- TMC2130 (45 V)
- Random stepstick TMC5160 (Dangerous!)

The drivers must have their own documentations! **READ THEM PRIOR TO YOUR PURCHASE!**

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
- Don't print directly on PEI. It'll weld to each other.

# I dare you ask questions about PETG...cuz why not?
If you were about to use PETG for the gantry parts, **don't.**<br>
Rather than melting at the spot, your gantry will first turn into jello. This is called glass transition.<br>
I shouldn't have to explain more, but easily said, **just use ABS.**
