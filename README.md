# UT2004 Server for Pterodactyl 

I couldnt find any eggs for UT2004 so I decided to learn some stuff and create my own

Current version contains: 
  - patched uplink servers for openspy and 333networks
  - download redirect to http://uz2.pwc-networks.com/

Working gametype variables:
  - deathmatch|dm 
  - lastmanstanding|lms
  - teamdeathmatch|tdm
  - onslaught|ons		
  - bombingrun|bomb
  - invasion|inv
  - assault|aslt
  - doubledom|dd
  - mutant|mut
  - capturetheflag|ctf

You can set your wanted mutators in start.sh file. 

Things you may want to add/change: 
  - change Name/Region/MessageOfTheDay in ./System/UT2004.ini, starting at line 292
  - add a "cdkey" file in ./System/ with your key to get rid of "Couldn't open cdkey file." error

Feel free to contact me at discord: gfxspeed

Ports:

|Port	|Type	|Description|
|-----|-----|-----------|
|7777	|UDP/IP	|(Game Port)|
|-----|-----|-----------|
|7778	|UDP/IP	(|Query Port; game port + 1)|
|-----|-----|-----------|
|7787	|UDP/IP	|(GameSpy Query Port; game port + 10)|
|-----|-----|-----------|
|28902	|TCP/IP	(|Allows your Server to Connect to the UT2004 Master Server Browser)|
|-----|-----|-----------|
|xxxx	|TCP/IP	|(Port set via ListenPort that your WebAdmin will run on)|


Many thanks to: 

- https://github.com/parkervcp for a ton of pterodactyl eggs, learned alot there
- http://jsalmi.com/ut2004/ for the base of the start.sh file 
- http://uz2.pwc-networks.com/ for still hosting a lot of UT2k4 mods
- https://333networks.com/ and https://openspy.net/ for masterservers 
