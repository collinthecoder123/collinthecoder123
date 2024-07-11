Welcome to Super Mario Odyssey Safari!

== STORY ==
In the middle of their journey to the Cascade Kingdom, a mysterious rabbit chews the wire ahead, causing them to be flung to a nearby island. Mario and Cappy, still eager to start the chase after Bowser, must find a way off the island before Bowser leaves them in the dust!

== CONTROLS ==
The default controls are listed below. You may change them at any time either on the title screen, or the pause screen, and selecting Options > Keybinding.

Arrow keys - Move
Z - Jump
X - Throw
C - Map
Enter - Pause

== MOVES ==
Mario has adopted his move set from Super Mario Odyssey for a (slightly) new take on the 2D Mario formula. Here are some iconic moves you may find useful:

* Hip Drop - Press down after a jump to drop down on the spot.
* Wall Jump - Hold towards a wall, and press jump to kick off the wall.
* Long Jump - Crouch, Hold a direction, then jump to fly forward! Be careful not to hit walls this way.
* Dive - Jump, Ground Pound, and while still in the air, press throw to fly forward in the air.
* Triple Jump - If you time three jumps in a row, Mario will soar super high on the third.
* Spin - Press left and right in quick succession to start spinning. In this state, you can fall slower and perform a large stomp.
* Side Somersault - Quickly reverse direction and jump to perform a Side Somersault.
* Backflip - Crouch, move backwards, and jump to perform a high backflip.
* Cap Throw - Press throw to throw Cappy. Cappy will quickly return to you though, so don't be afraid of losing him.
* Grab - Hold throw while running into something you can pick up to... pick it up!
* Up and Down Throw - Press throw and then quickly up or down to throw Cappy in that direction.
* Hatsorb - A mysterious ability Cappy seems to have learned out of thin air. When cappy is in range of an enemy, press throw again to latch on. Once he's latched on, keep pressing X until you hatsorb the enemy! Make use of the new physics and abilities to forge your path ahead!
* Hatsorb Discard - Crouch, and press C to discard your hatsorb.

Thank you for playing!

== TROUBLESHOOTING ==

** If the application does not finish loading or you experience immense (<10FPS) slowdown:

- Please check your available memory. The game typically uses just above 1GB of memory, which Java will not allocate unless there is a sizable (>5% free) of physical memory left on the disk, give or take. There also may be other restrictions set by antivirus, system administrators, etc.

- Low battery on certain devices also causes slowdown for the program. Make sure your device is charged!

- You may try using the Command Line to increase the amount of allocated memory to the game. Navigate to the folder using the command prompt (Use cd and (Windows: ls / Mac: dir) to change directories, and print the folders and files where you are, respectively. Once you see the executable printed in the list from ls/dir, copy/paste the following command based on which version you have:

java -jar -Xms1g -Xmx1280m "Super Mario Odyssey Safari.jar"
java -jar -Xms1g -Xmx1280m "Super Mario Odyssey Safari (MFGG Release).jar"

** If your preferences are lost:

There is a known bug in the game where the preferences.json file becomes corrupted. Please keep a backup of the file in case this happens.

** If your controls do not work / are choppy:

There is a known bug on Mac where the controls will not work as intended. This appears to be caused by the KeyListener class, but may still affect the updated system from 1.0.2. In this case, you will want to open the Terminal and copy/paste the following command as a workaround:

defaults write -g ApplePressAndHoldEnabled -bool false

Note that this will disable holding to access accented keys. If you want to undo this, input the following:

defaults write -g ApplePressAndHoldEnabled -bool true

** What's a .DS_Store?

The game was packaged on mac, which adds invisible files (on Mac, at least) called .DS_Store. It doesn't impact gameplay in any way and you are free to delete it.

** If the game lags in fullscreen / high aspect ratios:

Large aspect ratios increase the amount of updated objects in the level, while fullscreen scales the image output to fill the screen. Both are relatively expensive, so if they cause lag, try turning them off / reducing them for a bit.

== CREDITS ==

Qw2 - Producer

-- Artwork --

Nintendo
Super Mario Odyssey Staff
Random Talking Bush - Various sprites
Flourescent - New Super Mario Bros. sprites
Fleepa - Super Mario Bros. 3 sprites
SuperJustinBros - Super Mario Bros. 3 sprites
jdaster64 - Super Mario Bros. Deluxe sprites
Mr.C - Effect sprites
Blitz Lunar - Super Mario World Soundfont
Treeki - New Super Mario Bros. sprites
Ridge Troopa - Bowser Sprites
nicetas_c - Super Mario Bros. 3 Instruments
Deezer - Super Mario Bros. 3 Sound Effects
Cooper B. Chance - Mario Kart 64 Sound Effects
LukeWarnut - Super Mario 3D World Sound Effects
jazzmunch - Moon Picture

-- Utilities --

Snakemeat
NWPlayer123
aboood40091
SimonMKWii
SciresM
Finn Kuusisto

-- Special Thanks --

The VG Resource
Super Mario Bros. 3 Staff
Super Mario Maker Staff
Super Mario Maker 2 Staff
New Super Mario Bros. Staff
Mario Kart 64 Staff
Super Smash Bros. Ultimate Staff

All rights belong to their original owners.
The producer of this game is not contractually
bound, paid, or affiliated with any companies 
whose intellectual property is detailed in this work.
Characters and concepts copyright Nintendo.
