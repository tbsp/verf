# verf

verf is a simple paint toy, written in Tal.

To run this program you'll need a Uxn emulator.

To assemble the rom yourself, use the Uxn assembler, or you can download a pre-compiled release.

    uxnasm verf.tal verf.rom
    
There's no way to load/save images. .theme file support is included.
    
# Controls

verf supports a variety of controls. The gamepad+touch controls will activate on any mouse activity (movement/touch/scroll), but can be turned off again by pressing B (DS/3DS) if you'd like to use pure gamepad controls.

## Mouse

* `mouse1`: paint
* `mouse2`: erase
* `mouse wheel`: adjust brush size
* `shift+wheel`: adjust brush shape
* `ctrl+wheel`: adjust opacity

## Keyboard

* `1-4`: set brush size
* `q/w/e/r/t/y`: set brush shape
* `-/=`: adjust opacity
* `d`: toggle decay
* `c`: clear canvas
* `h`: toggle HUD

## Gamepad Common Controls

* `Start`: Toggle decay
* `Select+down`: cycle brush size
* `Select+up`: cycle brush shape
* `Select+left/right`: adjust opacity
* `Select+A`: clear canvas

## Gamepad only (GBA)

* `dpad`: move cursor
* `A/ctrl`: paint
* `B/alt`: erase

## Gamepad with touch (DS/3DS)

* `dpad up`: hold to erase when painting
* `dpad down`: cycle brush size
* `dpad left/right`: adjust opacity
* `B`: switch back to pure gamepad controls


