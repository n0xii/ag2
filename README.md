# Adrenaline Gamer 2  version 1.0.2
License Agreement
-----------------
IN NO EVENT WHATSOEVER SHALL THE Adrenaline Gamer 2 DEVELOPMENT TEAM  BE LIABLE FOR 
ANY DAMAGES WHATSOEVER (INCLUDING, WITHOUT LIMITATION, DIRECT OR INDIRECT 
DAMAGES, DAMAGES FOR LOSS OF PROFITS, BUSINESS INTERRUPTION, LOSS OF 
INFORMATION) RESULTING FROM THE USE OR INABILITY TO USE THE PROGRAMS AND 
FILES EVEN IF THE Adrenaline Gamer 2 DEVELOPMENT TEAM HAS BEEN ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGES. Without limiting the generality of the 
foregoing, no warranty is made that the enclosed software will do anything 
you want it to, or be error free. USING THIS SOFTWARE IMPLIES AGREEMENT TO 
THESE TERMS.
This version of Adrenaline Gamer 2 Mod is provided free of charge and may be freely 
downloaded and redistributed under the condition that all files in the 
original distribution remain in the distribution and that all redistribution 
sites must inform (in the form of a hypertext link, etc.) users of the 
original place of distribution. No person or group shall profit from the 
redistribution of this software in any form without the consent of the 
Adrenaline Gamer 2 development team.
In other words, do not put this program onto a CD containing 
shareware/freeware programs that will be sold without first consulting the 
HL2DM Pro development team.


Installation
------------
1. move the folder "ag2" into Steam/steamapps/sourcemods
2. restart Steam
3. ag2 should now be in your library

User's Guide
------------
Please refer to the following url: http://www.adrenalinegamer2.com/index.php?site=articles&action=show&articlesID=10


Contributors
------------
Core Development Team:
	- J@nek : Lead Coder
	- RATICIDE : Coder

Official Mappers:
	- aRm : pg_sacred, pg_broken, pg_fragging_yard, pg_the_longestday, pg_stalkx (remake of original one)
	- keved : pg_boot_camp, pg_np_refinery_b5
	- boshed aka Zaxx : pg_datacore (and few models : gauss ammo, longjump, bases for flags, textures of egon), pg_stadium
	- Sadist : pg_catmouse

Intro movie maker:
	- RATICIDE (Adrenaline Gamer 2)
	- netrex (HL2 DM Pro)

Splashscreen maker:
	- Valve : HL2DM mousemat by Valve
	- Intro screen : by WonkaStudio http://www.wks.fr

Official Beta Test team:
	- keefy
	- boshed aka Zaxx
	- Rav

Mappers who have maps in the installation packages:
	- aRm : pg_sacred, pg_the_longest_day, pg_fragging_yard, pg_stalkx
	- keved : pg_boot_camp
	- boshed : pg_datacore, remake of pg_stadium
	- Sadist : pg_catmouse
	- The Dog : pg_collapse
	- <FENIX> : pg_winterchill
	- penE : pg_crossfire_final
	- s0cke : pg_deck17
	- Swot : pg_lostarena
	- Pincus : pg_bloodrun
	- Finger : pg_icepick
	- [m.x] : pg_campgrounds
	- Electric Warrior : pg_roman_sanctuary
	- =EUV=asylum : pg_stalkyard
	- StickFigs : pg_stadium
	- Valve : pg_lockdown
	- ? : pg_lostvillage

Special credits:
	- nyukdesign : splashscreen from v1.1
	- skaruts (Lich): for egon model and soccer ball model
	- The Dog: deep help in doing SDK for mappers (refer to sdk folder in ag2)
	- PimP (HL2DMA): for sharing his gauss gun code
	- Expert and Rokstanski: tuning gameplay
	- Erozbey from AGMerkezy community for providing gauss model (and of course which did this model)

Sponsors:
	- VeryGames : http://www.verygames.net (Developpers's server)
	- Webspell CMS : http://cms.webspell.org (CMS)
	- AGmerkezi: http://www.agmerkezi.com (tuning gameplay in 1.9.3)

Beta testers for previous versions:
	- bi0_gauss (till version 1.3)
	- M|k33 (till version 1.5)
	- noodle (till version 1.5.1)
	- Rijuu (till 1.9.4)
	- Nilsson (till 1.7)
	- raz!el (till 1.8)
	- aeLiXiR (till 1.9.4)
	- pille (till 1.7)
	- s0cke (till 1.9.4)
	- mAgu (till 1.7)


ChangeLogs (dates are dd/mm/yyyy)
---------------------------------:
Version AG2 1.02 : 07/07/2010
. Added : in teamplay game mods, HUD is getting color of your team (can be prevented in Advanced Player menu)
. Added : music in main menu
. Added : map pg_collapse by The Dog
. Added : ability to control opacity of font based xhair and quick info in Player menu (F12->Advanced)
. Added : Music Control Center is now supporting Windows Media Player in addition to WinAmp 
. Changed : each player can now decide which netcode he wants to use by checking box in Player menu (F12->Advanced). It means that even in a same server, you can have players using valve netcode (if they feel better with it) and others using an alternative netcode that we did.
. Changed : in teamplay game mods, trail effect of hand grenade is using color of your team (even in Vanilla)
. Changed : "in-eye death" set to off by default
. Changed : orb ammo model is now the same as HL2DM 
. Changed : sv_friction was not appearing in cvar list
. Changed : generated demo name are using following format: YYYYMMDD-HHMMSS-mapname.dem
. Changed : hidehud 9 is now hiding inventory, team name, radar, remaining time, scores
. Fixed : fix a bug impacting fps
. Fixed : For Russian Cyrillic support copy/paste content of ag\resource\russian\resource in ag2\resource
. Fixed : "tunnel-bug" exploit restored
. Fixed : maps including very long entity description were not managed properly
. Fixed : "game_player_equip" was ignored
. Fixed : team spawnpoints were treated as non team spawnpoints
. Fixed : crossbow effect was not properly positioned
. Fixed : Jesus pose when player had no weapons
 
