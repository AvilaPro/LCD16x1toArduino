# LCD16x1toArduino
Arduino LCD Library 16x1

I recently found an character LCD display which was 16x1. But the strangest thing was that those 16 cols was divided by 2 a.k.a splited by half 8+8. So the default library couldn't work and i decided to make my own. In this library there are 2 separate functions for writing strings e.g for regular 16x1 and chinese 16x1 split to 2x8 columns in 1 row.

Wiring:

LCD RS pin to Arduino 12 LCD EN pin to Arduino 11 LCD R/W pin to GND LCD data bus 0 to 7 to Arduino Digital pins 0 to 7
