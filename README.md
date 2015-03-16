# WebastoWBUSInterface

Hardware circuit and diagram for interfacing to the Webasto WBUS interface from a PC/Arduino

This small circuit allows you to connect a 5 volt device with a serial port to a Webasto Heater which communicates in the WBUS protocol.

The circuit expects you to connect a FT232R USB Serial to TTL interface, or a micro controller such as the Arduino.

Its a http://fritzing.org/home/ circuit/file so you can make a PCB from it if you want (not tested!).

It uses hardly any parts, costs less than £1 (GBP) to make.

Amount 	Part Type 	Properties
1 	Generic female header - 3 pins 	row single; hole size 1.0mm,0.508mm; pin spacing 0.1in (2.54mm); pins 3; form ♀ (female); package THT
3 	NPN-Transistor 	variant variant 2; type NPN (EBC); package TO92 [THT]; part # BC548 NPN
1 	Generic female header - 6 pins 	row single; hole size 1.0mm,0.508mm; pin spacing 0.1in (2.54mm); pins 6; form ♀ (female); package THT; part # FTDI BASIC
1 	Yellow (595nm) LED 	color Yellow (595nm); package 3 mm [THT]; 
1 	PNP-Transistor 	type PNP (CBE); package TO92 [THT]; part # BC557 PNP
4 	10kΩ Resistor 	bands 4; tolerance ±5%; pin spacing 400 mil; resistance 10kΩ; package THT
3 	1kΩ Resistor 	bands 4; tolerance ±5%; pin spacing 400 mil; resistance 1kΩ; package THT




Have fun!