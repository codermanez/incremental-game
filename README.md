# incremental-game (Chronostasis)
Incremental game made in HTML, JavaScript, and CSS.<br>
Hope you enjoy!<br><br>
Link: https://codermanez.github.io/incremental-game/main.html<br><br>
# Things I don't know how to fix
Buy Amount not
# Ideas and Calculations
## Prestige Mechanics
I already have the first one down, probably gonna be called Time Condensation, currency would be Time Crystals<br>
Time Crystal Gain: ![image](https://user-images.githubusercontent.com/75057913/147837315-77d058ee-36c0-498b-8f9d-a8213d09af69.png), where x is equal to Time Particles<br>
General Multiplier from Time Crystals: ![image](https://user-images.githubusercontent.com/75057913/147837406-4cf22fcd-90ca-4ed9-9849-574e8a127227.png), where x is equal to Time Crystals
# Update 1
For the current moment, to save and load, call WriteToStorage(gameData, "chronostasis-save"), and ReadFromStorage("chronostasis-save").<br>
Why? Because I am too lazy to fix that right now, however it will be fixed in the next update.
# Update 2
## In-Game
Included a tab switcher from the "Time" menu to the "Menu" menu, where you can find saving and loading, as well as import/export.<br>
Made good use of that multiplier, current formula is ![image](https://user-images.githubusercontent.com/75057913/147837039-439b5cda-ba91-45b1-8bba-294d30a8bad3.png), where x is equal to the number of tier bought.<br>
Made code more efficient, to run the game faster
## Extra
Organized into folders.<br>
Elements now grouped and rendered in separate scripts, to add code readability.

