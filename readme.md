## Introduction
The Pokecrystal access project is designed to provide a set of scripts,
currently for the VBA-ReRecording gameboy emulator. These scripts allow the playing of
Pok�mon Crystal for people using a screen reader.

## Requirements and installation
1. You'll need VBA ReRecording:
http://vba-rerecording.googlecode.com/files/vba-v24m-svn-r480.7z

1. Get an English pok�mon crystal rom.

1. After you have these, extract and run VBA.

1. Go to the Options menu, Head-Up Display, Show Speed, None (alt-o, h, s, enter)
Without this, NVDA reads the title bar every time it changes.
1. Optional, turn down the sound. Options, Audio, Volume (alt o, a, v)
##Starting the game
Each time you run VBA, you'll need to load the rom.
You can do this from the open dialog, or load a recent rom after you've opened it once.

Once the rom is loaded, load the lua script (tools, lua, New Lua script window).
From there, load pokemon.lua, press run. It should say ready, alt tab out and back in again

##Keys
Make sure num lock is off while playing the game, or the keys won't work.

* j, k and l - previous, current and next item
* shift m - read current map name
* shift n - rename current map
* n - rename current item
* t - read text on screen, if any
* p - pathfind
* c - read coordinates
* h - read enemy health if in a battle

