**WTH is this...**

Shield/dock/whatever for [MiSTeryNano](https://github.com/harbaum/MiSTeryNano) project (nano tang 20k + M0S dock)  
Ports on this is just **MIDI-out** and **Joystick** only (no level shifters for mice)  
Resistors R1/R2 may need different values
100% THT so low cost to produce  

**WARNING**

YMMV _check_ before use, proceed with caution etc etc as I may have messed/missed something there...

**Thanks**

To [Till](https://github.com/harbaum/) for patiently answering my tech questions!

**BOM**

| ﻿Designator | Footprint                                                                                | Quantity | Value             |
| ------------- | ---------------------------------------------------------------------------------------- | -------- | ----------------- |
| C1            | C_Disc_D5.0mm_W2.5mm_P5.00mm                                                             | 1        | 100n              |
| J1, J3        | PinSocket_1x20_P2.54mm_Vertical                                                          | 2        | Conn_01x20_Socket |
| J2            | DSUB-9_Male_Horizontal_P2.77x2.84mm_EdgePinOffset7.70mm_Housed_MountingHolesOffset9.12mm | 1        | Joy               |
| J4            | PinSocket_2x06_P2.54mm_Horizontal                                                        | 1        | M0S               |
| J5            | MIDI_DIN5                                                                                | 1        | MIDI OUT          |
| R1, R2        | R_Axial_DIN0207_L6.3mm_D2.5mm_P10.16mm_Horizontal                                        | 2        | 100               |

R1/R2, C1 and MIDI (out) port not requred if you don't use MIDI

11/12/2025
Updated with fabrication files for [JLCPCB](https://jlcpcb.com/) 
nanoshield.zip as gerber file, bom.csv as BOM, positions.csv as CPL files (all of them into 'production' folder)
also note headers not visible on JLC's site - not big deal IMHO


