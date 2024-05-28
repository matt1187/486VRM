# Project  486VRM.
A interposer for  3.3V 486  for using on motherboard without 3.3V regulator.
A advantage of this  486VRM interposer: switching regulator instead linear regulator.

# PCB Revision History
- 000 initial draft
- 001 smaller pcb size, current limit resistor added for Intel DX4 I/O buffer (pin J1), added solder help

# Feartures
- Vcore can be adjusting with jumper: 3.3V,  3.45 and 4V
- Clock-Multi jumper (for some DX4 and AMD/Cyrix 5x86)
- Writeback L1 jumper 
- connector for fan, 5V
  
![grafik](https://github.com/matt1187/486VRM/assets/155289528/ef8d5e7e-0f1a-4025-8efc-ea1d19ef5248)



# Pictures
![grafik](https://github.com/matt1187/486VRM/assets/155289528/72c69535-1fac-49f1-8d76-10e1ec1bf26c)![grafik](https://github.com/matt1187/486VRM/assets/155289528/73b5ebf2-bc49-44dc-86fa-6407342b29bc)

# Bill of material
[![Gerber data 001](https://github.com/matt1187/486VRM/blob/main/486VRM/Gerber/vrm_001.zip)




|Footprint|Count|Value|Supplier|Order-number|
|--------------|----|-----|-------|-----------------|
|Top1|1|486|various|PGA-168 486 168pin socket|
|Bot1|1|486|various| turned pin header, dia =0.5mm|
|JP1|1|WB/WT|Mouser|649-78511-203HLF|
|JP2|1|voltage|Mouser|649-78511-203HLF|
|JP3|1|CLKMUL|Mouser|649-78511-203HLF|
|JP4|1|FAN|Mouser|649-78511-203HLF|
|U1|1|TPS54308DDCR|Mouser|595-TPS54308DDCR|
|R1|1|50Ω|Mouser|603-RC0402JR-0750RL |
|R2|1|100kΩ|Mouser|603-RC0805JR-07100KL |
|R3|1|22kΩ|Mouser|603-RC0805JR-0722KL|
|R4|1|430kΩ|Mouser|603-RC0805JR-07430KL |
|R5|1|91kΩ|Mouser|603-RC0805JR-0791KL |
|R6|1|100Ω|Mouser|603-RC0805JR-07100RL|
|C4,C3,C2,C1|4|10µF|Mouser|80-C1206C106M3P |
|C6|1|75pf|Mouser|581-08051A750J|
|C10,C9,C8,C7,C5|5|0.1µF|Mouser|581-08055C104K|
|C11|1|47µF|Mouser|80-T491C476M010|
|L1|1|10µh|Mouser|581-LMLP07A7M100DTAS |


# License
The project is free for non-commercial reproduction. Do not sell it on Ebay or other platforms for profit. Do not make a closed source derivative. Share your experiences and ideas with the community.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
