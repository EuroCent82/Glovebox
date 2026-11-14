<p align="center">
  <img src="screenshot/banner-readme.png" alt="Glovebox, a PineLoader mod">
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/Glovebox">GitHub</a>
  &nbsp;·&nbsp;
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
  <a href="#the-seller">The seller</a>
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
  <a href="https://github.com/EuroCent82/Glovebox"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-EuroCent82%2FGlovebox-245C48?style=flat-square"></a>
  <a href="LICENSE"><img alt="Apache License 2.0" src="https://img.shields.io/badge/license-Apache%202.0-D5B41A?style=flat-square"></a>
  <a href="https://github.com/EuroCent82/PineLoader/releases/latest"><img alt="PineLoader 1.0.1" src="https://img.shields.io/badge/PineLoader-1.0.1-04221a?style=flat-square"></a>
  <img alt="Version 1.0.1" src="https://img.shields.io/badge/version-1.0.1-245C48?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/EuroCent82/Glovebox/releases/latest"><img alt="Download 1.0.1" src="https://img.shields.io/badge/download-1.0.1-D5B41A?style=flat-square"></a>
</p>

The loader is [PineLoader 1.0.1](https://github.com/EuroCent82/PineLoader/releases/latest). The same guide is on [PineLoader.dev](https://pineloader.dev). This repository holds the Glovebox release. The pictures below are the German game. The labels follow the language of the game.

## The compartment

K opens the glovebox from any seat. The upper row is the compartment. The lower row is the inventory you are carrying. The two are separate, and the glovebox is not the trunk.

<p align="center">
  <img src="screenshot/handschuhfach.png" alt="The glovebox row above the inventory you are carrying" width="683">
</p>

## Mod Manager

The Mod Manager is optional. Without it, the compartment still opens from the key and from `Config\Glovebox.ini`.

With the Mod Manager, the game settings gain a tab after Keyboard. The row is named in the game's language. In German it reads Handschuhfach. On and off use the same bar as VSync. Turning it off leaves the saved items where they are.

## Key

The key is the row under that switch. It uses the game's own key button. The default is K.

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

1. Download [Glovebox 1.0.1](https://github.com/EuroCent82/Glovebox/releases/latest). The file is `Glovebox-1.0.1.zip`.
2. Copy the `Glovebox` folder from that zip into `PineLoader\Mods`. The two files are `Glovebox.dll` and `glovebox-agent.jar`.
3. Start the game through PineLoader. The loader writes `Config\Glovebox.ini` when that file is missing.

The default key is K, from any seat.

## Save

Saved items are in `PineLoader\Cache\glovebox.json`. Leave that file in place if you want to keep them. Each vehicle keeps its own number of slots.

## The seller

At the seller, the vehicle card shows the places that belong to that vehicle. On the Royale the trunk line reads 6 places. The glovebox is not that line. Its own number of places stays with the vehicle in the save.

<p align="center">
  <img src="screenshot/dealer.png" alt="The Royale at the seller. The card lists a trunk of 6 places." width="420">
</p>

## Game 0.4.7

Pionero Capital 0.4.7, Steam build 26637959, uses different server class names than the build before it. This release calls those names. The compartment opens on that build, with or without the Mod Manager.

## Author

EuroCent82. The site is [PineLoader.dev](https://pineloader.dev). PineLoader is [release 1.0.1](https://github.com/EuroCent82/PineLoader/releases/latest). Glovebox is [release 1.0.1](https://github.com/EuroCent82/Glovebox/releases/latest).

## License

Apache License 2.0. The full text is in [LICENSE](LICENSE).

The Nexus Mods header is [screenshot/banner-nexusmods.png](screenshot/banner-nexusmods.png), 1300 by 372.
