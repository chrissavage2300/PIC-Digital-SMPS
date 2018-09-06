# PIC-Digital-SMPS
This is a digital SMPS that I designed with current sensing capablitlies. It is powered from a PIC18F13K22, but any PIC will work that has the same pinout. The PIC runs at 64Mhz to output a 250Khz signal used in half bridge mode. 
Input: 15V Max
Output: Not tested, but 0 to 15V
Iout(max):Not tested, 2A

Has spare outputs for Red,Green,and Blue LEDs. 
UART/I2C Connectors for board to board communications
PIC16F series with 16Bit PWM should work as well. 

Note: Current schematic (9/4/2018) has PGC and PGD reversed on the programming side. Just reverse the connections with a wire and it will work.


![Schematic](https://raw.githubusercontent.com/chrissavage2300/PIC-Digital-SMPS/master/PICSMPS.png)
0
