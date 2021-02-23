# Dodger

A simple 2D game made in the Godot Engine where the player has to avoid being hit by asteroids for as long as possible.

![Dodger](https://i.imgur.com/lGzTklj.png)

You are a spaceship in this game, and your goal is to stay alive for as long as possible. As time goes on, the number of asteroids coming at you will increase, and, as the levels go up, the speed of the asteroid will also increase. The longer will stay alive, the more points you score. Fortunately, every once in a while, the game will give you one of two possible kinds of power-ups that you can use for a limited time: a shield or slow motion.

This game was made in the [Godot Engine](https://godotengine.org/), a "2D and 3D, cross-platform, free and open-source game engine released under the MIT license" that uses GDScript as its scripting language.

![Godot](https://i.imgur.com/PhBqFv8.png)

## Instructions

### Launching the Game

To start playing the game, download the binary release, run ```Dodger.exe``` and make sure ```Dodger.pck``` is in the same folder. When you launch the game for the first time, a ```save.json``` file containing the save information will be created in the same folder as the game files. This file can be edited in any text editor and contains your high score and highest level you got to. Don't cheat. :) You can start a new game by selecting the appropriate option in the main menu.


![Main Menu](https://i.imgur.com/N7N2nJj.png)

### Playing the Game

Once you've started a new game, all you have to do is stay alive for long as possible by avoiding getting hit by the asteroids. As time goes on, your score will go up, but so will the number of asteroids flying across the screen. Avoid them, and you will also start going up levels: the higher the level, the faster the asteroids. From time to time, the game will spawn power-ups that you can pick up to help you stay alive for longer.

![In-game](https://i.imgur.com/Fyakgsb.png)

You can either get a shield, which gives you invicibility for a limited time, or slow motion, which, as the name suggests, makes everything around you go slower in time. Should you get hit by an asteroid - and you will :) -, the game will be over and your score will be saved.

![Game Over](https://i.imgur.com/U3jEcrG.png)

If you start a new game, and in case you passed at least Level 1, you will be prompted to either start a new game from Level 1 or continue from the level you died at. However, if you choose the second option, the game won't save your score when you die. If you choose option one, you will have the chance to get a new high score by trying to stay alive for longer than you have before. Everytime you die, the game will save your score and the level you died at in case you beat your previous high score and high level. You can reset either your high score or your high level at any time in the main menu.

![New Game](https://i.imgur.com/kN8nMBc.png)

## Usage

In case you want to edit the game yourself, you will need to install the Godot game engine, which can be found on [the official website](https://godotengine.org/download) or on [Steam](https://store.steampowered.com/app/404790/Godot_Engine/). This project needs at least version 3.0.

![GDScript](https://i.imgur.com/upPkXPp.png)

## Contributing

The game is considered finished, so I won't be taking any suggestions to improve it any further. But feel free to report any bugs you find or to correct them yourself.

## Credits

The font used in the game is VP Pixel Simplified by [VP Type](https://www.myfonts.com/foundry/Val_Kalinic/). The sprites were made by me in [Aseprite](https://github.com/aseprite/aseprite). The sounds were generated in [Bfxr](https://www.bfxr.net/).

## License

MIT License

Copyright (c) 2021 Felipe Canever Fernandes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
