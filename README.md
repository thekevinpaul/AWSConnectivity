# AWS Server Connectivity
A short analysis on packeting and why you get connected to the wrong server while playing any game made by EA Sports.


I have written this repository after extensive study for the past month on how the packets released from our routers travel and reach AWS servers (Amazon Web Servers) who currently are in contract with EA Sports.

Of course there is a lot of times, we as gamers, feel we enter matches or matchmaking situations where we feel we are in a game with ping so horrible it is unplayable.

This can be due to 3 factors:
<br>

i) Your internet connection is purely not sufficient or fast enough to broadcast or stream your games in a capable manner.
<br>

ii) Your bandwidth is incapable of handling too much traffic, this is applicable when there are multiple devices in your house attempting to hog the bandwidth, eg. Someone streaming Netflix, Prime, etc in 4K

<b>iii) You are purely being connected to the wrong server as your ISP is under the impression the route to the server you're connected to, has the least latency.</b>
 

 <h>In this README.md, we will be addressing just this third point, which EA or infact, some other gaming organisations don't provide a strong enough method to troubleshoot for users.</h>
  
  I say this with personal experience, being a victim of continously being connected to a server 10 times as far as the nearest one to me.
  
# Simple steps to get connected to the closest server:
  
When you are playing a game which uses AWS servers as game data centres, such as the following studios:
  
* Epic Games
* Gearbox Software
* Rovio
* Capcom
* Zynga
* UBISOFT
* Ankama
* Sony Playstation
* GungHo
* Untold Studios
* SundayToz
* Gameloft

The AWS server you are connected to, for a brief moment experiences a overload in traffic and you might get redirected to a server in another country. 

To check your AWS server latency, please click [here](https://www.cloudping.cloud/aws)
 
  
