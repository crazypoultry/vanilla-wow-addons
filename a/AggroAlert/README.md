

# AggroAlert
### v 1.5
By Sathanas of Khadgar

Creates a movable frame that will display the target's target (if any), and allow for 
visible warning on player gaining aggro.

To move the AggroAlert bubble, use Shift+Left Button and drag it to a new position.

Clicking on the AggroAlert bubble will target the unit named in the bubble

#### v 1.5 Changes:

Updated TOC for 1.7 patch.

Added an option in the /agg warning command to disable all text warnings.


#### v 1.4 Changes:

Removed buggy call command. Seeing a pattern here?

Background of the AggroAlert bubble is now a healthbar for the named unit in the bubble.


#### v 1.3 Changes:

Ditched the buggy spell alert that was in 1.3 beta. It sucked. 

Added Healer Mode, the bubble will display "- Tank" or "- Idle" when targetting an ally, showing whether their target is currently aggrod on them (i.e. the ally is tanking) or not. 

Also added the new command "/agg call" which turns on automatic announcment of targets target changes in the appropriate channel. When your target changes targets (i.e. the main tank loses aggro) AggroAlert will broadcast a message to the channel, example "Target Change! Onyxia is now engaged on SomeDumbGuy!", this alert disables itself when you change targets or exit combat, and must be turned on individually each time with "/agg call", this is done mainly since this is a very situational feature.


#### v 1.2 Changes:
Slash commands have changed, use "/agg mode" to toggle modes, and "/agg warning" to toggle between the original smaller warning, and a new gigantic one. Hopefully fixed all the errors caused by stun/sap/poly etc


#### v 1.1 Changes:
AggroAlert now uses the slash command /aggroalert or /agg to toggle between 2 modes: 

DPS Mode will alert you visibly on screen when the targetted unit targets onto you (You pulled aggro) 

Tank Mode will alert you when the targeted unit CEASES targetting on you (Someone else pulled aggro)
