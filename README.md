# Kallebol-fanout-board
PCB to fan out and io expand the computers GPIO for the rotating Kallebol assembly

The GPIO of the kallebol computer was to slow for I2C. This board did not work and was replaced with a Raspberry Pi Pico instead.  

Features: 
~~* UART for elevation control~~
~~* I2C bus ~~
~~* I2C temp sensor~~
~~* I2C 16 bit IO expander~~
~~* Coax switch control ~~
~~* 2x 12V outputs to drive LNB + 1.3 GHz LNA block. ~~
~~* PTT input to computer ... for future TX use. ~~
~~* 12V -> 5V linear regulator, don't use this to power anything power hungry. ~~
~~* 5V -> 3.3V linear regulator, don't use this to power anything power hungry.    ~~
~~* 2x Female RS232 ports (might need to be male in rev 2 ...) ~~
~~* Way too many resistors, all should not be mounted.~~
~~* Way too many screw terminals ~~
~~* Chinesium (TM) voltmeter to monitor incoming 12V. ~~

DC load: 
* Computer, 12V 5A peak 
* 10.5 GHz LNB, 12V ?A
* 1.3 GHz LNA, 12V ?A

Board2Pdf & jlcpcb plugin used in KiCad project. 