Version AG2 1.01 : 26/04/2010
. Added : new map pg_catmouse done by Sadist
. Added : cvars pg_sv_add_gauss and pg_sv_add_longjump to dynamically add this item/weapon/ammo in maps which don't contain them. Set to "0" by default meaning they are not added. A reload of the map is required if set in-game
. Added : blood splash effect when really hitting an opponent (could be deactivated in Advanced player menu. Please note it is working only with enhanced netcode)
. Added : bases are now displayed in radar for CTF, CTFArcade, Football, Warball
. Added : arrows to indicate directions to get flags/balls are displayed for game mods CTF, CTFArcade, Footbal, Warball and Domination
. Added : arrow to indicate direction to find fugitive is displayed in HUD in Fugitive game mod
. Added : detail.vbsp
. Added : server settings are now included in .dem files so that you don't have to start a listenserver using correct settings (especially for gameplay even custom gameplay you don't have in your computer) before using "playdemo"
. Changed : mp_forcecamera set to "0" by default (0:view all, 1: spectate team mates only)
. Changed : bots are automatically removed when no real players (humans) are present in the server (green computing by using less CPU)
. Changed : rpg missile can be fire when RPG is fully deployed (same behaviour as in regular hl2dm for any gameplay)
. Changed : new ag2.fgd in folder sdk for mappers
. Fixed : pg_sv_bot_stopifrealplayers was specified 2 times in server.cfg
. Fixed : missing pg_sv_bot_skill in server.cfg
. Fixed : descriptions of cvars related to IRC have been updated
. Fixed : descriptions of game modes reviewed to take care of number of grenades which is dependent on gameplay
. Fixed : compliant with maps having names longer than 28 characters
. Fixed : rcbotd command could crash listenserver
. Fixed : shotgun was pumping on deploy in certain conditions
. Fixed : no more take into account in stats players who don't fire anything
. Fixed : constrained weapons were not attaching properly to player models
. Fixed : gravity modifier not reset properly in case you're killed while in a gravity modifier
. Fixed : fixed jittery animation for .357 and pistol
. Fixed : auto-assign to team was not working 100% properly
. Fixed : simultaneous death was not displaying correct weapon for the second notice in death notice
. Fixed : .357 reset view bug fixed
. Fixed : server crashing randomly
. Fixed : Jesus pose in some conditions
. Fixed : unability to get flag in CTF, CTFARcade if object in gravgun or opponent flag in your back
. Fixed : infinite ammo shotgun exploit
. Fixed : server crash caused by npc_zombie
. Fixed : satchel was not causing damage when fired by a weapon

