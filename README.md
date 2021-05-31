# AWS Server Connectivity
A short analysis on packeting and why you get connected to the wrong server while playing any game made by big Gaming Studios such as EA, Activision etc.


I have written this repository after extensive study for the past month on how the packets released from our routers travel and reach AWS servers (Amazon Web Servers) who currently are in contract with EA for FIFA 21, hence my interest.

Of course there is a lot of times, we as gamers, feel we enter matches or matchmaking situations where we feel we are in a game with ping so horrible it is unplayable.

This can be due to 3 factors:
<br>

- Your internet connection is purely not sufficient or fast enough to broadcast or stream your games in a capable manner.
<br>

- Your bandwidth is incapable of handling too much traffic, this is applicable when there are multiple devices in your house attempting to hog the bandwidth, eg. Someone streaming Netflix, Prime, etc in 4K

- ** You are purely being connected to the wrong server as your ISP is under the impression the route to the server you're connected to, has the least latency.**
 

### In this README.md, we will be addressing just this third point, which gaming studios don't provide a strong enough method to troubleshoot for users.
  
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

The AWS server you are connected to, for a brief moment, experiences a overload in traffic and you might get redirected to a server in another country.

To check your AWS server latency, please click [here](https://www.cloudping.cloud/aws)

### You must be getting something like this:
![1Gi](https://user-images.githubusercontent.com/58849353/119665718-4a6a2c80-be52-11eb-88fd-55703734d849.png)


# In my case, it is currently Mumbai which is the closest server, but in case it was something else, the steps to reconnect to the Mumbai server would be:

+ **Factory reset your router to base settings**

+ **[Click this link](https://ec2-reachability.amazonaws.com) to see the IP Adresses of the EC2 AWS servers used by these gaming studios.**
+ **Copy one of the IP Addresses of the closest server to you.**
![2Gi](https://user-images.githubusercontent.com/58849353/119666219-cf554600-be52-11eb-8c02-3184376e577d.jpg)
+ **Open your Command Prompt in Windows and run the following command: ping (ip address of server), for example ping 3.6.0.0**
![3Gi](https://user-images.githubusercontent.com/58849353/119666659-31ae4680-be53-11eb-8b39-3cf69effdf24.png)

+ **Once you feel satisfied with the ping results, run the AWS latency test again, [here.](https://www.cloudping.cloud/aws)**

You should be getting your closest server as the best one after doing all the steps. Thanks for your time and I hope this helps you cause this really drove me insane for the past month! 

### Happy gaming/streaming!



 
  
