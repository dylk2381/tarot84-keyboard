# tarot84-keyboard
An 84-key 65%+numpad keyboard. Name is just something I decided like 95% of the way through :P.

## A note
I am actually unsure if this works properly at the moment. I am planning on ordering some prototype PCBs whenever some of the components come back in stock. As of now, this is just a fun side project that I decided to throw up on github. This is my first time designing *any* PCB.

## Specifications
 - 84 keys
 - Alpha, Numbers, Numpad, Nav keys
 - Supports MX-Style switches (3pin or 5pin)
 - Supports QMK (Not sure about any alternatives, should be anything compatible with the ATMEGA32U4-A)
 - Soldered

## Component List
NOTE: All of the components on this list are just what I have found, they should work with anything that is equivalent.
 - 1x ATMEGA32U4-A TQFB Package Microcontroller
 - 84x YFW 1N4148WS Diodes
 - 2x CL21C220JBANNNC Capacitors
 - 2x 0805W8F220JT5E Resistors
 - 3x C0805C104K3REC7800 Capacitors
 - 1x 0805B105K250NT Capacitor
 - 1x 0805X106K250NT Capacitor
 - 2x 0805W8F1002T5E Resistors
 - 1x X322516MLB4SI Crystal
 - 1x RS-187R05A2-DS MT RT Switch
 - 1x SM04B-SRSS-TB(LF)(SN) 4 Pin Connector

## Required Libraries
https://github.com/ai03-2725/MX_Alps_Hybrid
https://github.com/egladman/keebs.pretty
https://github.com/tmk/keyboard_parts.pretty
https://github.com/ai03-2725/Unified-Daughterboard
https://github.com/ai03-2725/random-keyboard-parts.pretty
https://github.com/tmk/kicad_lib_tmk

## Assembly
I believe everything on this board *should* be able to be hand soldered, albeit designed with just ordering assembly online in mind. If you are assembling, I would strongly recommend not relying entirely on the silkscreening.

## Additional Info
Screenshots are in the folder labelled "Screenshots." 
