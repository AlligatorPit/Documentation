Player
======
The Player handle contains information about a player.

It has 3 member variables:

* ``Number PID`` - The player ID.
* ``String Name`` - The current name of the player.
* ``String SteamID`` - The Steam ID of the player, in Steam2 ID format.

Kick
----
Kicks this player if this is called on a server.

This function takes 1 argument:

* ``String reason`` - The disconnect message to show to the player.

SendChat
--------
Send a chat message to this player from the server. Nobody else but this player will see the message.

This function takes 1 argument:

* ``String message`` - The message to send to the player.

GetEntity
---------
Returns the ``CPlayer`` object for this player.

operator ==
-----------
Returns a ``bool`` if the players have matching Steam IDs.
