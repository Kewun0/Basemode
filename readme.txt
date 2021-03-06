Me presents...
The official AAD (Attack and defence) gamemode for Liberty Unleashed! It was previously dedicated for public release to play clanwars by Liberty City Killers [LCK] clan and to let other clans/players play it on their own servers too. I've started development of this gamemode at around 2010 when I was a beta tester of LU and current version is from 2015.

The gamemode contains:
- 18 unique bases,
- 1 spawns for attackers,
- 1 closed lobby,
- well balanced weapons system to make every weapons useful, to avoid shotgun only fights or M16. Every weapon is powerful here and has it pros and cons,
- complete AAD logic (timeout, killed all players, picked up the base, draws),
- only attackers can enter vehicles and this is a basic the idea of AAD,
- a spectator (if I remember correctly it needs fixing),
- administrator luid loging in,
- admin commands: /bmlogin <pass> (login as administrator), /base <id>, /end, /switch, /add <player id>, /help, /t1/2name <team name>, /resetscore, /del <player id>, /add <player id>
- player commands: /votebase <id>, /fix or /fix2 to show/hide mouse cursor and toggle camera movement (it was messy sometimes, probably LU bug)
- a teamchat on "Y" key,

TODO:
- firstly, the easiest thing: it needs adding "DEBUG" variable in client and server to hide debug messages with "if ( DEBUG ) Message(...)"
- secondly: autostart system which is already in, but needs testing and probably fixing
- spectator camera, it was probably broken, but I'm not sure
- integrity with recent admin panel
- new bases and spawnpoints for attackers
- polishing GUI and adding a nice, centered "Basemode" logo on join
- showing only allied team players on radar (sadly, LU was missing functions to complete this and I'm not sure if it's possible)
and the last one: cleaning source from obsolete things.

Im looking for a developer, who can continue my work in this official thread and make updates under my supervision. I can help a bit, but my time is very limited. The goal is making this gamemode clear and 100% stable, to let people play clanwars or just have fun/train on public/private servers. Required is knowledge of squirrel and commiting changes on github, so everyone can see every change and to  be sure the script is safe. This AAD was inspired by Basemode from MTA:SA by [ANO]Rhbk.


Installation:


Changelog and history (including unreleased versios):

1.0-RC1 (24.05.2018):
- added information about team players count on spawnscreen
- made player frozen when using teamchat (Y)
- fixed /add command
- changed /type command to /settype and added parameter auto/vote/manual
- fixed known issues: /votebase, /bmlogin, errors caused by lu_ini module

1.0-beta (?? - 22.05.2018)
- first public beta release
- colored and fixed some messagess (kill/part/join)

1.0-alpha3 (21.09.2015):
- added score label
- improved UI
- opened garages
- added time and weather setting for bases
- deleted deprecated stuff
- added autostart system
- added part/join/kill messages

1.0-alpha2 (20.09.2015):
second private test
- balanced m16 weapon
- fixed base 8 marker
- increased weapons ammo
- increased capture time (15secs from now)
- added 7 bases

1.0-alpha1 (19.09.2015):
first real-private testing build with 2 players after recode

pre 1.0-stage2 (20.09.2014):
- improved map loader
- recoded game logic
- added 3 bases

pre 1.0-stage1 (27.07.2010):
- created basic map loader
- created basic game logic
- added 7 bases
- added spawn point for attackers (calahan bridge)

Big thanks to:
- NC (testing and help)
- Gudio (testing, help and hosting)
- Mr. Sych (my best friend forever, also tester)
- Piterus (testing)
- rww (testing)
and everyone which I've forgot - feel free to remind me!