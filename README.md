# AVR DB/DD Breakout


This little Board is designed to allow for easy experimentation with AVR128DB32 and AVR64DD32 Microcontrollers.
It is very minimalist with only the AVR itself, A pair of standard LDO linear regulators (1117-5V and a 2112-3.3V), A simple power indicator and some jumpers for configuring the board and/or VDDIO2 to 3.3V or 5V.
Note: This relies on the Internal Oscillator which on the new generation of AVR chips can achieve pretty high speeds.

Both the DB and DD work. The DD is more suitable as a general purpose and is fairly cheap (comparable to a ATMega32PB), while the DB is more for bigger stuff. As one might guess by having up to a whopping 128Kb of Flash for code.