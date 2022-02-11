# Backdoor script

Note: I'll be keeping the documentation and progress of my work on this page.
-_-_-_- Update -_-_-_-

After researching the topic of backdoor creation I decided to just make it a reverse shell script due to being short on time for development. Apologies.

###### Firstly what do I plan to achieve with this project?
I plan on coding a script that creates a connection once executed, which provides the client with an cmd shell on a windows machine.

## Useful networking sources:

* [PCoIP Protocol](https://en.wikipedia.org/wiki/Teradici#PCoIP_Protocol)
* [RDP](https://en.wikipedia.org/wiki/Remote_Desktop_Protocol)
* [SPICE](https://en.wikipedia.org/wiki/Simple_Protocol_for_Independent_Computing_Environments)
* [More info on Remote Administration](https://en.wikipedia.org/wiki/Remote_administration)


[Wake on LAN](https://en.wikipedia.org/wiki/Wake-on-LAN) - Cool feature to add

## Interesting libraries to look at
mRemoteNG
websocket-sharp - Currently inspecting 
BeetleX
System.Net.Sockets - Creates a TCP connection via the TcpClient class
