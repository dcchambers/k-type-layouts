# Input Club K-Type Configuration/Layouts
The K-Type Keyboard is an awesome, fully-programmable "75%/TKL" Keyboard from the good folks at [Input Club](https://input.club/)

![](https://input.club/wp-content/uploads/2016/01/k-type-600x400.jpg)

Fully-programmable means you can have the keys do whatever you want *at the firmware level*.
You don't need to run any software on your machine to get the extra features. The K-Type has 7 function
layers that you can map different keys to as well if you want to leave your base layer unchanged.

This repo contains some of my Input Club K-Type Keyboard configuration/layout files.

## iKBC (New) Poker II
The new-poker-ii directory contains a [KLL](https://input.club/kll/) firmware layout that emulates the
iKBR New Poker II keyboard layout + default function layer.

The iKBC New Poker II is a "60%" keyboard.
Press "f1+F2" (layer-1 key + F2 key) to enter the iKBC New Poker II mode. All this does is locks
the keyboard to a layer 2 I created which is a copy of the Poker II profile. To return your k-type
keyboard to default, press "f1+F2" again. This re-locks it to the main layer.

:warning: "f1" is the key labeled "Fn" on your keyboard - next to LAlt. "F1" is the key labeled "F1" on your keyboard.

:bulb: You can toggle the LED animation with "f1 (Fn Key) + F5" and "f1 (Fn Key) + F6".

## K-Type Mac Layout
Make your K-Type work better with your Mac!
- Swaps Left-Alt/Option with Left-Command.
- Replaces Menu with Left-Alt/Option.
- Replaces Left-Alt/Option with Left-Command.

## Flashing Your Keyboard
To use one of these layout profiles, clone this repository to your local machine and navigate
to the directory from whichever layout profile you want. Then follow
[the instructions](https://github.com/kiibohd/controller/blob/master/Documentation/Keyboards/K-Type.md)
to flash the firmware.
