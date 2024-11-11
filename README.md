![365181](https://github.com/user-attachments/assets/07e60848-c171-467c-a46d-5e1adaecd15e)
# ScummVM360
ScummVM emulator port for XBox360
by A600

ScummVM is a collection of game engine recreations. Originally designed to play LucasArts adventure games that use the SCUMM system (the VM in the name stands for virtual machine), it now also supports a variety of non-SCUMM games by companies like Revolution Software and Adventure Soft. It was originally written by Ludvig Strigeus.

ScummVM is a reimplementation of the part of the software used to interpret the scripting languages such games used to describe the game world rather than emulating the hardware the games ran on; as such, ScummVM allows the games it supports to be played on platforms other than those for which they were originally released.

This is a ScummVM port for the Xbox 360, possible thanks to the hard work of
the ScummVM team, the SDLx360 libs by Lantus and the XBDM plugin by Natelx.

It features all the 1.4.1 supported engines, MP3, Vorbis, Flac, AAC,
FluidSynth (tested with up to 250 MB soundfonts) and the MT-32 emu.

The file xbox.patch is the diff patch against the 1.4.1 branch
https://github.com/scummvm/scummvm.git

IMPORTANT NOTE
-------------
Don't use the Guide button because the Xbox 360 will probably hang.

CONTROLS
--------
Left Analog -> Move Cursor

Dpad -> Arrow keys. In the select game dialog, left=pgup, rigth=pgdown

A -> Left Button

B -> Right Button

X -> Escape

Y -> Enter. In Lands of Lore, attack button for all party members (F1+F2+F3)

Back -> R (Rest party in Lands of Lore)

Start -> ScummVM Menu

Left Trigger -> Increases cursor speed while pressed. In Lands of Lore, turn left

Right Trigger -> Decreases cursor speed while pressed. In Lands of Lore, turn right

Left Shoulder -> F5

Right Shoulder -> Virtual Keyboard

Right Analog -> Numeric keypad as shown below

Right Analog Thumb -> KP5


7 8 9

\ | /

4 - 5 - 6

/ | \

1 2 3


SCREEN
------
The xResizer.xex included allows to resize the screen for those with overscan problems.
It generates an xbox.cfg with these default settings:

xpos=0

ypos=0

xstretch=0

ystretch=0

NOTE: for a pixel perfect screen with correct aspect ratio these values
and the 3x* scalers should be used:

xpos=160

ypos=0

xstretch=-320

ystretch=0
