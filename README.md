# GLCD01 - MIP LCD display module

MLAB module for the [TN0181ANVNANN-GN00](doc/datasheets/MIP_LCD.pdf) square MIP (Memory-in-Pixel) LCD display. MIP displays retain the image without power, making them suitable for low-power applications. The display is connected via a 10-pin FPC connector (J2) and communicates over a 3-wire SPI interface (SCLK, SI, SCS).

The module includes a [MIC1557](https://www.microchip.com/en-us/product/mic1557) RC oscillator that generates the required VCOM polarity-reversal signal for the LCD, so no external signal source is needed. Power supply is 3.3 V via the standard MLAB 2×7 pin header (J1).

## Design

<img src="/doc/gen/img/GLCD01-top.png" width="40%"> <img src="/doc/gen/img/GLCD01-bottom.png" width="40%">

## Schematics

[![Schematics](/doc/gen/GLCD01-schematic.svg)](/doc/gen/GLCD01-schematic.pdf)
