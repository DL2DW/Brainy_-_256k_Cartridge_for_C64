# BRAINY - 256K Cartridge for Commodore C64

![](https://github.com/DL2DW/Brainy_-_256k_Cartridge_for_C64/blob/main/Images/Brainy_Cartridge.jpg)

This is a replica of a 256kByte EPROM card for the Commodore C64. 

The magazine "64er" summarized the whole thing in its conclusion as follows:

#### "Brainy is a new generation EPROM module card. In contrast to the module cards presented so far, every EPROM memory space is used. Brainy is recommended to any beginner or advanced user who is tired of waiting an eternity for loading longer programs from floppy disk. The included floppy disk contains a very clear module generator, which automatically makes all the necessary settings for the card."



## Assembly

The card consists entirely of parts for through-hole mounting. Some resistors and capacitors and a diode are below the ICs. 

Due to the given size of the original board, the components are placed very close to each other. 

However, according to the level of difficulty, even an ambitious beginner should have no major problems assembling the board.

The components are all quite common and should be available in any better electronics store.



## BOM

Here now the parts list. The last position with the Winbond W27C512 is only a recommendation. EPROMs in other sizes can also be used. However, the Winbond EEPROMs are unbeatable cheap at the moment.



| Quantity | Designator                                      | Manufacturer 1      | Manufacturer  Part Number 1 | Description                                                  |
| -------- | ----------------------------------------------- | ------------------- | --------------------------- | ------------------------------------------------------------ |
| 11       | C1,  C2, C3, C4, C5, C6, C7, C10, C11, C12, C13 | Kemet               | C320C104K5R5TA7305          | Ceramic  Disc Capacitors 100nF -20%~+80% 50V Through Hole,P=2.54mm RoHS |
| 1        | C8                                              | KEMET               | C315C221J5G5TA              | Keramischer  Scheibenkondensator, bedrahtet. Für Printmontage, Rastermaß 2,5 mm. |
| 1        | CP1                                             | KEMET               | T378E106K025AS              | Tantalum  Capacitors - Solid Leaded 25volts 10uF 10%         |
| 1        | D1                                              | NXP  Semiconductors | 1N4148                      | NEXPERIA  - 1N4148 - DIODE, 1N4148 AMMO-BOX 10K              |
| 1        | D2                                              | Wurth  Electronics  | 151033RS03000               | WURTH  ELEKTRONIK  151033RS03000  LED, 3MM,   RED, 2600MCD, 621NM |
| 1        | Q1                                              | Diotec              | BC547C                      | BC547C  Diotec Bipolar NPN Transistor 45V                    |
| 1        | Q2                                              | Diotec              | BC557C                      | Trans  GP BJT PNP 45V 0.1A Automotive 3-Pin TO-92 T/R        |
| 3        | R1,  R2, R3                                     | Yageo               | CFR-25JB-52-10K             | RES  10K OHM 1/4W 5% AXIAL                                   |
| 1        | R4                                              | Yageo               | CFR-25JB-52-22K             | RES  22K OHM 1/4W 5% AXIAL                                   |
| 1        | R5                                              | Yageo               | CFR-25JB-52-390R            | RES  390 OHM 1/4W 5% AXIAL                                   |
| 1        | SW1                                             | TE  Connectivity    | 1-1825027-1                 | SWITCH  TACTILE SPST-NO 0.05A 24V                            |
| 1        | U1                                              | Texas  Instruments  | SN74LS00N                   | IC,  74LS, 74LS00, DIP14, 5.25V                              |
| 1        | U2                                              | ON  Semiconductor   | SN74LS155N                  | Decoder/Demultiplexer  Single/Dual 3/2-to-8/4 16-Pin PDIP    |
| 1        | U3                                              | Texas  Instruments  | SN74LS174N                  | Flip  Flop D-Type Bus Interface Pos-Edge 1-Element 16-Pin PDIP Tube |
| 1        | U4                                              | Texas  Instruments  | SN74LS04N                   | IC  HEX INVERTER 14-DIP                                      |
| 1        | U5                                              | Texas  Instruments  | SN74LS11N                   | IC  GATE AND 3CH 3-INP 14DIP                                 |
| 1        | U6                                              | Texas  Instruments  | SN74LS86AN                  | IC  GATE XOR 4CH 2-INP 14-DIP                                |
| 4        | U10,  U11, U12, U13                             | Winbond             | W27C512-45Z                 | IC  EEPROM 512KBIT 45NS 28DIP                                |



## PCB

The PCB can either be ordered directly from [PCBWay](https://www.pcbway.com/project/shareproject/BRAINY___256K_Cartridge_for_Commodore_C64.htmll), or you can create it yourself from the Gerber files available here.

[![PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/BRAINY___256K_Cartridge_for_Commodore_C64.html)





If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)



# License

The contents of this repository, with the exception of the Software directory, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/Brainy_-_256k_Cartridge_for_C64/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
