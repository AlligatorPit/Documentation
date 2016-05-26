Entities
========
The Entities handle can be used to access and manipulate entities.

GetAll
------
Returns a ``Table`` of all entities in the world.

GetLocalPlayers
---------------
Returns a ``Table`` of local ``PlayerHandle`` objects. "Local" means the players that are playing on the computer the function is called on. This is most often a single player, but could also be multiple players in case of split screen.

GetAllPlayers
-------------
Returns a ``Table`` of all ``PlayerHandle`` objects in the world.

GetByName
---------
Returns an entity by name, or ``null`` if it can't be found.

This function takes 1 or 2 arguments:

* ``String name`` - The name of the entity.
* (optional) ``Number index`` - The index of the entity in the array, in case there are more entities with the same name in the world.

GetCount
--------
Returns a ``Number`` of the amount of entities currently in the world.

GetByIndex
----------
Returns the entity at the given index from the world. Must be between 0 and the return value of ``GetCount``.

This function takes 1 argument:

* ``Number index``

GetLocation
-----------
Returns a ``Vector`` of the position of the given entity.

* ``CEntity entity``

SendSync
--------
Sends a correctional synchronization packet to clients for the given entity and the given property name. This is useful for addons, so servers can force the state of some property on some entity.

This function takes 2 arguments:

* ``CEntity entity`` - The entity to send a correctional packet for to clients.
* ``String propertyName`` - The name of the member variable on the entity to send a correctional packet for.
