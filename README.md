# Microcontroller-SystemVerilog
8-bit microcontroller for FPGA, written in SystemVerilog.
A small program for blinkning a LED when a button gets pressed is implemented in machine code.

There are two clock sources available, a 50 MHz system clock for regular use and a manual clock implemented by pressing down a button.
When manual clock source is used, current operation code and the content of CPU register R16 is displayed via five 7-segment displays. 
The address pointed to by the program counter is also displayed in binary form via eight LEDs on the FPGA card.
The documentation is written in Swedish.

The PINs are assigned for FPGA card Altera DE0 (device Cyclone V - 5CEBA4F23C7).
The code was written between 2022-07-13 - 2022-07-15 by using Intel Quartus Prime 18.1.
Download the Quartus Prime Archive File file mcu.qar to open the entire project in Quartus.