Version AG2 1.0 : 16/01/2010
. Added : ag2.fgd in folder sdk for mappers
. Added : pure_server_whitelist.txt to use sv_pure 1
. Added : compliant with hl1dms maps
. Changed : new egon model by skaruts and textured by Boshed
. Changed : new gauss model
. Changed : new soccer ball model by skaruts
. Changed : mod is renamed Adrenaline Gamer 2
. Changed : use of Orange Box engine instead of Ep1 engine
. Changed : new gauss ammo model by Boshed
. Changed : new long jump model by Boshed
. Changed : new pg_stadium by Boshed
. Changed : new pg_datacore adapted to OB engine by Boshed
. Changed : new desktop icon by Boshed
. Changed : new splashscreen
. Changed : new intro movie 
. Changed : Hurricane Bots (http://www.hurrikhan.net) replaced by RCBot2 (http://rcbot.bots-united.com/) for OB engine compatibility in which we added following features:
	- skill level to tune bots skill
	- dynamic waypoint generation so that bots can be active in any maps even maps without predefined waypoints file
	- look at server.cfg or listenserver.cfg to understand how to use cvar related to bots
. Changed : your name can be different than the one for steam friends by setting it in "Advanced" player menu
. Changed : "stealing missile" is now a votabled option which is "off" by default
. Fixed : Jittery movement in certain conditions
. Fixed : demo recording was not smooth
. Fixed : optimizing our own netcode
. Fixed : cl_autowepswitch is now working and has been added in "Advanced" player menu
. Fixed : ability to get frag and slam even if weapon_stay set to 1
. Fixed : slow bolt when firing close to satchel
. Fixed : invisible beam for tripmine in certain condition
. Fixed : ability to throw slam through wall in certain condition
. Fixed : tripmine could be attached in invisible element
. Fixed : no gravgun holding sound in case graving an object using double tap 
. Fixed : rpg round, bolt and smg1 nades were stopped by invisible elements in spawn points
. Fixed : infinite shotgun reload animation in certain circonstances

Version HL2DMPro 1.9.4 : 03/06/2009
. Changed : "Enhanced Hitreg" rewritten for better efficiency and reliability
. Changed : minor changes in pg_winterchill 
. Changed : when choosing "auto-assign" and teams have same number of players, team is choosen randomly
. Fixed : slam was not displayed in inventory
. Fixed : spam ratio in scoreboard was not properly computed

Version HL2DMPro 1.9.3 : 13/04/2009
. Added : option "Disable countdown sound" added in "Player's Advanced" panel
. Added : chat box ala Regular hl2dm
. Added : promod version is automatically displayed in server name in servers list if not specified
. Added : additional font crosshairs
. Added : options "additive" and "outline" for font crosshairs
. Added : ability to select "silent jump" or not when doing a custom gameplay
. Added : map from <FENIX> pg_winterchill 
. Changed : standard hl2dm ladders are working like in regular hl2dm (no change for textured ladders)
. Changed : spread reviewed in "Pro" gameplay for smg1, ar2, shotgun, .357 
. Changed : in Pro gameplay, splash damage are impacting movement of players in a specific radius
. Changed : hitsounds less loud for non-instant weapons
. Changed : ability to steal opponent rpg using your own red dot (unavailable in regular hl2dm gameplay)
. Fixed : during a match, a player who was disconnecting and coming back was displayed 2 times in scoreboard
. Fixed : explosive physics were immediately explosive after a first launch
. Fixed : spread was not properly managed in 1.9.2
. Fixed : explosive barrels were not explosing all the time when launched
. Fixed : "unconnected" player procedure prevented
. Fixed : netcode optimized for high ping
. Fixed : target player name not displayed if you are this player or spectating him
. Fixed : removing hand grenades before starting a round

Version HL2DMPro 1.9.2 : 22/12/2008
. Changed : netcode partially rewritten for a better hit registration (Valve's netcode can be use by unchecking "Enhanced HitReg" in admin panel)
. Changed : lower egon sound
. Fixed : wall gauss could cause explosion in the bad side (occured only in pg_crossfire_final)
. Fixed : "pause" command from Valve is now rerouted to "pause" management of HL2DM Pro
. Fixed : "Allow" is writing name of the player without color code in name
. Fixed : wall jump was possible by looking at floor even if there had no wall near you
. Fixed : pg_stalkx was not including balls and flags

Version HL2DMPro 1.9.1 : 29/11/2008
. Changed : "Admin command" is specifying name of the requester when identification is possible
. Changed : no more punch effect within gauss attack2
. Changed : gauss penetration distance reduced from 32 units to 21 units to make it harder to fire through wall and corners
. Changed : pg_lockdown (Valve) back to installation package
. Changed : egon in pg_lostarena and pg_fragging_yard
. Fixed : Tau cannon attack1 no more available in game mod "Instant Gib"
. Fixed : Scoreboard was remembering players who quit in previous war
. Fixed : Change team was not working properly
. Fixed : Constraint items were falling down each first spawn after getting them
. Fixed : Gauss and Egon sound management reviewed
. Fixed : Gauss behavior reviewed to be like in 1.8.3 (effect management remains the same as in 1.9)
. Fixed : Egon effect was staying when use of attack2
. Fixed : Gauss was called Egon in selection menu for German version

Version HL2DMPro 1.9 : 10/11/2008
. Added : new weapon Egon (aka Gluon gun). Active in  FFA, TDM, CTF, Domination, Warball
. Added : new game mod Last Man Standing
. Added : pg_datacore by boshed from [S-UK]
. Added : pg_crossfire_final by penE
. Added : pg_lostvillage
. Added : pg_frenzy by sw0t
. Changed : gauss gun modified for a better registration and better effects
. Changed : in TDM, CTF, CTFArcade, Domination, Warball, changing of team will cause a suicide
. Changed : during countdown it is no more possible to fire (except Attack2 of gauss gun)
. Changed : removing following maps from installation package --> pg_broken (aRm), pg_biohazard (sw0t), pg_grand_pyramids (TigerStyle), pg_lockdown (Valve), pg_overwatch (Valve), pg_scepter (ThinkCircle)
. Fixed : team color changed not taken into account in all situation
. Fixed : vertical jump pads behavior could have trouble depending on the server (not jumping high enough)
. Fixed : preventing keeping acquired weapons when changing of team
. Fixed : preventing team changing when choosing same team
. Fixed : in "Original HL2MP" there had no reserve when getting shotgun or pistol. In "Pro" or "Custom" it remains the same (No reserve for this two weapons due to the fact it makes "dropping weapon" working bad).

Version HL2DMPro 1.8.3 : 25/06/2008
. Added : native support of maps of "Fisful of Frags"
. Fixed : when starting a server in "Original HL2MP", entities reserved to "Pro" gameplay (long jump, gauss) were present
. Fixed : invisible "suicide" icon
. Fixed : in "Original HL2MP" we shouldn't hear stepsounds when practicing ducked bunny hopping
. Fixed : weapon deployment animation not played when spawning
. Fixed : server was unstable while running Fugitive game mod
. Fixed : in Arena, Instant Gib, Tourney and Football, entities like doors, jump pads... could not work properly

Version HL2DMPro 1.8.2 : 
. Added : cvar pg_sv_ctf_roundbased to play CTF game mods with or without rounds
. Added : cvar pg_sv_reg_padsreactive and pg_sv_reg_padsreactive_admin to define if pads must be reactive or not in "Original HL2MP" gameplay
. Changed : server settings file are now taking care of this 3 new cvar
. Fixed : bug with blue flag
. Fixed : a user with ID_PENDING could be able to join a match without having been allowed
. Fixed : IRC bug related to private message

Version HL2DMPro 1.8.1 : 31/01/2008
. Added : "Server Settings" management to apply a set of settings via "Command Menu". Standard settings for CAL, Clans-United and DM-Warzone are included.
. Added : map from aRm pg_the_longest_day
. Added : map from Electric Warrior pg_roman_sanctuary
. Added : map from Swot pg_lostarena
. Added : CCTP support for built-in IRC
. Added : listenserver.cfg file 
. Added : "autoconnect" checkbox in IRC settings to automatically connect to IRC while joining a server
. Added : spray hl2dmpro logo done by -=D$=-
. Added : cvar pg_cl_netautoconf (Advanced player menu) to dynamically set cl_updaterate, cl_cmdrate and cl_interp regarding tickrate of server you're connected to
. Added : floating rotating spawn weapons by setting "Start constrained" flag for weapon when doing map in Hammer
. Added : floating items by setting "Start constrained" flag for items when doing map in Hammer
. Added : cvar pg_sv_pausewithoutvote to allow a player performing a "Pause" without doing a vote
. Added : cvar pg_sv_overtime to specify an amount of minutes for an overtime in case of a draw during a match. No overtime if set to 0.
. Added : cvar for mappers to tune pads realtime in-game : pg_pad_tuning, pg_pad_x, pg_pad_y, pg_pad_z, pg_pad_ax, pg_pad_ay, pg_pad_s. Refer to our guide section to see how to use them.
. Changed : new version of pg_armageddon also renamed pg_fragging_yard
. Changed : pg_campgrounds --> fixed "start constrained" entities
. Changed : "Match" written in server list if a match is on air in the server
. Changed : Fugitive on top of scoreboard in Fugitive mod
. Changed : tripmine, satchels and dropped weapons are removed from battle field when starting a new round in Arena, Tourney, LTS, CTF, CTF Arcade and Warball
. Changed : ability to put flag on your back in CTF and CTFArcade game mods (use "reload" when you have gravgun)
. Changed : mp_falldamage can be used in 4 ways : 0=10 damage, 1=realistic damage, <0=0 damage, >1=fixed amount of damage
. Fixed : "Half-Life 2 DM Pro" is now displayed when a friend is joining a "HL² DM Pro" server (instead of Half-Life 2: Deathmatch)
. Fixed : MountSteamContent error message
. Fixed : command menu width for high resolution
. Fixed : server crashed sometimes in Fugitive mod
. Fixed : missing sounds for Orb
. Fixed : when starting "Fugitive", everybody was "Winner"
. Fixed : no hitsound in Arena/Tourney/LTS when spectating but not in spectator team
. Fixed : pg_sv_reg_materialstepsounds had no impact when set in server.cfg
. Fixed : server.cfg, game.cfg file were containing bad ConVar statement
. Fixed : bad gauss sound when releasing attack2
. Fixed : InstaGib no more change current weapon of killer
. Fixed : black screen in Arena/Tourney/LTS when fall dying
. Fixed : ability to play 1o1o1 in  Tourney not more possible
. Fixed : server crash when a match was started and a player was joining the server
. Fixed : default web browser page set to www.hl2dmpro.com
. Fixed : LTS sometimes doesn't detect team victory
. Fixed : playdemo was displaying bad text
. Fixed : 1 handgrenade at spawn for "Regular HL2MP" instead of 2
. Fixed : items could respawn at (0,0,0)
. Fixed : sometimes weapon handled disappeared
. Fixed : ability to hold an object while in observer mode in very specific case
. Fixed : weapons were not spawning in LTS
. Fixed : in Football gamemod, ball was not falling down when a player was receiving damage by physcannon and player's health was impacted by fall and physcannon attacks.
. Fixed : crowbar speed to slow in Regular hl2mp
. Fixed : jump pads were not working properly
. Fixed : combine ball selfkill : sometimes ball kills launcher when he was firing it
. Fixed : silent jump while ducked bunny hopping
. Fixed : pg_stalkx main field allowing groundgauss nuke
. Fixed : additional spawnpoints in pg_sacred to avoid respawn kill in LTS
. Fixed : multi-decals could be seen while performing a attack2 with gauss gun
. Fixed : quickinfo ammo warning was not refreshed properly

Version HL2DMPro 1.8 : 19/10/2007
. Added : "Gameplay SDK" which allows you to create your own gameplay (speeds, weapons damage, spread, brightskins, zoom...)
. Added : WinAmp Control Center
. Added : IRC (Internet Relay Chat) client
. Added : Web browser
. Added : easy management of maps from external mods (like CS, DODS, HL2CTF...)
. Added : map cycle GUI for administrators
. Added : game mod "Tourney"
. Added : game mod "The Fugitive"
. Added : round statistics
. Added : radar (optional in Original HL2MP)
. Added : 2 minutes overtime in case of a draw at the end of time of a match
. Added : speech icon when a player is speaking in game, in IRC or is browsing the web
. Added : ability to use textured ladder (so that you can create climbable walls for example). It makes maps based on textured ladders (like css maps) also working properly
. Added : step sounds depending on material
. Added : map pg_sacred by aRm
. Added : map pg_broken by aRm
. Added : map pg_armageddon by aRm
. Added : map pg_deck17 by s0cke
. Added : map pg_bloodrun by Pincus 
. Added : colors for name/message can now be choosen using $rgb where r=red, g=green, b=blue with a value going from 0 to F
. Added : panel to modify "config.cfg/autoexec.cfg" in game
. Added : cvar pg_cl_crosshair_sprite_sizefactor (default 1) to increase sprite's based crosshairs when using high resolution
. Added : ability to mute player through scoreboard panel when sv_voiceenable set to 1
. Changed : full code optimization
. Changed : new splashscreen by firzen1
. Changed : up to 32 players instead of 16
. Changed : new player skins
. Changed : pg_sv_tdm_teams are now refering only to the first letter of the name of a team --> GOYBRP (G=Green, O=Orange, Y=Yellow, B=Blue, R=Red, P=Purple)
. Changed : pg_sv_lts_teams are now refering only to the first letter of the name of a team --> GOYBRP (G=Green, O=Orange, Y=Yellow, B=Blue, R=Red, P=Purple)
. Changed : pg_sv_domination_teams are now refering only to the first letter of the name of a team --> GOYBRP (G=Green, O=Orange, Y=Yellow, B=Blue, R=Red, P=Purple)
. Changed : in Promod hl2mp ladders have the same behaviour as textured ladders so that you can jump on them
. Changed : gauss beam managed client side so that you can choose if you want team colored beam or not
. Changed : gauss reg reviewed
. Changed : gauss primary fire effect ala "star wars"
. Changed : new version of map pg_stakx done by aRm
. Changed : fraglimit restored
. Changed : AddTime removed
. Changed : ability to have "In-Eye death" ala DOD:S instead of Third person view when dying
. Changed : when spectating, DefaultFov remains your Fov instead of the one from the observed player
. Fixed : combine ball no longer kills the launcher after having killed an opponent
. Fixed : combine ball killed the shooter in Original HL2DM
. Fixed : teleporter was not remaining speed
. Removed : pg_sv_reg_tripmineexploit, pg_sv_reg_nophysgundelay, pg_sv_itemthroughwall cvars removed
. Removed : maps from installation packages ---> pg_lostvillage, pg_gaswork, pg_democracy, pg_np_refinery, pg_powerhouse, pg_steamlab, pg_swamplight. all this maps can be downloaded from our download section.

Version HL2DMPro 1.7 :
. Added: Hud "Inventory"
. Changed: new weapon balance (ProMod only)
. Changed: no spread for smg1 and ar2 (ProMod only)
. Fixed: server was crashing when starting dm_lockdown
. Fixed: lts was not running properly when a new player was joining a team during a round

Version HL2DMPro 1.6.1 :
. Added: Scorer in Football/Warball/CTF/CTF Arcade is displayed
. Changed: gauss power tuned
. Changed: white ball symbol in mini scoreboard in front of the team that holds the ball Football
. Changed: yellow ball symbol in mini scoreboard in front of the team that holds the Warball
. Changed: no death column in Football
. Fixed: Weapons/ammos/items respawn correctly
. Fixed: no black screen anymore when switching to windows and switching back to HL2DM Pro
. Fixed: Selection of new mods in Admin was not effective in Command menu
. Fixed: CTF sounds were not played properly
. Fixed: Scorer in Football/Warball/CTF/CTF Arcade/Domination scores a frag
. Fixed: bad sequence in blue flag model
. Fixed: RPG fired when switching quickly from a weapon to RPG
. Fixed: Red teams respawn points in pg_stadium

Version HL2DMPro 1.6 : 23/03/2006
. Added: new intro video done by netrex. XviD codec is in "hl2dmpro\media" folder
. Added: 5 new game mods
  - CTF: Capture The Flag
  - CTF Arcade: same as CTF but you start with all weapons
  - Domination: hold the flag the biggest elapse time you can
  - Football: put the ball on opponents base to score
  - Warball: same as Football but with weapons
. Added: versions controler which prevents to play with a client version that does not match server version
. Added: map "pg_campgrounds" from [m.x]
. Added: map "pg_stalky_b3"
. Added: map "pg_stadium" from StickFigs
. Added: "Objective" panel which shows objective of the current gamemod (you can bind a key to open it: by default it is 'i')
. Added: "Last news" panel which displays the last news coming from the http://www.hl2dmpro.com website (click on the "Last news" button in the "Command menu" to open it)
. Added: "Original HL2DM" panel in order to vote for server variables that are dedicated to "Original HL2DM"
. Added: Full crosshairs management from the "Player menu". You can choose:
  - if you want to activate or not the "quick info"
  - if you want crosshair being always bright
  - color of the crosshairs
  - color of the brackets
  - if you want to use a font based crosshair and which shape you want to use
  - if you want to use a sprites file like in HL1
. Added: Dynamic map analysis
  - all "dm_" maps are dynamically modified to integrate gauss/gauss ammo and a long jump module. All maps that are currenlty existing for vanilla are now already adapted to Promod without doing anything
  - all "dm_" maps (and "pg_" maps) are also dynamically modified to integrate new items required to play CTF, CTF Arcade, Domination, Football and Warball
  - HL2DM Pro is now fully compliant with maps from many other mods like CSS, DOD, Dystopia, HL2CTF, Hidden Source, SourceFort, Plan of Attack, Battleground 2, Project 22, HL Assault, Golden Eye. All maps coming from these mods are dynamically modified to be compliant with all gamemods of HL2DM Pro. Check our guide section to see how to proceed: http://www.hl2dmpro.com/guides_main.html
. Changed : map "pg_stalkyard" removed from installation pack
. Changed: "Administration" panel takes care of new gamemods and settings for "Original HL2DM"
. Changed: colored names/text/death notice are now available in "Original HL2DM". Refer Changelog 1.5.1 to see how to use this feature
. Changed: FOV unlocked in "Original HL2DM"
. Changed: drawviewmodel unlocked in "Original HL2DM"
. Changed: gauss registration is now fully functional
. Changed: "Red combine" turn to "Blue combine" using alba's brightskins
. Changed: "Blue rebels" turn to "Red rebels" using alba's brightskins
. Changed: an admin can have access to all "command menu" options even if he is not playing
. Changed: crowbar and stunstick have same power and same refire rate in Promod only (unchanged in "Original HL2DM")
. Changed: gauss penetration distance increased
. Changed: 2 RPG ammo in all game mods except for Arcade, CTF Arcade and Arena where there is only 1 RPG ammo max
. Fixed: crash when loading a map for the first time no longer occurs
. Fixed: sometimes it was impossible to kill an opponent in LTS
. Fixed: "quick info" brackets does not display bad character
. Fixed: "mini-score" was not working properly in non teamplay mods

Version HL2DMPro 1.5.1 : 26/01/2006
. Added: Advanced Player Menu
. Added: new splash screen from [KIA]Stig
. Added: new map from SilentRunner007 --> pg_stalkx
. Added: colored names/text (chat, target id, deathnotice...)
	To write with colors, include those codes in your name/text:
	^0: default color from Valve 		^9: orange
	^1: red					^a: black
	^2: green				^b: dark blue
	^3: yellow				^c: dark green
	^4: blue				^d: dark red
	^5: cyan				^e: dark pink
	^6: pink				^f: dark grey
	^7: grey				^g: dark cyan
	^8: white
. Added: client CVARs all availabled in the Advanced Player Menu
	- pg_r_3dsky : to enable or not 3dsky
	- pg_cl_weapon_icon_x: x axis position of the onscreen weapon icon if weapon model is not drawn
	- pg_cl_weapon_icon_y: y axis position of the onscreen weapon icon if weapon model is not drawn
	- pg_cl_miniscore_team_x: x axis position of the onscreen score when in teamplay mod
	- pg_cl_miniscore_team_y: x axis position of the onscreen score when in teamplay mod
	- pg_cl_miniscore_noteam_x: x axis position of the onscreen score when not in teamplay mod
	- pg_cl_miniscore_noteam_y: y axis position of the onscreen score when not in teamplay mod
	- pg_cl_colorednames: set to "1" to see colored names, "0" to not see them colored
	- pg_cl_coloredtext: set to "1" to see colored text, "0" to not see them colored
	- pg_cl_coloredtargetid: set to "1" to see colored names in your target ID Hud, "0" to not see them colored
	- pg_cl_coloreddeathnotice: set to "1" to see colored names in Death Notice Hud, "0" to not see them colored
. Added: ability for an Admin to select the teams that are authorized in teamplay mods (TDM and LTS)
. Added: new server side CVAR pg_reg_sv_hitsound to enable "hitsound" in "Original HL2DM" mod
. Added: spectators that are spectating a player also hear "hitsound" of the spectated player
. Added: prevent "Get items through wall" exploit. Activated by default in ProMod. In "Original HL2DM", server Admin must set CVAR 'pg_sv_reg_itemthroughwallexploit' to '0' to prevent this exploit.
. Added: localization sentences for multi-languages support by KindDragon
. Added: default bind settings in case of a new install by KindDragon
. Changed: long jump always stands up
. Changed: zoom/unzoom activated when spectating a player
. Changed: improved gauss registration
. Changed: gauss wall penetration increased
. Changed: one hand grenade at respawn (ProMod only)
. Changed: smg1 grenades --> -25% in radius, -15% in damage (ProMod only)
. Changed: RPG missile --> -25% in damage (ProMod only)
. Changed: Ability to switch from RPG to another weapon even if the red dot is activated
. Changed: "phys_swap scripts" exploit is not possible in ProMod since 1.5 and in "Regular HL2DM" if pg_sv_regular_nophyscannondelay is set to "0". Fine tuning has been done to find a better compromise between the way to prevent this exploit and the way to perform good actions
. Changed: attack2 of shotgun is firing 14 bullets instead of 12 (ProMod only)
. Changed: wallgauss allowed in Arena
. Changed: stunstick and crowbar have same damage and range (Promod only)
. Changed: RPG speed lowered (Promod only)
. Fixed: maps with longjump/gauss respawn problem --> pg_boot_camp, pg_lockdown, pg_overwatch, pg_lostvillage
. Fixed: missile is always driven by the red dot if it is On
. Fixed: battlefield is correctly set up even if we switch from one map to an other
. Fixed: unavailability to spectate a spectator
. Fixed: In LTS say_team messages from a dead player are not visible to other team players that are still alive
. Fixed: r_drawviewmodel can be used in "Original HL2DM" if sv_cheats is set to "1"

Version HL2DMPro 1.5 : 16/12/2005
. Added: Admin Menu
. Added: Last Team Standing gamemod
. Added: 4 new teams --> Yellow Combine, Red Combine, Blue Rebels and Purple Rebels
. Added: wall jump
. Added: 3 new maps --> pg_swamplight and pg_icepick_B3 from Finger and pg_scepter from -think-circle
. Added: dynamic modification of FOV in ProMod (80 to 120)
. Added: ability to bind a key to open a Demo UI via Keyboard panel
. Added: mod icon in steam
. Added: unlimited reflection in secondary fire of gauss
. Added: team sorted by scores in Scoreboard (in ProMod)
. Added: default binds for additional ProMod features
. Added: dynamic control of "Add Time" and "Time Limit" entry fields in Command Menu
. Added: new variables for dynamic messages
	- %w: display your current weapon
	- %d: display your last dropped weapon
. Added: pg_cl_miniscore_team_x, pg_cl_miniscore_team_y, pg_cl_miniscore_noteam_x, pg_cl_miniscore_noteam_y to position the miniscore in the screen
. Added: physcannon primary attack can act on players by pushing them
. Changed: new maps version -> pg_boot_camp and pg_np_refinery_b5 from keved
. Changed: default spawn with one hand grenade
. Changed: 3 SMG1_Grenades in Arcade and Arena when spawning
. Changed: all "pg_cl_" CVARs are written in the config.cfg when changed
. Changed: Arena countdown set to 5 (was 10)
. Changed: countdown last minute in Red
. Changed: countdown ten last seconds with hundredth of second
. Changed: bunny hopping/long jump enabled when ducked
. Changed: instantGib includes .357 and crossbow. No primary fire with gauss.
. Changed: instantGib now allowed in "Regular HL2DM"
. Changed: unlimited reflection in primary attack of gauss
. Changed: ability to be a non player spectator in Arena mod
. Changed: ability to go to spectator even if dead
. Changed: rcon moved from Command Menu to Admin Menu
. Changed: gauss beam enlarged
. Changed: RPG with only 1 missile maximum (to prevent RPG spamming) in ProMod
. Changed: RPG missile damage power reduced of 25%
. Changed: RPG max ammo is 1 in ProMod
. Changed: Gauss accuracy improved
. Changed: Gauss recoilforce increased of 3%
. Changed: Gauss penetration power reduced from 48 units to 17 units in order to make most of the maps playabled with wallgauss "on"
. Changed: Gauss secondary attack power reduced of 25%
. Changed: wallgauss is disabled in Arena mod
. Changed: quicker weapon switch and attack (ProMod)
. Fixed: "tripmine under object" exploit is not possible in ProMod.
	 To prevent it in "Regular HL2DM" set pg_sv_regular_tripmineexploit to "0" (set to "1" by default).
. Fixed: "phys_swap scripts" exploit is not possible in ProMod.
	 To prevent it in "Regular HL2DM" set pg_sv_regular_nophyscannondelay to "0" (set to "1" by default)
. Fixed: when changing level, battlefield items are adapted to it
. Fixed: miniscore is now display even if timelimit is set to 0
. Fixed: When in zoom in magnum or xbow and dropping weapon, we are not zoomed in the new weapon
. Fixed: server does not crash if dropping weapon when in spectator
. Fixed: Shot on npc (SLAM) does not make hitsound now
. Fixed: "maps list" and "next maps list" are updated when changing from a server to an other one

Version HL2DMPro 1.4 : 19/10/2005
. Added: 3 new game mods
  - Arena: turning one on one (no combine balls in this mod)
  - InstaGib: one hit one kill
  - Arcade: spawn with all weapons and full armor (no combine ball in this mod)
. Added: hit sound when hitting an opponent (view from the server). Specific sound when hitting head. Can be activated/de-activated in command menu (adding of a client side variable pg_cl_hitsound)
. Added: drop weapon <-- use control panel to bind a key to this feature. 
  Please note that only the following weapons can be dropped: SMG1, AR2, .357 magnum, Crossbow, RPG, GAUSS, Pistol, Shotgun. The other weapons crowbar/stunstick, physcannon, frag, satchels can not be dropped.
. Added: "in-game score teams" or "rank/# players" with diff with players just above and player just behind you. Can be activated/de-activated in command menu (adding of a client side variable pg_cl_showteamsscore)
. Added: brightskins in Pro Mod only
. Added: autoload of location file if it exists for the map
. Added: say/say_team with dynamic informations:
  - %h <-- print health
  - %a <-- print armor
  - %l <-- print location if have the info
  - %j <-- print if he has long jump or no
  i.e.: add the following sentence in your autoexec.cfg file: bind "h" "say I'm a %l (%h/%a) LJ[%j]"
. Added: tool to generate location files with console commands (file scanned when using %l in say message)
  - pg_loc reset : reset the list of locations
  - pg_loc add "text of location" : add this location to the list with your current coordinate
  - pg_loc list : list all locations in the list
  - pg_loc list startnumber endnumber : list locations from startnumber to endnumber
  - pg_loc del number : delete location number
  - pg_loc save : save the list of locations in the file maps/mapname.loc
  - pg_loc load : load the list of locations from the file maps/mapname.loc
  Please note that all these commands are server sided, you must be admin/rcon to use them
. Added: pg_version variable to know the server version via a game browser before joining
. Added: gauss reflector in primary attack dependant on the angles with the hitted surface
. Added: ability to draw or not the weapon (r_drawviewmodel)
. Added: location files for : pg_stalkx2, pg_lostvillage, pg_boot_camp, pg_lambdabunker, pg_gasworks, pg_stalkyard, pg_powerhouse, pg_democracy, pg_lockdown, pg_overwatch
. Added: new maps : pg_boot_camp (remake by keved), pg_np_refinery_b1 (by keved), pg_lambdabunker, pg_gasworks, pg_stalkyard (done by boxy), pg_steamlab (adapted by [m.x]). We encourage the authors of pg_lambdabunker and pg_gasworks to contact in order we thank them correctly
. Changed: bunny hopping is now easy even in Internet servers
. Changed: restore valve settings for shotgun
. Changed: including physics in longjump module
. Changed: gauss with new effect
. Changed: gauss loading speed
. Changed: gauss penetration distance (from 16 to 48)
. Changed: wallgauss impacts all entities
. Changed: gauss secondary fire delay between 2 shots set to 0.5
. Changed: spectators can't vote
. Changed: unduck speed increased of 1.4. It makes the jump on boxes a lot easier and quicker for a smoother movement
. Changed: longjump speed decreased from 350 to 330
. Changed: colors in score board of ProMod are now green for Combines and Orange for Rebels
. Changed: restart round function in order to be compliant with all maps
. Changed: impossible to jump if ducked
. Fixed: gauss ammo are now easy to pickup
. Fixed: gauss looping sound
. Fixed: gauss sound localization
. Fixed: RPG reload in "Original HL2DM"
. Fixed: kill bug
. Fixed: no tripmine left when starting a match

Version HL2DMPro 1.3.3 : 08/09/2005
. Changed : restore standard RPG reload speed in "Pro Mod"
. Fixed : server crash when restarting "dm_swamplight_final"

Version HL2DMPro 1.3.2 : 06/09/2005
. Fixed : restore standard RPG reload speed in "Original HL2DM"

Version HL2DMPro 1.3.1 : 15/08/2005
. Fixed : sometimes server/client crashes just before rocket explodes

Version HL2DMPro 1.3 : 12/08/2005
. Added : gauss weapon aka Tau canon with wallgauss
. Added : wallgauss on/off via GUI
. Added : tweaked bunny jump (air acceleration included)
. Added : "Easy Start" intro menu
. Added : sound when picking up the longjump module
. Added : maps pg_lockdown, pg_overwatch, pg_powerhouse <-- great maps created by Valve that we have adapted to the gameplay and features of HL2DM Pro
. Added : maps pg_democracy, pg_lostvillage <-- two other great maps. Message to the authors: thanks a lot for the quality of your maps. Please contact us to get proper thanks
. Changed : quick weapon changing
. Changed : when RPG laser guide is Off, ability to change from RPG to another weapon even if a missile has just been fired
. Changed : shotgun strength lowered
. Changed : default walking speed reduced (265 instead of 290 in 1.2)
. Changed : default sprint speed reduced (300 instead of 380 in 1.2)
. Changed : no hand grenades on respawn
. Changed : Step sounds is the same for Rebels and Combine
. Changed : pg_stalkx2 (remake by {2h2k}-Dealer) includes Gauss and associated ammo
. Changed : same step sounds for Rebels and Combines (equilibrated team features)
. Fixed : silent jump not possible now
. Fixed : Source TV is not considered as a player for vote
. Fixed : server does not crash when starting a round under "dm_powerhouse"

Version HL2DMPro 1.2 : 09/07/2005
. Added : longjump (requires a map with the longjump module)
. Fixed : superadmin can speak to players during a match
. Fixed : superdamin can pause a match
. Fixed : superadmin can abort a match
. Changed : longjump module added to pg_stalkx2 (remake by {2h2k}-Dealer)

Version HL2DMPro 1.1 : 03/07/2005
. Added : dm_stalkx2 map by {2h2k}-Dealer
. Added : RCON GUI so that admins can decide on settings with no vote
. Added : "Vote Yes" and "Vote No" buttons in GUI
. Added : "Please vote " message when a vote is required
. Added : direct weapons bind in "Controls" panel
. Added : support for widescreen - 16:9 and 16:10
. Added : autorecord demo
. Added : auto screenshot in case of change map or match is over (can be set in config.cfg by adding -> pg_cl_autoscreen "1")
. Added : pg_matchison (yes/no) -> Shows if a match is started or not
. Fixed : RPG repeating noise
. Fixed : "Speak" when in spec mode and no match started
. Fixed : Friendly Fire is deactivated when in FFA
. Fixed : timelimit = 0 means no start of match and no add time as 0 means infinite duration
. Fixed : dynamic menu was not running properly
. Changed : bolt speed ==> low speed if non-zoomed / high speed if zoomed
. Changed : shotgun damage is stronger
. Changed : sprint speed reduced to 380 (420 in 1.0)
. Changed : when a server is started by a user, this user is handled as a superadmin

Version HL2DMPro 1.0 : 16/06/2005
. Fixed : scoreboard
. Added : steam_id in scoreboard
. Added : colt zoom
. Added : unable/disable RPG red dot
. Added : mp5 is more accurate
. Added : faster bolt speed
. Added : Bunny hop
. Added : increase default moving speed
. Added : in game Graphic User Interface
. Added : decide game mode in game
. Added : voting system
. Added : counter with voice message when match starts
. Added : pause match
. Added : counter when match restarts
. Added : recover score when a player dropped
. Added : decide next map
. Added : set time limit, friendly fire, weapon stay in game
. Added : roaming spectator mode
. Added : in eye spectator mode
. Added : chase spectator mode
. Added : sign in case of headshot (for magnum and shotgun)
