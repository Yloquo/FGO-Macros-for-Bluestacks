What this is:
A macro for Bluestacks and other Android Emulators to automate giving EXP to all servants in FGO.
Specifically, it'll give to the second and third slots, which slowly move down as they become EXP capped.


Contents:
1. EXP All pals: A macro which gives EXP to all servants.
Is a merged macro consisting of:
GOTO select servant, Select the second servant, Select the Third Servant, and Auto EXP.

2: Auto EXP 1 Pal: Automates the enhancing process. Presses Auto EXP, OK, Enhance, then OK.

3: GOTO select servant: Taps the screen in a location to swap from "Enhancement" to "Servant Selection" screen.

4: Select the second servant: Taps the screen in the location to select the second servant (horizontally beginning from left.)
Only tested for max (lv 3) zoom out.

5: Select the third servant: Same but for the third servant
Also only tested for max (lv 3) zoom out.



Required:
1: You are on the enhancement screen. NOT the servant select screen.
2: On the servant selection screen, you have the following filters:
All. Not Level Max. Level, Ascending. Smart Sort On. Otherwise you could have incorrectly selected servants.
3: Also, you are on Max (Lv 3) zoom out.
4: I think? As few party members in party as possible? 
I think it's fine but party members are given +1 priority in the EXP line.
I don't exactly have the grails to spare, since I did this a long time ago.

5: In the Enhancement screen, you've set your auto exp settings to your liking.

6: Done.

How to install:
1. Download these files.
2. Some android emulators have an import macro function, in the macro screen. Use that and import all four macros.
3. Check the macro settings to see if they are to your liking.
4. Optional: you may inspect the macros themselves in a text editor to change up the screen tapping.
5. Make sure the servant selection filters and auto exp settings are correct as described in required.
6. Finished!

How this macro works:
First, this macro taps a part of the screen which is guaranteed to move to the servant select screen and not select any servants.
Then it presses the space for the second servant card. It does so twice but fast enough so the second tap won't be registered. This is to decrease the odds lag stops the macro from actually selecting.
Then it taps the space for Auto exp, Enhance, and presses through the Enhancing process.
Then it repeat the above, but for the third servant card.
I believe Level Ascending is the setting to ensure you don't double select a servant, since the lowest second and third servants are in slots two and three.
This makes it so that usually, after leveling, a servant's level is high enough it's not the third or third lowest.

Warnings
This will give EXP to all your servants, from lowest to highest. Make sure anyone you don't want to give EXP to safely tucked away. 
This only works with 3+ servants. Also note that the lowest level servant never gets touched. 

Software specifications

Made with MSI player.
Display size: 1600 x 900
OS: Windows
Android player lag: Low, about 10ms?
