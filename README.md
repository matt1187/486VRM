# Project  486VRM.
A interposer for  3.3V 486  for using on motherboard without 3.3V regulator.
A advantage of this  486VRM interposer: switching regulator instead linear regulator. -> less heating.

# PCB Revision History
- 000 initial draft
- 001 smaller pcb size, current limit resistor added for Intel DX4 I/O buffer (pin J1), added solder help

# Feartures
- Vcore can be adjusting with jumper: 3.3V,  3.45 and 4V
- Clock-Multi jumper (for some DX4 and AMD/Cyrix 5x86)
- Writeback L1 jumper 
- connector for fan, 5V
  
![grafik](https://github.com/matt1187/486VRM/assets/155289528/ef8d5e7e-0f1a-4025-8efc-ea1d19ef5248)



# Pictures & how to soldering of pin
- I use "BGA"-technologie on this interposer.
![grafik](https://github.com/matt1187/486VRM/assets/155289528/72c69535-1fac-49f1-8d76-10e1ec1bf26c)![grafik](https://github.com/matt1187/486VRM/assets/155289528/73b5ebf2-bc49-44dc-86fa-6407342b29bc)
- using of solder paste is very recommend.
- you need solder iron with long and small chisel for extra adding of tin to socket.

![grafik](https://github.com/user-attachments/assets/123b4d15-7852-4772-8d2f-c6b759e4cc3e)

- "solder helper hold pin (bottom) on their place.
- very recommend: solder only one row with pin to pcb, then second row, then third row.


# Bill of material
[![Gerber data 001](https://github.com/matt1187/486VRM/blob/main/486VRM/Gerber/vrm_001.zip)




|Footprint|Count|Value|Supplier|Order-number|
|--------------|----|-----|-------|-----------------|
|Top1|1|486|various|PGA-168 486 168pin socket|
|Bot1|1|486|various| turned pin header, dia =0.5mm|
|JP1|1|WB/WT|Digikey|609-78511-203HLF-ND|
|JP2|1|voltage|Digikey|609-78511-203HLF-ND|
|JP3|1|CLKMUL|Digikey|609-78511-203HLF-ND|
|JP4|1|FAN|Digikey|609-78511-203HLF-ND|
|U1|1|TPS54308DDCR|Digikey|296-47880-1-ND|
|R1|1|50Ω|Digikey|541-CRCW080550R0FKTACT-ND |
|R2|1|100kΩ|Digikey|311-100KARCT-ND |
|R3|1|22kΩ|Digikey|311-22KARCT-ND|
|R4|1|430kΩ|Digikey|311-430KARCT-ND |
|R5|1|91kΩ|Digikey|311-91KARCT-ND |
|R6|1|100Ω|Digikey|603-RC0805JR-07100RL|
|C4,C3,C2,C1|4|10µF|Digikey|399-C1206C106M3PAC7210CT-ND |
|C6|1|75pf|Digikey|478-3743-1-ND|
|C10,C9,C8,C7,C5|5|0.1µF|Digikey|KGM21NR71H104KT|
|C11|1|47µF|Digikey|T491C476M010AT|
|L1|1|10µh|Digikey|LMLP07A7M100DTAS |


# License
The project is free for non-commercial reproduction. Do not sell it on Ebay or other platforms for profit. Do not make a closed source derivative. Share your experiences and ideas with the community.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
