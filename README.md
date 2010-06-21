Freetronics Power-over-Ethernet 35V Regulator
=============================================
Copyright 2010 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

Module to regulate power supplied on Power-over-Ethernet connection
down to a maximum of 12Vdc for supply to the on-board voltage regulator
in an Arduino Duemilanove, Freetronics TwentyTen, or other compatible
board using the Freetronics Ethernet Shield.

Features:

 * Adds Power-over-Ethernet "PD" (powered device) support to the
   Freetronics Ethernet shield.
 * Input voltage range 14-35Vdc.
 * Output voltage limited to 12V and fed to Arduino on-board voltage
   regulator via Ethernet shield for further regulation down to 5V.
 * Input protection diode to prevent damage due to reverse polarity.
 * Plugs directly onto Freetronics Ethernet Shield.
 * "Power on" LED.


More information is available at:

  http://www.freetronics.com/poe-regulator-35v

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> PoERegulator35V.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
