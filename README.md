# ATtiny406_Board
PCB Design Files for ATtiny406 Board

This board design is a variant of a board design that is found in the blog link below.

https://www.omzlo.com/articles/baremetal-programming-on-the-tinyavr-0-micro-controllers

The board features fairly easy to hand solder components, such as a SOIC20 IC and 0805 resistors, capacitors and LEDs, and it is breadboard friendly (100 mil spacing pin headers) with an orderly pin arrangement (PA0->PA7, PB0->PB5, and PC0->PC3). 

The programming connector is a standard FTDI USB-UART adapter pin-out. Since most FTDI USB-UART cables have different voltage for the Vcc and Vttl (such as the TTL-232R-3V3), a solder jumper (JP1) is open by default. The board can be powered from the breadboard pin headers or the FTDI programming header if the the jumper JP1 is closed. Using an FTDI TTL-232RG-VIP USB-UART requires the jumper JP1 to be closed so that the TTL-232RG-VIP adapter TTL voltage (Vttl) would be the same as the Vcc.

The board file ATtiny406.kicad_pcb uploads with no issues at the OSHPARK website. 

The Bill of Materials is also included (see file ATtiny406BOM.csv).

![Image](https://github.com/DCelectronics/ATtiny406_Board/blob/main/AT406BRD_Front.png)

![Image](https://github.com/DCelectronics/ATtiny406_Board/blob/main/AT406BRD_Back.png)
