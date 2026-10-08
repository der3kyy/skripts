# Anvil Repair

A Minecraft [Skript](https://github.com/SkriptLang/Skript) script that repairs anvils using iron blocks.

## Features
- Sneak and right-click a damaged or chipped anvil while holding the repair item.
- Repair anvils one damage stage at a time: damaged → chipped → undamaged.
- Animated repair with a progress bar, hand swings, block particles, and sounds for nearby players (48-block radius).
- Prevent multiple players from repairing the same anvil simultaneously.
- Configurable repair item, item cost, animation delay, and progress bar length.

## Requirements
- Minecraft Java Edition 1.21.10
- Skript 2.16.0

## Installation
1. Download [anvil-repair.sk](./anvil-repair.sk).
2. Place it in the server's `plugins/Skript/scripts/` directory.
3. Run `/sk reload anvil-repair`.

## Default settings
The script consumes **1 iron block per repair stage**. Each repair takes **3.5 seconds**, with a **10-segment progress bar**. Edit the `options` section at the beginning of the script to customize these values.

> The script has not been independently tested as part of this repository upload.
