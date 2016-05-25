Server
======
This is the server library for dedicated server addons.

DoCommand
---------
Executes a string in the server console. It then returns a string of the output of the executed command.

This function takes 1 argument:

* ``String command`` - The string to execute in the console.

GetMap
------
Returns the filename of the current level as a ``String``.

GetPort
-------
Returns the value of ``net_iPort`` as a ``Number``.

GetHostname
-----------
Returns the hostname of the server as a ``String``.

GetGamemodeName
---------------
Returns the name of the current gamemode as a ``String``. This could be ``"Cooperative"``, ``"Deathmatch"``, ``"Capture The Flag"``, etc.

GetMaxPlayers
-------------
Returns the maximum number of players that can be in the server as a ``Number``.

GetPlayerCount
--------------
Returns the current count of players in the server as a ``Number``.
