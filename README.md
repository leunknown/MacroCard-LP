# MacroCard-LP
A simple credit card sized PCB made for an 8 Key Macropad powered by a Raspberry Pi Pico

## Parts Needed:
- 8x Kailh Low Profile Choc Switches (any Low Profile Choc switch you desire) (From MKUltra)
- 8x Kailh Low Profile Choc Hotswap sockets (From MKUltra)
- 8x Kailh Low Profile Choc Keycaps (regular MX style keycaps would not work) (From MKUltra)
- 1x Raspberry Pi Pico
- 2x 20 male header pins
- 2x 20 female header pins

## Why I chose these parts
- Raspberry Pi Pico is cheap and flexible in terms of what Pin headers and it supports Python, C, and Arduino
- Male and female headers since I don't want to solder the parts directly onto the PCB and make more space for additional keys
- Kailh LP switches since I wanted a low profile macropad.


## Instructions
1. First solder the Kailh hotswap sockets to the back. An easy way to do it is to put solder on one side of the PCB contact, then solder one side and then the other afterwards.![IMG_7957](https://user-images.githubusercontent.com/77712523/171341768-0776d308-3246-4034-9b1e-f852cffbe576.jpg)

2. Put Male headers (long side) on breadboard and afterwards put the pico on the pins and solder. We do it this way to ensure the header pins are straight.
3. Put the Female header pins onto the pico pins, align it with the back of the PCB (where there is an image of a person and solder the Female headers in place.![IMG_8024](https://user-images.githubusercontent.com/77712523/171342058-3aeecc59-2cc4-4654-93f4-8932512c4941.jpg)

4. Solder the rest of the SMD hotswap sockets by first tinning one pad, then placing the socket and heat up the part touching the tinned pad. Afterwards, solder the other pad. Repeat this process until all sockets are soldered on.
5. To code the Pico, pick a programming language to use and code!

## Final Product
![IMG_7959](https://user-images.githubusercontent.com/77712523/171341813-d8d13c89-b715-4efe-856f-5eebdebda715.jpg)

## MISC
- I like getting parts from MKUltra as their parts are cheaper and relatively more resonable than other vendors. (unless you want to wait for a month from AliExpress)
