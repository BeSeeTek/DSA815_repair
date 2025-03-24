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
| C204       |  470 μF     | 50 V    | CapXon | KF 105 °C |
| C108       |  1000 μF    | 16 V   | CapXon | KF 105 °C |
| C115       |  1000 μF    | 16 V   | CapXon | KF 105 °C |
| C124       |  330 μF     | 35 V   | CapXon | KF 105 °C |
| C121       |  330 μF     | 35 V   | CapXon | KF 105 °C |
| C111       |  100 μF     | 35 V   | CapXon | KF 105 °C |
| C107       |  68 μF      | 450 V   | CapXon | KF 105 °C |


## Switch Mode controllers

Main [TEA1755LT
HV start-up DCM/QR flyback controller with integrated
DCM/QR PFC controller](https://www.mouser.de/datasheet/2/302/TEA1755LT-3139535.pdf)

Standby [ICE3B0565J Off-Line SMPS Current Mode
Controller with integrated 650V
CoolMOS ® and Startup cell
(frequency jitter Mode) in DIP-8](https://www.mouser.de/datasheet/2/196/Infineon_ICE3BXX65J_DS_v02_09_en-1226717.pdf) 
