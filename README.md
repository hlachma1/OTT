# OTT (WW1 Kaizo roguelike)

**FOR KING AND COUNTRY** 

You are one soldier of a British infantry battalion in an attack on the German line,
between December 1914 and September 1915: over the top, across no-man's-land,
through the wire and into their trenches. 

It is turn-based and played with the keyboard, drawn in letters or in its own
WW1 tiles. OTT is a total conversion of the roguelike Sil-Q (see the credits
below).

Use the numberpad to move your character in the cardinal directions.

F or f aims and fires the rifle. B or b cycles the bolt. R reloads.

G or g readies a grenade. T or t throws the grenade; select your target square using the numberpad.

If you are wounded and capable of bandaging yourself, H or h begins the process of applying a dressing. Keep pressing it to finish the process.

C is a quick step which may put enemies at a disadvantage when closing distance in the trench.

Should doubt set in, remember that your betters have decided that this fate for you and that dissent is proscribed. 


## Download and play

The builds are on the [Releases](https://github.com/soundovision/OTT-WW1/releases)
page: `OTT-<version>-windows.zip` and `OTT-<version>-macos.zip`. Each holds the
game, [PLAYING.md](PLAYING.md) (how to play — read it first), this README and
the licence.

- **Windows:** unzip the whole `OTT-windows` folder anywhere and double-click
  **Play OTT.bat** to play in letters, or **Play OTT (Tiles).bat** to play
  with the WW1 tiles.
- **macOS:** unzip `OTT-macos` and open **OTT.app** (letters) or
  **OTT (Tiles).app** (the tiles). The first time, macOS will not open an app
  from the internet that Apple has not checked; PLAYING.md says how to let it.

You can also switch between letters and tiles from the game's own menu;
PLAYING.md explains how.

## Building from source

OTT builds with CMake and a C compiler on Windows (MSYS2/MinGW), macOS and
Linux:

```sh
cmake -G Ninja -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build
```

That makes `build/OTT.exe` on Windows, `build/OTT.app` on macOS, and
`build/ott` on Linux (run it from the repository root, as `./build/ott`: it
needs `./lib`). For the terminal build on macOS add
`-DSUPPORT_COCOA_FRONTEND=OFF -DSUPPORT_X11_FRONTEND=OFF
-DSUPPORT_GCU_FRONTEND=ON` and run `./build/ott -mgcu`.

## Credits

OTT is built on **Sil-Q**, by the Sil-Q developers and community
(<https://github.com/sil-quirk/sil-q>), which grew out of **Sil** (© half &
Scatha). Sil descends, through NPPAngband, from
**Angband** and Moria (© Ben Harrison, James E. Wilson and Robert A.
Koeneke). The engine underneath OTT is theirs, and OTT would not exist without
it. The fonts are credited in
[lib/xtra/font/copying.txt](lib/xtra/font/copying.txt).

OTT was created with significant help from an internet figure, whose identity I am withholding pending his permission.

## Licence

Like Sil-Q, OTT is free, open source and non-commercial. You may redistribute
it and/or modify it under either the GNU General Public License, version 2, or
the Angband licence, with the exceptions listed in [LICENSE.md](LICENSE.md).
