# incremental-game (Chronostasis)
Incremental game made in HTML, JavaScript, and CSS.<br>
Hope you enjoy!<br><br>
Link: https://migearu.github.io/incremental-game/main.html<br><br>
# Credits where they're due
[Hector Polanco](https://github.com/hecpolanco), [Simple-Music-Player](https://github.com/hecpolanco/Simple-Music-Player)
# Things I don't know how to fix
~~Buy Amount text field not excluding special characters.~~ Fixed with regex, taken from the OmegaNum.js library (41)
# Ideas and Calculations
## Some things to note
The formula used for price calculation is ![image](https://user-images.githubusercontent.com/75057913/147889111-d0267914-cfa7-427c-ab93-78ba5e7d45ee.png), where b is the base cost, x is the price ratio, and y is the # of item bought (does not include items generated from higher tiers).
# Update 1
For the current moment, to save and load, call WriteToStorage(gameData, "chronostasis-save"), and ReadFromStorage("chronostasis-save").<br>
Why? Because I am too lazy to fix that right now, however it will be fixed in the next update.
# Update 2
## In-Game
Included a tab switcher from the "Time" menu to the "Menu" menu, where you can find saving and loading, as well as import/export.<br>
Made good use of that multiplier, current formula is ![image](https://user-images.githubusercontent.com/75057913/147837039-439b5cda-ba91-45b1-8bba-294d30a8bad3.png), where x is equal to the number of tier bought.<br>
## Extra
Organized into folders.<br>
Elements now grouped and rendered in separate scripts, to add code readability.
## Bugs
Multiplier caps at 1.79e308 (Infinity) because of operator errors, already fixed but change not rolled out yet
# Update 3
## In-Game
Autobuyers implemented, up to tier 10<br>
Formula for Autobuyer interval is ![image](https://user-images.githubusercontent.com/75057913/147888930-5db39eff-8b23-4253-b19a-8481846d70ed.png), where x = the amount of upgrades.<br>
Added a hover effect.<br>
(note: I eventually plan to add a prestige layer, maybe in the next update or two)
## Extra
N/A
## Bugs
Intervals stuck at 1000 ms.
## Update 3.1
### In-Game
Properly added Autobuyers, added an on/off switch, as well as properly implementing intervals.
# Update 4
## In-Game
### Prestige
Time Crystal Gain: ![image](https://user-images.githubusercontent.com/75057913/147837315-77d058ee-36c0-498b-8f9d-a8213d09af69.png), where x is equal to Time Particles<br>
General Multiplier from Time Crystals: ![image](https://user-images.githubusercontent.com/75057913/147837406-4cf22fcd-90ca-4ed9-9849-574e8a127227.png), where x is equal to Time Crystals, and a is an upgradeable value that decreases.
### Songs
A new songs tab is available.<br>
As of now, only one song is available, but I do plan on adding more into the future.<br>
Songs are paused by default as well.
## Extra
Credit for the song player goes to Hector Polanco.<br>
Added assets folder.
## Bugs
None as of yet, although I will try to look through to find any.
## Update 4.1
### In-Game
Added 2 more tracks.
