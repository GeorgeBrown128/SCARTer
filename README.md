# SCARTer
Over-engineering a multi-way SCART source switcher for retro consoles.

Note this project is currently in active development.

A 12-input, 3-output SCART RGB crosspoint switch. Designed to deliver signals from an array of consoles to the two TVs and a capture card in my retro games setup.

The system can copy the signal from any one source to all three outputs without loss of signal integrity, or send different inputs to each output, or any combination inbetween.

Switching is performed by the [FMS6501 12x9 video switch matrix IC](http://www.onsemi.com/PowerSolutions/product.do?id=FMS6501  "Chip data page"). The system is controlled by two ATMEGA328s, one in the remote switching matrix and another in user input control box.
