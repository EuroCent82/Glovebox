<p align="center">
  <img src="screenshot/banner-readme.png" alt="Glovebox, a PineLoader mod">
</p>

<p align="center">
  <a href="#the-compartment">The compartment</a>
  &nbsp;·&nbsp;
  <a href="#mod-manager">Mod Manager</a>
  &nbsp;·&nbsp;
  <a href="#key">Key</a>
  &nbsp;·&nbsp;
  <a href="#the-loader">The loader</a>
  &nbsp;·&nbsp;
  <a href="#install">Install</a>
  &nbsp;·&nbsp;
  <a href="#save">Save</a>
  &nbsp;·&nbsp;
  <a href="#game-047">Game 0.4.7</a>
  &nbsp;·&nbsp;
  <a href="#author">Author</a>
</p>

<p align="center">
  A PineLoader mod for Pionero Capital.<br>
  In a vehicle it opens a glovebox, separate from the trunk.<br>
  The contents stay saved.
</p>

<p align="center">
  <a href="LICENSE"><img alt="Apache License 2.0" src="https://img.shields.io/badge/license-Apache%202.0-D5B41A?style=flat-square"></a>
  <a href="https://github.com/EuroCent82/PineLoader/releases/latest"><img alt="PineLoader 1.0.1" src="https://img.shields.io/badge/PineLoader-1.0.1-04221a?style=flat-square"></a>
  <img alt="Version 1.0.0" src="https://img.shields.io/badge/version-1.0.0-245C48?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/Glovebox/releases/latest"><img alt="Download 1.0.0" src="https://img.shields.io/badge/download-1.0.0-D5B41A?style=flat-square"></a>
</p>

The loader is [PineLoader 1.0.1](https://github.com/EuroCent82/PineLoader/releases/latest). The same guide is on [PineLoader.dev](https://pineloader.dev) and [PineLoader.de](https://pineloader.de). This repository holds the Glovebox release. The pictures below are the German game. The labels follow the language of the game.

## The compartment

K opens the glovebox from any seat. The upper row is the compartment. The lower row is the inventory you are carrying. The two are separate, and the glovebox is not the trunk.

<p align="center">
  <img src="screenshot/handschuhfach.png" alt="The glovebox row above the inventory you are carrying" width="683">
</p>

## Mod Manager

The row is named in the game's language. In German it reads Handschuhfach. An turns it on, Aus turns it off. Turning it off leaves the saved items where they are.

<p align="center">
  <img src="screenshot/mod-manager.png" alt="Handschuhfach switched on in the Mod Manager" width="770">
</p>

## Key

The gear on that row opens the key page. The key is captured the same way as on the keyboard tab. The default is K. Close and Apply use the game's own words.

<p align="center">
  <img src="screenshot/taste.png" alt="The glovebox key page, set to K" width="422">
</p>

## The loader

PineLoader lists the mod before the game starts. In this window both mods were found and both were loaded. Start game here, or press Play in Steam.

<p align="center">
  <img src="screenshot/loader.png" alt="PineLoader ready, with two mods loaded" width="640">
</p>

## Install

Install PineLoader first, then Glovebox. The same steps are in [instructions.txt](instructions.txt).

### PineLoader

1. Download [PineLoader 1.0.1](https://github.com/EuroCent82/PineLoader/releases/latest). The file is `PineLoader-1.0.1-win-x64.zip`.
2. Unpack it into a folder named `PineLoader` next to the game, so the program is `Pionero Capital\PineLoader\PineLoader.exe`.
3. Close the game and start `PineLoader.exe` once. The loader saves the official file as `PioneroCapital-Win64-Game.exe` and points `PioneroCapital-Win64-Shipping.exe` at itself.
4. Leave the Steam launch options empty. **Play** in Steam starts PineLoader first.

### Glovebox

1. Download [Glovebox 1.0.0](https://github.com/EuroCent82/Glovebox/releases/latest). The file is `Glovebox-1.0.0.zip`.
2. Copy the `Glovebox` folder from that zip into `PineLoader\Mods`. The two files are `Glovebox.dll` and `glovebox-agent.jar`.
3. Start the game through PineLoader. The loader writes `Config\Glovebox.ini` when that file is missing.

The default key is K, from any seat.

## Save

Saved items are in `PineLoader\Cache\glovebox.json`. Leave that file in place if you want to keep them. Each vehicle keeps its own number of slots.

## Game 0.4.7

Pionero Capital 0.4.7, Steam build 26637959, renamed the server classes this build calls. On that build the glovebox does not open yet.

## Author

EuroCent82. The site is [PineLoader.dev](https://pineloader.dev) and [PineLoader.de](https://pineloader.de). PineLoader is [release 1.0.1](https://github.com/EuroCent82/PineLoader/releases/latest). Glovebox is [release 1.0.0](https://github.com/EuroCent82/Glovebox/releases/latest).

## License

Apache License 2.0. The full text is in [LICENSE](LICENSE).

The Nexus Mods header is [screenshot/banner-nexusmods.png](screenshot/banner-nexusmods.png), 1300 by 372.
