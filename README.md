How to play:
This game is played on a 5x4 LED battlefield. The objective is to destroy enemy tanks and achieve the highest possible score.
The leftmost button is the FIRE/START button, and the remaining four buttons are used for movement.
Use the directional buttons to move the tank one square at a time in any of the four directions: up, down, left, or right.
Landmines are not displayed on the screen. However, a warning sound will always play if there are landmines above, below, to the left, or to the right of the tank. There is no warning sound for landmines that are positioned diagonally.
Unlike the original game, attacks are performed in two stages. First, press the FIRE button to enter attack mode. Next, press the direction buttons to attack adjacent squares in that direction.
If the attack misses, the tank will not move and attack mode will be canceled. You can also cancel attack mode at any time by pressing the FIRE button again.
Once an enemy tank is destroyed, your score will be displayed, and the game will wait until the next stage begins. Press the FIRE button to start the next stage.
After game over, press the FIRE button to start a new game.

This is a compact handheld gaming console that uses an ATtiny85 microcontroller to recreate the classic retro LSI game "Bandai Combat".
The game display consists of a 5x4 LED matrix showing the player's tank and enemy tanks. Input is provided via a 5-button resistor ladder interface. A 2-digit 7-segment display is used for the score and remaining time, and a piezoelectric buzzer generates sound effects.

I designed the enclosure to the best of my ability, but if anyone has better CAD design skills, please feel free to create a cleaner, more attractive case.
While the 3D print file supports two-color printing, this results in numerous unnecessary filament changes and increased printing time. Therefore, it is recommended to print parts in a single color and paint them later.

The following components are also required to assemble this enclosure (all dimensions are in millimeters):
M2.5 × 6 mm thermosetting insulator (outer diameter 3.5 mm) ×4
M2.5 × 8 mm pan head screws × 8
M2 x 8 mm screws x 2
M2 nuts ×2
2 x AAA batteries, battery holder
Power switch (fits a 7.6 x 15.6 mm opening, with mounting hole spacing of approximately 19 mm)
Hot glue or double-sided tape for securing the battery holder.
OHP transparent film, plastic sheets, tracing paper, super glue, and other materials for creating LED matrix artwork.
Tact switches with a height of 4.7 mm or more for control buttons
8 mm diameter button caps for control buttons
The following files are required to build the project.

Circuit diagram: BandaiCombat_schematic.pdf
Bill of materials: bom.zip
LED Matrix Artwork: film.zip

Note: The PCB files are included in the GitHub repository
at: https://github.com/eggcup001-maker/BandaiCombat/releases/download/v1.0.0/BandaiCombat_Release_v1.0.zip

important:
The resistor network uses four 0603-size SMD resistors. These components are very small and can be difficult to solder by hand. If you are not familiar with surface mount soldering, consider having them assembled during PCB manufacturing or redesigning the PCB to use larger through-hole components.

Disclaimer:
This project is a fan-made recreation inspired by the classic Bandai Combat handheld game. It is intended for educational and hobby purposes only. This project is not affiliated with, endorsed, sponsored, or related to Bandai Namco Holdings Inc., Bandai Inc., or any of their subsidiaries or affiliates. All trademarks and copyrights belong to their respective owners. You are free to enjoy modifying the design. 

Improve the project and make it even closer to the original game.