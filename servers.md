# Installing

The dedicated server can be installed either via [Steam CMD](https://developer.valvesoftware.com/wiki/SteamCMD) or via the Steam client itself.

If you're installing the dedicated server via Steam CMD, the AppID for the dedicated server is `299310`.

Otherwise, you can get the dedicated server via the Steam client, under the *Tools* tab.

# Configuring

First of all, you need to have a server configuration. A configuration is a folder of `.ini` files that define the properties. These configurations are actually scripts, which run on the internal shell, which is basically the same as the in-game console.

Each configuration has its own folder in the `Scripts/Dedicated/` folder. You can see that there are already a few default configurations that we ship, but we don't recommend using them directly. You can use the folders as a template for your own server, however.

As a quick guide to getting started, we'll set up a basic cooperative server. Copy the `DefaultCoop` folder and paste it in the same folder with a different name. For example, `MyAwesomeCoopServer`. This server configuration can then be used by the dedicated server executable by running the dedicated server with the name of the folder as its parameter. For example: `Bin/DedicatedServer.exe MyAwesomeCoopServer`.

You could make a batch file for this for convenience:

```
@echo off
Bin/DedicatedServer.exe MyAwesomeCoopServer
```

### init.ini

In the example above, we copied `DefualtCoop` to `MyAwesomeCoopServer`. In that folder, there is an `init.ini` file, which is the most important file in your configuration. This is where you'll set most of the server properties.

The default file has comments explaining most of the options, but here's a list of a few noteworthy ones:

* `net_iPort = 27015;` This sets the server port to 27015 and - implicitly - the enumeration port to 27016.
* `gam_strSessionName = "Awesome Server";` This sets the server name that is shown in the server browser.
* `net_ctMaxPayers = 16;` This sets the maximum amount of players to 16. The minimum for this is 2, and the maximum is 42.
* `ser_bWaitFirstPlayer = 1;` This makes the server wait for the first player to join the server before it starts executing game ticks. It's recommended to keep this option on.
* `ded_strLevel = "...";` Sets the level to start on. This can optionally get overridden in the `n_begin.ini` files.

Some helpful variables that are not included with the default configurations are:

* `net_bEnableAPI = 1;` Enables the RCon API. This will allow you to use `RCon.exe` to connect to your server and execute commands. This will also allow you to programatically execute commands on the server.
* `net_iPortAPI = 5000;` Sets the port used for the API to 5000.
* `net_strAdminPassword = "joe";` Sets the RCon password to "joe". You will need this when connecting to the API.
* `ser_bPure = 1;` Requires all clients to have the same mods installed as the server. That means that if the server has no mods installed, all other clients must also not have any mods installed.

### n_begin.ini

This file is executed at the beginning of the round, before the level loads on the server. This means that you can put `ded_strLevel = "...";` here to load a different level. This is normally only useful in versus gamemodes. By making several files, such as `1_begin.ini`, `2_begin.ini`, `3_begin.ini`, ..., you can define a list of levels that will be played through on the server.

### n_end.ini

Executed at the end of the round. This could be used (for example) to tell clients what map is going to be played next. However, it's not recommended you use these files for actual scripting, but instead use script addons written in Bromscript. Therefore, it's suggested you keep this file empty, or simply not modify the default example scripts if you so wish.

# Addons

Addons are scripts written in Bromscript that can get executed by the game or the server. By default, Revolution ships with the "CCC", the "Combative Creature Cutter".

### CCC (Combative Creature Cutter)

Todo...
