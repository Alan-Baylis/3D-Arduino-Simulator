.::\ 3D Arduino Simulator /::.


0x00 the story

We're students in Bilkent University who like computers. We also like Arduino boards.

They told us to program something in Java this semester and gave us the freedom to try something cool.


0x01 "why another simulator?"

We're too lazy to mess with cracked copies of proteus to get a flexible simulation of primitive Arduino code with a few extra circuit components.

We envision a true 3D simulator which can be programmed with the Arduino IDE over a virtual USB port.
We envision a simulator which allows us to add an Arduino shield to the simulation space with no more effort than that to add an extra LED.

We're in efforts to:

- get the simulation running in a 3D engine like JMonkeyEngine

- support direct USB connection with the Arduino IDE & preload the virtual CPU flash with the bootloader

- support the serial interface, I2C communication etc.

- support the simulation of Arduino shields


Currently we're too busy with the emulation of the ATMega. Once that works, we'll have time to do useful things like the stuff listed above.
