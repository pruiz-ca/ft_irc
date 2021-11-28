# 💬 ft_irc
Our own IRC Server written in C++ without forks using poll. Tested with LimeChat and Textual.

Made by: [🐨 mmunoz-f ](https://github.com/mmunoz-f) [🦔 rorozco-](https://github.com/larroky)  [🦞 pruiz-ca](https://github.com/pruiz-ca)

## Features
- RFC Compliant
- Compatible with comercial clients
- Server password
- Nick and Username registration
- Ping Pong
- Channels
- Modes (user, channels and operator)
- Kick, Kill and Ban
- Messages / notice
- List, names, whois, who

## How to use
1. Clone this repo
2. Run ```make``` or ```make debug``` to print what the server receives and send to stdout
3. Run ```ircserv <port> <server_password>```
4. Connect with a client to the IP and Port printed by the server.
5. With the client, send:

		PASS <server_password>
		USER <username> 0 * :<Real Name>
		NICK <nickname>

6. By now you should have access to the server and can create channels or communicate with other users

## Resources
http://beej.us/guide/bgnet/html/ ⭐️

https://modern.ircdocs.horse/ ⭐️

https://www.rfc-editor.org/rfc/rfc2812

https://www.rfc-editor.org/rfc/rfc2813

http://chi.cs.uchicago.edu/chirc/index.html

http://books.msspace.net/mirrorbooks/irchacks/059600687X/irchks-CHP-5-SECT-2.html

https://www.cs.cmu.edu/~prs/15-441-F10/project1/project1.pdf

http://se.inf.ethz.ch/student_projects/fabian_gremper/Report.pdf

https://modern.ircdocs.horse/ctcp.html

https://modern.ircdocs.horse/dcc.html
