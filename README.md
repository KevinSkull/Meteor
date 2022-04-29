Meteor
======

Meteor is a C# open-source CFlyFF (Chinese FlyFF) emulator based on lesderid's open source emulator : https://github.com/lesderid/XinFeiFei

I suggest you to read the full README.md of XinFeiFei emulator.

We develop this emulator for fun and for learn more about C# and network apps.
/!\ Please respect the credits ! For lesderid's work if you use his source or mine if you're using this sources.

Credits for uXinEmu :

- Lesderid (Original author)
- pushedx, RE help
- Duotone, RE help
- Windrius, RE help

Credits for Meteor :

- ShyroFR (developer)

Informations:
-------

Meteor is developed in C# with Visual Studio 2012.

Database : MySQL

App type : Console

Client link : https://mega.nz/#!KRlj0ALR!JaOuioqgv1-7foQM94TjfCKnoYGdKO-PEE8P1by-fig

Install instructions:
-------

1) Install the database (meteor.sql)

2) Configure "meteor.exe.config"

3) Copy your "gameres" folder from your CFlyFF client and past it in the Meteor "Binary" folder.

4) Run the "Meteor.exe"

5) Enjoy !

I'll post more tutorials later... :)

Todo list
-------

- Player timers + real moves
- Inventory

Tools :
-------

CFlyFFAddonsExtractor:
![Alt Text](http://www.yagoshack.fr/images/cflyffaddo.png)

Extracts all files from config.wdf and converts them into .lua files


--------
**Full README.md of XinFeiFei emulator (archived)



﻿I strongly advise you to read the full README before you use the project.


Description
-----------

This project contains a number of applications for use with the 新飞飞 (also known as 'cFlyFF' or 'FF') client and/or server.

A short description of every sub-project:
-decompiler (LuaChunkExplorer): Originally a tool to disassemble Lua manually, now a tool that makes use of an external decompiler to decode and decompile the files extracted from the WDF packages.
-emulator (uXinEmu): A small and very incomplete emulator for 新飞飞 written in C#.
-encryption (FFEncryptionLibrary): A small, but complete C++/CLI library to generate the keypairs and handle the encryption used in 新飞飞's packets.
-extractor (uWDFExtractor): An extractor for 新飞飞's WDF (and WD1...n) packages.
-proxy (FFProxy): A proxy for 新飞飞 that can be used to decrypt and dump its packetflow.

Credits
-------

-lesderid, original author (lesderid@hotmail.com)
-pushedx, RE help
-Duotone, RE help
-Windrius, RE help


License
-------

This project (all files originally included in the git repository) is released under the Common Development and Distribution License (version 1.0).
The full license can be found in the file 'LICENSE'.

A summary of this license (with no legal value):
-You can use this project for 'all' purposes, including commercial ones.
-Files you add to the project are allowed to be released under a different license.
-Redistribution of the project is allowed, but the (original) source code must be available.
-You may not alter or remove the 'Credits' section of this document and you may not alter or remove the original attribution in any other way.

Please read the full license before you use, alter and/or distribute this project.


Small request
-------------

Please don't use this project just to rip cFlyFF's UI, cash shop items or other resources.
I have spent countless hours working on this project mostly because I really love this game.
Please be respectful towards me and the game's developers by not using our work for easy money.


Donations
---------

Like I said in the previous section, I've spent quite some time working on this project.
As you know, time isn't free, however I am releasing this for everyone to download for free.
Therefore I would very much appreciate a small donation if you like this project and/or wish to use it.

PayPal: lesderid@gmail.com


Compiling
---------

This project can be compiled with the latest version of Microsoft Visual Studio (currently 2012).
Earlier versions might work, but haven't been tested.
