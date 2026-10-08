# Don't Touch the Spikes

A TIC-80 remake of *Don't Touch the Spikes* built in Lua, with additional game modes, difficulty settings, and powerups.

## Features

- Horizontal bird movement with gravity and jump controls
- Randomized spikes along the walls
- Moving spikes in an alternate game mode
- An AI-controlled bird that tracks the player in an alternate game mode
- Candy pickups that award bonus points
- A spike-remover powerup
- Easy, medium, and hard difficulty settings
- Score and high-score tracking
- Increasing spike count as the score rises

## Files

- `game.lua` — game logic and embedded TIC-80 assets
- `std/strict/init.lua` — Lua strict-variable support used by the game

## Running

Open `game.lua` in TIC-80. The `std/strict/init.lua` file should be available in the TIC-80 filesystem so the game's `require 'std.strict'` call can load it.

From a TIC-80 installation with filesystem support, you can also start TIC-80 with the repository directory mounted and load the game from there.

## Controls

The game uses the TIC-80 controller for selecting options and controlling the bird.
