> [!IMPORTANT]
> DELTAModKit is in **development.** If you find any issues, you can help out by creating an issue or opening a pull request.

# DELTAModKit
The most robust, feature-complete DELTARUNE GameMaker Studio 2 decompilation / port, enhanced with a multitude of tweaks designed to make the game easier to mod.

> [!CAUTION]
> This project does NOT allow for piracy of DELTARUNE Chapter 3, 4, or 5. It is simply a base from which you can start building your own DELTARUNE chapter/fan game. Most assets which have been included in the project can be found in the free Steam demo for Chapter 1 and 2.

## Usage
To start playing around with DELTAModKit, you have to download [GameMaker](https://gamemaker.io/en/download/windows/lts/GameMaker.exe). The project was originally created on GameMaker Beta, however any relatively recent version of GameMaker (such as the 2026 LTS) should work. 

1. Clone the repository onto your PC.
2. Create a `datafiles` folder at the root of the project.
3. Copy the `mus` folder from your Steam DELTARUNE installation into `datafiles/mus`.
4. Open the project in GameMaker.
5. To activate debug mode Switch Config from "Default" to "Debug"

> [!CAUTION]
> Light World (Hometown) rooms have not all been fully ported yet, so beware of missing text and certain rooms not existing.

## Adding / Changing Modular Stuff
The hearts of the modular reimplementations of the character, item, spell and equipment systems all live in the folder `Custom > Scripts > Configs`. I tried naming everything in an easy-to-understand way, but feel free to reach out if you encounter any issues. Provided in the `Custom > Objects` folder is an example cutscene for working with the Cutscene System and some helper markers to assist with character placement in cutscenes

## Attribution
All sprites and most code contained in this repository was created by Toby Fox and Royal Sciences LLC.
