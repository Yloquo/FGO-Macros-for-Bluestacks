# FGO-Macros-for-Bluestacks

---

I made Bluestacks macros for EXP feeding, Skill Uping, CE Merging, and mass ascensions. They can handle a bit of lag as well.
This is because FGO is not designed to handle high volumes of action, but thanks to FGA, we can lotto forever. 
But it's kinda a pain to clean up, so here we are. Automating even the minor actions.

---
How to use:

!!!You're using BlueStacks!!!

!!!You can't just put the macros in the macro folder!!! I did that and it didn't work. 

Therefore, we need to import them through the Bluestacks Macros UI.

Also importing doesn't work if the macros are in the macro folder. I did that as well and it also doesn't work. 
(Feel free to try them, though. It's not going to ruin everything forever.)


In Bluestacks Macro recorder (shortcut: Ctrl+Shift+7) icon weird clipboard with a play icon, found under ... icon, 
click the import icon (on the same horizontal line as "Record new macro", square with the arrow pointing down).
Go to wherever you've put the macros, and select them. 

Hit the play icon under action that lines up to the correct macro. The settings are to the right of that, and Skill Up is best used with that icon.
They should run indefinitely (except for skill up, which works best if it doesn't), but if not, go check that box.


---

Overview:

1-Dude EXP: Feeds EXP to the selected servant. No need to worry about feeding inefficiently.

All Dudes EXP: Feeds EXP to all servants in an unequal manner (See How they work for more details). 
Best used if you don't care too much for where EXP goes. 
It WILL feed EXP to randos, like your dupe Sthenos, so make sure that they are in second archive or burnt.

Skill Up: It skills up a skill one time. Doing it multiple times can be achieved through toggling the Bluestack settings or
performing the macro multiple times (Or both). 

CE Merging: It feeds EXP to a CE. It makes a CE bomb, but it isn't a 100% efficient CE Bomb process. 
If you're really worried about QP efficiency, don't use this. Otherwise, you're good.
This is affected by lag spikes, but it'll probably make the process miss a cycle. It won't fail spectacularly. 
It'll also hang up if you're trying to feed a CE that's equipped.

Mass Ascension: It ascends all servants that can be ascended, except for the for displayed servant. Since servants talk to you while ascending, there is a lot of waiting between ascending and going to the next servant.

----

Setup 
1-Dude EXP: 
Have set a servant to feed EXP to.
Currently on selecting EXP screen.
Make sure Auto-EXP select is set properly. 


All Dudes EXP:  
Make sure Filters for Auto-EXP and Servant select are set properly. 
Servant select screen is set to smallest (out of the three sizes in the bottom-left). 
Currently on selecting EXP screen.
For efficiency's sake, have at least 2 servants to enhance. Otherwise, just use the 1-dude.
Make sure that servants you don't want to feed are in second archive or burnt.


Skill Up: 
Set in the Bluestack macro settings how many times you want to skill up. Initialized at 1 time.
Currently in the skill up screen with the skill you want to up selected.

CE Merging: 
Have set a CE to feed EXP to. This will not manually limit break your CE, so you should LB it first.
CE select screen is set to largest (out of the three sizes in the bottom-left). I think it can work with smaller sizes, though.
Equipped CEs will make the process hang, so if you have random low-level CEs equipped, unequip them.
If there's no more stomach, the process will hang on the select a servant screen. 

!!! You've set the filters so the CEs you want to feed are on the top on the CE select screen and
you're absolutely sure you've protected any CEs you don't want to mulch! 
This doesn't go too far on the CE select screen (About 7 lines), but for safety, lock your CEs!!! 


Mass Ascension: 
Have at least 2 servants to ascend.
Servant select screen is set to lowest, and filters are configured properly.


----

How they work:

1-Dude: It feeds EXP to the selected servant.

All Dudes: It selects the second servant in the select screen, then feeds EXP to that servant. Repeat. 
The results are that the first two servants in the select screen get fed first, then moves on to the next two 
(or vaguely a 2-1 2-1... 2-3 2-3 4-3 4-3 4-3... [n] [n-1] feed order ). 
If it selects a full servant, it just misses a cycle, but won't fail spectacularly.

For both, there’s no need to worry about failing, if there’s no more exp cards, it will hang on the “There’s no more EXP” box, 
and if there’s no more stomach for exp, it will hang on the exp select screen. 

Skill up: It skills up the skill for n times, where n is the number set in settings. Note that repeat once means running one time,
and repeating 0 times means 0 times, since 1 run * 0 times = 0.

CE Merging: It opens the CE to mulch screen, scrolls down about 7 lines to select the CEs, and feeds to the selected CE. 
This it will eventually eat CEs you want to keep, so you need to lock that much CEs to ensure the safety of your box.
The macro won't unlock your CEs.

Mass Ascension: It selects the second servant, because the entire hitbox which chooses the first servant in the servant select screen is overlapped by the "choose a servant" hitbox in the ascension screen. Because of this, it's more useful the less you want to ascend the first servant. 

---

Final notes:
DM, email, or Git@ me if there's something wrong, or cool you've done with it. Or if you want to hang out. I'm not that "visible" online, but I lurk a lot.

Thanks to:
The maker(s) of Fate Grand Automata. Without your work, there wouldn't even be a realization that this is necessary.
Bluestacks. For accepting automation on your servers.
All the pals in the goon discords. I <3 all of you guys and your ramblings.



Copyright: LXP @ the SA forums and Fate Goon/Order Discord. 

This is free for everyone.
You can build on these macros, but credit me, and usage in a for-profit product is no go, though Patreon and Patreon-like transactions are okay.
