# Quad Serial 

Quad Serial is a project with four serial ports. The goal is to provide a way to get rid of that low quality USB - RS-232 cables by using a well know FT4232HL from FTDI.

# List of possibilities:
* 3 RS-232 COM port (2 of them ISOLATED + 1 non-isolated and shared with one UART)
* 2 Any level UARTs, you can use them anywhere from 1.8V to 5V

### Final product
![Preview](https://github.com/PY1CX/Quad-Serial/blob/master/HW%20v1.0/Output%20Files/Final_Front_Low.jpg?raw=true)
### 3D render of the Quad Serial
![Preview](http://i.imgur.com/0ZsWIK9.png)

# Next Version:
* Make possible to change between Female or Male connector without hacking the board with wires just by adding 0R resistors to it, so you can choose Male or Female connectors while doing the assembly.
* Put the I/O on the FTDI chip that aren't beeing used on 0.1 inch (2.54mm) headers so you can hack they out with the FTDI API. It's a nice feature over there and you can use without wire hacking the chip.

# Change log:
07/02/2018 - All V1.0 Hardware and Output files on your own folder so I can make some changes for v1.1 on another folder
