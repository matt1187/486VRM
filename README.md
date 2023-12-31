# Project  486VRM.
A interposer for  3.3V 486  for using on motherboard without 3.3V regulator.
A advantage of this  486VRM interposer: switching regulator instead linear regulator.

# Feartures
- Vcore can be adjusting with jumper: 3.3V,  3.45 and 4V
- Clock-Multi jumper (for some DX4 and AMD/Cyrix 5x86)
- Writeback L1 jumper 
- connector for fan, 5V
  
![grafik](https://github.com/matt1187/486VRM/assets/155289528/ef8d5e7e-0f1a-4025-8efc-ea1d19ef5248)

# PCB Revision History
- 000 initial draft
- 001 smaller pcb size, current limit resistor added for Intel DX4 I/O buffer (pin J1), added solder help

# Pictures
![grafik](https://github.com/matt1187/486VRM/assets/155289528/72c69535-1fac-49f1-8d76-10e1ec1bf26c)![grafik](https://github.com/matt1187/486VRM/assets/155289528/73b5ebf2-bc49-44dc-86fa-6407342b29bc)

# Bill of material
[![](gerber/486VRM.csv')](#bom)




|"Footprint"|"Case"|"Count"|"Value"|"Supplier"|"Order-number"|
|--------------|-------|----|-----|-------|-----------------|
|"Top1"|"PGA-168_socket"|1|"486"|various|PGA-168 486 168pin socket|
|"Bot1"|"PGA-168_pin"|1|"486"|various| turned pin header, dia =0.5mm|
|"JP1"|"PinHeader_1x03_P2.54mm_Vertical"|1|"WB/WT"|Mouser|649-78511-203HLF|
|"JP2"|"PinHeader_1x03_P2.54mm_Vertical"|1|"voltage"|Mouser|649-78511-203HLF|
|"JP3"|"PinHeader_1x03_P2.54mm_Vertical"|1|"CLKMUL"|Mouser|649-78511-203HLF|
|"JP4"|"PinHeader_1x03_P2.54mm_Vertical"|1|"FAN"|Mouser|649-78511-203HLF|
|"U1"|"SOT-23-6"|1|"TPS54308DDCR"|Mouser|595-TPS54308DDCR|
|"R1"|"R_0805_2012Metric"|1|"50"|Mouser|603-RC0402JR-0750RL |
|"R2"|"R_0805_2012Metric"|1|"100k"|Mouser|603-RC0805JR-07100KL |
|"R3"|"R_0805_2012Metric"|1|"22k"|Mouser|603-RC0805JR-0722KL|
|"R4"|"R_0805_2012Metric"|1|"430k"|Mouser|603-RC0805JR-07430KL |
|"R5"|"R_0805_2012Metric"|1|"91k"|Mouser|603-RC0805JR-0791KL |
|"R6"|"R_0805_2012Metric"|1|"100"|Mouser|603-RC0402JR-07100RL|
|"C4,C3,C2,C1"|"C_1206_3216Metric"|4|"10µF"|Mouser|80-C1206C106M3P |
|"C6"|"C_0805_2012Metric"|1|"75pf"|Mouser|581-08051A750J|
|"C10,C9,C8,C7,C5"|"C_0805_2012Metric"|5|"0.1µF"|Mouser|581-08055C104K|
|"C11"|"CP_EIA-6032-15_Kemet-U"|1|"47µ"|Mouser|80-T491C476M010|
|"L1"|"L_Taiyo-Yuden_NR-80xx"|1|"10µh"|Mouser|581-LMLP07A7M100DTAS |


# Licence
The project is free for non-commercial reproduktion. Do not sell it on ebay or other platforms for profit. Do not make a closed source. Share your experiences and ideas with the community.
