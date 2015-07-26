BATTLE ARENA BOT Fork - Zombie Madness Mod
--------------

## ABOUT

Zombie Madness Mod is a text game based on the popular Battle Arena Bot. This mod is under construction and in it's early stages but will be created for the entertainment of a Newsgroup Network in Canada which will allow localized game play. Where Battle Arena Bot is designed to work in one channel one monster at a time I hope with time it can be altered to allow mutiple monsters in mutiple channels, each channel will be for each city within this province. There is much work to be done though.

Battle Areana Original wiki guide (We will generate our own guide with time as features are dropped and added)

A full in-depth guide with commands and more in-depth information can be found on the Battle Arena wiki:  http://battlearena.heliohost.org/doku.php?id=start


## SETUP

Getting it set up is easy assuming you unpack the zip in a good location on your computer.

 1. Do a CLEAN install to C:\BattleArena\  with the complete zip package of the bot (either from this repository or from my website).
 2. Patch the bot to the latest versions if there are any patches. Don't skip versions unless I specifically say it's all right.  ALSO NOTE: DO NOT HAVE THE BOT RUNNING WHEN YOU APPLY PATCHES!
 3. Run the mirc.exe included with Complete Package.
 4. The bot will attempt to help you get things set up.  Set the bot owner's nick and the IRC channel you wish to game in.  Be sure to set a password for the bot that you'll register to nickserv with.
 5. (as with all mIRC programs) change the nickname and add a server
 6. Connect.
 7. Using another IRC connection as the bot owner's nick, use !new char (nick) without the () to get the character creation process started.
 8. Follow what the bot tells you to do.  Be sure to check out player_guide.txt as well.

Note, you do NOT have to install it to C:\BattleArena\ However, it's recommended.

   
## WHAT'S NEW?

If you have used this bot before and are updating you may be wondering what all has changed.  Well, the versions.txt in the documentation folder has a full list of changes. Listed below are some of the main highlights since version 2.5 complete. 

ADDITIONS:
* New Method of Doing Monster/Summon/NPC Stats Upon Summoning to Battlefield 
* Added a new battle type: Defend Outpost
* Added a new battle type: Assault
* Added Capacity and Enhancement Points. 
* Added the ability for monsters and npcs to be able to use battle items.
* Added NPC Trust Items
* Added new battlefield limitations
* Added new bot admin commands
* Added new system settings
* Added potion effects that players can purchase and use
* Added the Spirit of the Hero buff to help lower level players fight in higher levels

CHANGES:
* Changed the !augment commands to work in private or channel. 
* Changed the portal battles so that they have a level cap. 
* Changed the shop to allow players to view and buy techniques that are on the left-hand weapon.
* Changed the drops in the bot
* Changed the lockpicking skill to be 3% per level, up from 2%.
* Changed Evil Doppelgangers so that they are generated correctly if the user is level synced.
* Changed chests so that red chests can never spawn mimics.
* Changed the GIVES command so that players can now give red orbs to certain NPCs.  
* Changed the way the bot picks NPCs to have more settings like bosses/monsters
* Changed the scoreboard.html to include the level of the player
* Changed the drunk status to last 2 rounds
* Changed the GIVES message to hopefully show grammatically correct lines
* Changed the way the bot handles negative status effects on targets.
* Changed the way the bot does all of the status timers to make it consistent
* Changed the modifier checks so that they will also check for weapon names
* Changed the way the bot displays damage (purple = resisted, orange = enhanced)
* Changed the way the bot displays the "battle open" message 
* Changed the chance of a rescue allied president battle to 25% and lowered the streak from 100 to 20. 
* Changed how the allied forces president is generated slightly (stat-wise)
* Changed the chance of certain special boss types of occurring by a small amount.
* Changed the way the bot boosts portal monsters, hopefully keeping them closer to the synced levels
* Changed the way the bot does the stats for monsters, npcs and summons upon summoning to the battlefield.
* Changed the way the HP for monsters/summons/NPCs/bosses are boosted at the start of battle
* Changed demon portals so that monsters spawning out of them will be slightly less than the battle streak.
* Changed the code to allow partial target name matches on attacks and techs. 
* Changed the way players purchase stats; they must be kept somewhat close to each other now.

FIXES:
* Fixed an issue with songs showing resists on targets who shouldn't be affected by the song to begin with.
* Fixed an issue with counter attacks showing the wrong pronouns sometimes.
* Fixed an issue with lost souls appearing in gauntlet battles.
* Fixed an issue where instruments could be used with !use
* Fixed an issue with the mech shop so that cores and weapons that cost 0 won't show up for purchase.
* Fixed an issue with the snatch error message showing the wrong name
* Fixed an issue with monsters being unable to take action while charmed.
* Fixed an issue with techniques doing too much damage when a player was level synced.
* Fixed an issue in which Ghost Turkey could show up in other months besides November
* Fixed an issue with !view-info style doppelganger getting cut off
* Fixed an issue with the bot not checking left-handed weapons for augments
* Fixed a bug with !augment list that would say players had no augments even if they did.
* Fixed a bug with !fullbring when used with +TP items.
* Fixed a bug in which Inactive monsters would attack even while inactive if they went first in battle
* Fixed a bug with the drunk status effect
* Fixed a bug with !augments list not showing in private even if the command was used in private
* Fixed a bug with !unequip armor
* Fixed a bug with shadow clones attacking their owners in PVP mode
* Fixed a bug with shadow clones attacking themselves in PVP mode
* Fixed a bug with items occasionally not showing damage correctly 
* Fixed a bug in which players could trade armor they were still wearing
* Fixed multiple typos and errors found in weapons.db/items.db/techniques.db (courtesy of Andrio)

REMOVALS:
* Removed the following monsters: Final_Guard, Prime_Vise, Excenmille, NajaSalaheem, Wind-UpShantotto
* Removed the following NPCs: Nauthima
* Removed the following bosses: Adlanna, Eldora, EldoraAdlanna, NauthimaTiranadel, RuneFencer_Nauthima
* Removed Battle Formulas 1 & 2. The bot now only has 1 battle formula
* Removed the !toggle battle formula bot admin command
* Removed the bot setting the user levels of bot owner/admins upon starting to prevent a security hole

Again, this IS NOT everything. Be sure to read the versions.txt in the documentation folder for a full list of everything as the list is quite extensive.


## THANKS

These are people who have helped me by helping me test, making monsters/weapons/etc, finding bugs, or just by giving me some ideas.  This bot would not as good/far along as it is without these fine folks.

* Scott "Smz" of Esper.net
* Andrio of Esper.net
* AuXFire of Hawkee
* Raiden of Esper.net
* Sealdrenxia of Twitter
* Rei_Hunter of Esper.net
* Trunks of Esper.net
* Roy of Esper.net
* Wims of mIRC's official forum
* W3TPantsu of Esper.net
* Pangaea from my forum
* Anthrax from my forum
* Karman from my forum
