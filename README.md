![Logo](https://cdn.discordapp.com/attachments/616061053662527502/790365924653531144/desolate_lands_logo_bright.png)

This is some--albeit outdated--of Yu's work on Desolate Lands, a multiplayer, 2d, bullet-hell shooter game. The HTML file included in the source is an older version of the payment website we had. The server included is purely the server code, and purely for studying/viewing purposes.

# Basic Stucture

The server is composed of a few things: a chat server, a login server, a world spawner, and a world server. The chat server handles in-chat chatting features between players, the login server handles the logging in of players, the world spawner creates world servers based on in-game actions, and the world server is where the players interact with game objects. There can be multiple world servers running, and each individual server is its own application. The world server also handles hit detection and player collision server-side to ensure that players aren't cheating.

# Screenshot of Gameplay
![Gameplay](https://cdn.discordapp.com/attachments/616061053662527502/675766723831529472/unknown.png)
