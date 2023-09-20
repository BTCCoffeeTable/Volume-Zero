The irc.cpp file in the Bitcoin v0.01 ALPHA software is a key component that works in tandem with the irc.h file. It contains the implementation of the functions used to connect to an Internet Relay Chat (IRC) server.

In the early days of Bitcoin, IRC was used as a means for nodes to discover each other. When a node started, it would connect to an IRC server and join a specific channel. The node would then see other nodes in the channel, obtain their IP addresses, and establish connections with them.

The irc.cpp file provides the implementation for the functions necessary to interact with an IRC server. It includes functions to connect to the server, join a channel, and parse the list of users in the channel.

This file underscores the importance of network discovery in the operation of the Bitcoin network.