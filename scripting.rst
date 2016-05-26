Scripting
=========

Introduction
------------
The scripting language we use in Revolution is called Bromscript. This is an advanced scripting language written by one of our own programmers. It's heavily inspired by Lua and C++, with the goal to improve upon the existing Lua syntax. You can read more about it on `the Bromscript website <http://bs.4o3.nl/>`_.

Script entity
-------------
The script entity in-game lets you execute scripts when the entity is triggered. These scripts can reference other entities and change their properties.

A simple example would be something like::

	local ent = Entities.GetByName("Some Gnaar")
	print(ent)
	ent.m_fMoveSpeed = 10

Script handles
--------------
These is where most of the API resides.

.. toctree::
   :maxdepth: 1
   :glob:

   handles/*

Entity classes
--------------
These are all the entity classes that are approachable by scripts.

.. toctree::
   :maxdepth: 1
   :glob:

   entities/*
