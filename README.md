# MacroCard-LP
A credit card sized PCB made for an 8 Key Macropad powered by a Raspberry Pi Pico

# Parts Needed:
- 8x Kailh Low Profile Choc Switches (any Low Profile Choc switch you desire)
- 8x Kailh Low Profile Choc Hotswap sockets
- 1x Raspberry Pi Pico
- 2x 20 male header pins
- 2x 20 female header pins

# Why I chose these parts
- Raspberry Pi Pico is cheap and flexible in terms of what Pin headers and it supports Python, C, and Arduino
- Male and female headers since I don't want to solder the parts directly onto the PCB and make more space for additional keys
- Kailh LP switches since I wanted a low profile macropad.


# Instructions
1. First solder the Kailh hotswap sockets to the back. An easy way to do it is to put solder on one side of the PCB contact, then solder one side and then the other afterwards.
2. Put Male headers (long side) on breadboard and afterwards put the pico on the pins and solder. We do it this way to ensure the header pins are straight.
3. Put the Female header pins onto the pico pins, align it with the back of the PCB (where there is an image of a person and solder the Female headers in place.
4. To code the Pico, pick a programming language to use and code!

I will provide example code for CircuitPython.
