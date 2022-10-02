# NoTwive (previously Twive International)
Based on [Twive Simplified](https://github.com/fractalysid/Twive_Simplified). Read Twive README for more info.

Well, this could no longer be referred to as Twive, so NoTwive should do the trick.

ZMK config files for the [Lucy](https://github.com/fractalysid/Lucy-Keyboard) v0.2 keyboard.
I couldn't manage to make the github action workflow work so it must be manually compiled.
A sample bash script to compile the firmware is provided, compile_example.sh. Remember to edit it modifying the variables.

[Here](https://github.com/fractalysid/qmk_firmware) you can find my fork of [QMK](https://github.com/qmk/qmk_firmware) with the layout for the ferris sweep (it is a modified version where the keys in the right half are in reverse order). You can also find the keymap.json in the QMK directory.

## Goals
Twive Simplified was designed with the italian language in mind. NoTwive, aka Twive International,
wants to be a good base layout for any language. At the cost of having 2 layers accessible
through the home row, this layer fixes every drawback encountered in Twive Simplified.

## Design principles and differences with Twive Simplified
- 2 layers accessible through the home row
- A layer for international keys. It should fit almost every common european language
- A layer with numbers, operators, ',', '.' and other common symbols used in programming languages
- As I prefer using the one shot modifiers in the Utility layer, I'm keeping the modifiers in the bottom row and shift in the home row

### Details about layers and modifiers triggering
- Modifiers: Positional hold-tap, "tap-preferred" with 160ms tapping term
- Utility layer: default layer-toggle timings
- Numbers and Symbols layer: "Balanced" with only 125ms tapping term for quick access while typing text

![NoTwive Layout](https://github.com/fractalysid/Notwive/blob/main/Notwive.png?raw=true)
