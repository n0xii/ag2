Heyyo,

Ok, since Cheeseh released RCBot2 preview, I decided to release a beta mappack.
Now take note that RCBot2 is still its early stages still, and cause of that,
the waypoint editor doesn't work right. After about the 72nd waypoint,
I can't really see the paths on them, sometimes I don't even see the waypoints.

To install just unzip the waypoints into your:

$moddir\rcbot2\waypoints\half-life 2 deathmatch\hl2mp   folder and pwn.

-ThE_MarD

========================================
Revision 2.0 - February 22,2007
(using RCBot2 Build v.08 v.2.06 alpha Feb16,2007 Release)
========================================
dm_lockdown - Since the upgrade of the waypoint editor (w00t! I can see all the waypoints
and pathwaypoints now with that rcbot waypoint drawtype 1 command) I started to fix up my
waypoints, and even fix up a lot of pathwaypoint errors.. maybe over 80 bad paths that
went through other waypoints and would cause bots to bump into objects/walls. I also
removed the ladder waypoints for the time being since the ladders aren't implemented
into the bot yet to prevent bots using ladders when they have no idea how they work.

dm_overwatch - Once again, fixed up a lot of pathwaypoint errors and better arranged a lot
of waypoints to make both navigation better. Probably moved/created 5-15 waypoints, and
fixed over 50 pathwaypoint errors.

dm_powerhouse - Removed all the ladder waypoints since they aren't implemented in the bot
yet, so they won't use those, but really fixed up this map. Probably over 40 waypoints
created and at least 200 waypoint errors fixed.. too many to keep track of.

dm_resistance - Like all the other maps, this one got lots of fixing up. It was a bugger
to do the pit there cause the autopathwaypointer is still very early stages and just
decided to link up a lot of waypoints, lol, fixed probably over 100 pathwaypoint errors
and 10-20 waypoints moved/created.

dm_runoff - Removed ladder waypoints, and created about 20 waypoints and fixed up over 70
pathwaypoint errors. The main ones being inside the building where they were just going
through tables and such.

dm_steamlab - This one had some pretty bad waypoint/pathwaypoint errors. I probably added
40 waypoints and fixed about 80 pathwaypoint errors. There was one pit where bots spawn
that didn't have a pathwaypoint going up the stairs so bots would just get stuck, and I
fixed the one pit with the ammo crates for rockets were by removing the ladder waypoint
and creating paths for bots to jump out via the pipes, and they do that pretty well. :)

dm_underpass - This map was royally screwed. I redid almost all the waypoints and added
over another 100 waypoints to make the bot movement less restricted. I also did it all
with auto pathwaypointing disabled. Got the map done MUCH faster. I also removed the
ladder waypoints until they are supported, and made a rediculous amount of pathwaypoint
changes.. this map's easily over 300 waypoints and 700 pathwaypoints now. :P


========================================
Revision 1.0 - June 28,2006
========================================
dm_lockdown - my first waypointing attempt. Bots tend to have problems with the
ladders, but that's cause I couldn't see 1 set of ladders, and the other I could
only see the waypoints, not the paths. :P

dm_overwatch - my 2nd waypointing attempt, and I say the better of the 2 right now.
Bots can pretty much run wherever they want, and I've even seen 1 bot run to the
top.

dm_powerhouse - impossible to waypoint properly until the waypoint editor's updated
so I can always see all the waypoints and the pathwaypoints, and cause of that,
I only completed ~70% of my waypointing/tuning on the level.

dm_resistance - this one also works pretty good, sometimes they don't get out of the
pits but that's due to invisible pathwaypoints too. The rest works great.

dm_runoff - this one works pretty good minus the ladders. I don't think RCBot likes
the new ladder style at all...

dm_steamlab - this is probably the most bot-friendly map of the bunch. I diddn't do
the telporter though since I ain't got the "rcbot util notouch" console command yet.

dm_underpass - this one has quite a bit of ladders, bots won't climb them. The rest
the bots do quite well as well.