# DSA815_repair
rapair documentation of an DSA 815 Spectrum Analyser power Supply

## Broken Caps
All output filterCaps look suspicious and many of them have <1 μF capacitance left and and ESR >1 kOhm
| Designator | Capacitance | Voltage | Vendor | Type      | 
| ---------- | ----------- | ------- | ------ | --------- |
| C102       | 1000 μF     | 16 V    | CapXon | KF 105 °C |
| C103       | 1000 μF     | 16 V    | CapXon | KF 105 °C |
| C123       | 1000 μF     | 16 V    | CapXon | KF 105 °C |
| C113       | 1000 μF     | 16 V    | CapXon | KF 105 °C |
| C114       | 1000 μF     | 16 V    | CapXon | KF 105 °C |
| C120       |  470 μF     | 35 V    | CapXon | KF 105 °C |
| C110       |  470 μF     | 35 V    | CapXon | KF 105 °C |
| C203       |  330 μF     | 35 V    | CapXon | KF 105 °C |
| C212       |  330 μF     | 35 V    | CapXon | KF 105 °C |
| C219       |  22 μF      | 100 V   | CapXon | KF 105 °C |
| C130       |  22 μF      | 100 V   | CapXon | KF 105 °C |
| C204       |  47 μF     | 50 V    | CapXon | KF 105 °C |
| C108       |  1000 μF    | 16 V   | CapXon | KF 105 °C |
| C115       |  1000 μF    | 16 V   | CapXon | KF 105 °C |
| C124       |  330 μF     | 35 V   | CapXon | KF 105 °C |
| C121       |  330 μF     | 35 V   | CapXon | KF 105 °C |
| C111       |  100 μF     | 35 V   | CapXon | KF 105 °C |
| C107       |  68 μF      | 450 V   | CapXon | KF 105 °C |

**Comparison Table:**

| Designator(s)                 | Original CapXon KF Series Specifications | Recommended Replacement (Nichicon UPW Series) | Mouser Part Number | Mouser Link |
|-------------------------------|------------------------------------------|----------------------------------------------|--------------------|-------------|
| C102, C103, C108, C113, C114, C115 | 1000 μF, 16 V, 5 mm lead spacing        | 1000 μF, 16 V, 5 mm lead spacing             | 647-UPW1C102MHD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1C102MHD) |
| C110, C120                    | 470 μF, 35 V, 5 mm lead spacing          | 470 μF, 35 V, 5 mm lead spacing              | 647-UPW1V471MPD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V471MPD) |
| C203, C212, C124, C121        | 330 μF, 35 V, 5 mm lead spacing          | 330 μF, 35 V, 5 mm lead spacing              | 647-UPW1V331MPD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V331MPD) |
| C219, C130                    | 22 μF, 100 V, 5 mm lead spacing          | 22 μF, 100 V, 5 mm lead spacing              | 647-UPW2A220MPD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW2A220MPD) |
| C204                          | 47 μF, 50 V, 5 mm lead spacing           | 47 μF, 50 V, 5 mm lead spacing               | 647-UPW1H470MED    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1H470MED) |
| C111                          | 100 μF, 35 V, 5 mm lead spacing          | 100 μF, 35 V, 5 mm lead spacing              | 647-UPW1V101MPD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V101MPD) |
| C107                          | 68 μF, 450 V, 7.5 mm lead spacing        | 68 μF, 450 V, 7.5 mm lead spacing            | 647-UPW2W680MPD    | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW2W680MPD) |

**Bill of Materials (BOM) replacement:**

| Quantity | Mouser Part Number | Description                                 | Voltage | Capacitance | Lead Spacing | Mouser Link |
|----------|--------------------|---------------------------------------------|---------|-------------|--------------|-------------|
| 6        | 647-UPW1C102MHD    | 1000 μF 16V Aluminum Electrolytic Capacitor | 16 V    | 1000 μF     | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1C102MHD) |
| 2        | 647-UPW1V471MPD    | 470 μF 35V Aluminum Electrolytic Capacitor  | 35 V    | 470 μF      | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V471MPD) |
| 4        | 647-UPW1V331MPD    | 330 μF 35V Aluminum Electrolytic Capacitor  | 35 V    | 330 μF      | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V331MPD) |
| 2        | 647-UPW2A220MPD    | 22 μF 100V Aluminum Electrolytic Capacitor  | 100 V   | 22 μF       | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW2A220MPD) |
| 1        | 647-UPW1H470MED    | 47 μF 50V Aluminum Electrolytic Capacitor   | 50 V    | 47 μF       | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1H470MED) |
| 1        | 647-UPW1V101MPD    | 100 μF 35V Aluminum Electrolytic Capacitor  | 35 V    | 100 μF      | 5 mm         | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW1V101MPD) |
| 1        | 647-UPW2W680MPD    | 68 μF 450V Aluminum Electrolytic Capacitor  | 450 V   | 68 μF       | 7.5 mm       | [Link](https://www.mouser.com/ProductDetail/Nichicon/UPW2W680MPD) |

## Switch Mode controllers

Main [TEA1755LT
HV start-up DCM/QR flyback controller with integrated
DCM/QR PFC controller](https://www.mouser.de/datasheet/2/302/TEA1755LT-3139535.pdf)

Standby [ICE3B0565J Off-Line SMPS Current Mode
Controller with integrated 650V
CoolMOS ® and Startup cell
(frequency jitter Mode) in DIP-8](https://www.mouser.de/datasheet/2/196/Infineon_ICE3BXX65J_DS_v02_09_en-1226717.pdf) 

## Fets

[2SK3569 ](https://www.mouser.com/datasheet/2/408/2SK3569_datasheet_en_20100129-1760726.pdf?srsltid=AfmBOoqOfAcmhnEl1CbtQnjtN7u57uDR2veouXWp1996Qa7RFYuwRC6d)
[SPI11N60C3](https://www.infineon.com/dgdl/Infineon-SPP_I_A11N60C3_E8185-DS-v03_03-EN.pdf?fileId=db3a3043163797a6011638a2fdee01a3)

## Diodes
[MBR B10100](https://www.mouser.com/catalog/specsheets/mbr10100.pdf?srsltid=AfmBOora0FWSBqrYTXQP6bggfBUvFZGf9zUhdGbjF-tB9XX7xbbk-SA4)
[HY ES2D](https://assets.nexperia.com/documents/data-sheet/ES2D.pdf)


