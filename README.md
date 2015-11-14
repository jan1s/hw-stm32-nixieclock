# hw-nixieclock-mini
This is work in progress

## BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R1, R2, R3, R4 | 33 Ω | 4 | SMD-0603 33 |  |
| R12, R13 | 1 kΩ | 2 | SMD-0603 1,00K |  |
| C1, C2, C13, C14 | 22 pF | 4 | NPO-G0603 22P |  |
| C7, C8 | 10 nF | 4 | X7R-G0603 10N |  |
| C18, C19, C20, C21 | 100 nF | 4 | X7R-G0603 100N |  |
| C3, C5, C6, C10, C11 | 10 µF | 5 | X5R-G0603 10/6 |  |
| L1 | Ferrite Bead | 1 | BLM18AG 121 |  |
| Y1 | 8MHz | 1 | 32,768 PGD-9 |  |
| Y2 | 32kHz | 1 | 32,768 PGD-9 |  |
| LED1 | LED green | 1 | LG L29K |  |
| LED2 | LED white | 1 | LW L283 | |
| BAT1 | Batteryholder | 1 | - |  |
| BAT | CR 1220 | 1 | CR 1220 VAR | |
| SW1 | Tact Switch Top | 1 | - | - |
| J2 | USB Jack | 1 | USB BWM SMD |  |
| IC1 | STM32F103C8T6 | 1 | STM32 F103C8T6 |  |
| IC2, IC6 | LP2985 | 1 | LP 2985 IM5-3,3 |  |
| IC3, IC4 | USBLC6-2 | 1 | - |  |

## Power supply - BOM
| Identifier | Type/Value | Quantity | Supplier Id | Supplier | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R23 | 0.01 Ω | 1 | 603-RL1206JR-070R01L | [Mouser][mouser] |
| R18 | 82 kΩ | 1 | SMD-0603 82K | [Reichelt][reichelt] |
| R20 | 8,2 kΩ | 1 | SMD-0603 8,2K | [Reichelt][reichelt] |
| R19 | 1 MΩ | 1 | SMD-1206 1M | [Reichelt][reichelt] |
| C12 | 150 pF | 1 | NPO-G0603 150P | [Reichelt][reichelt] |
| C9 | 22 nF | 2 | X7R-G0603 22N | [Reichelt][reichelt] |
| C4 | 1 µF / 250V | 1 | 1u/250V | [Aliexpress][aliexpress] |
| C15, C16 | 10 µF | 2 | X5R-G0603 10/6 | [Reichelt][reichelt] |
| C17 | 100 µF | 1 | X5R-G1210 100 | [Reichelt][reichelt] |
| D2 | Diode | 1 | BAT 54C SMD | [Reichelt][reichelt] |
| D3 | Diode | 1 | XXX | [Reichelt][reichelt] |
| L2 | 680 µH | 1 | L-PISR 680µ | [Reichelt][reichelt] |
| T1 | IRF 7470 | 1 | IRF 7470 | [Reichelt][reichelt] |
| IC5 | LT1619ES8 | 1 | LT1619ES8 | [Aliexpress][aliexpress] |

## Display Board - BOM
| Identifier | Type/Value | Quantity | Supplier Id | Supplier | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R1-R4 | 220 kΩ | 4 | SMD-0603 220K | [Reichelt][reichelt] |
| R10-R60 | 22 kΩ | 4 | SMD-0603 22K | [Reichelt][reichelt] |
| RN10-RN71| 4x10 kΩ | 12 | BCN16 10K | [Reichelt][reichelt] |
| C1-C8 | 100 nF | 6 | X7R-G0603 100N | [Reichelt][reichelt] |
| T1-T69 | SMBTA 42 SMD | 42 | SMBTA 42 SMD | [Reichelt][reichelt] |
| IC1-IC8 | 74HC595PW | 6 | SMD HC 595 | [Reichelt][reichelt] |
| JP1 | 2x5pol Header | 1 | ??? | [Reichelt][reichelt] |  |
| GL1, GL2 | Neon Bulb | 2 | GLIMMLAMPE | [Reichelt][reichelt] |

[reichelt]: http://www.reichelt.de
[mouser]: http://mouser.com
[aliexpress]: http://www.aliexpress.com
