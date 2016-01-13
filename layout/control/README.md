# Control PCBs

## c100

![Control PCB](c100_rev_a.png "Control PCB")
rev. a

In the first revision of the PCBs are some minor errors. (This is the version from the 32C3 workshop)
Find detailed pictures of the first prototype [here](../../docu/detail_c100_rev_a).

* A pullup resistor is missing on the USB data lines
* LED silkscreen missing, they are on the right of the controller

![Control PCB](c100_rev_b.png "Control PCB")
rev. b

## c150

![Control PCB](c150_rev_a.png "Control PCB")
rev. a

### control BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| :---        | :---        | :---      | :---         | :---      | :---     |
| R1, R2, R3, R4 | 33 Ω | 4 | SMD-0603 33 | 311-33GRCT-ND |
| R12, R13 | 1 kΩ | 2 | SMD-0603 1,00K | 311-1.0KGRCT-ND |
| C1, C2, C13, C14 | 10 pF | 4 | NPO-G0603 10P |  |
| C7, C8 | 10 nF | 2 | X7R-G0603 10N |  |
| C18, C19, C20, C21 | 100 nF | 4 | X7R-G0603 100N |  |
| C3, C5, C6, C10, C11 | 10 µF | 5 | X5R-G0603 10/6 |  |
| FB1 | Ferrite Bead | 1 | BLM18AG 121 | 490-1011-1-ND |
| Y1 | 8MHz | 1 | - | 535-10630-1-ND |
| Y2 | 32kHz | 1 | 32,768 PGD-9 | 535-9542-1-ND |
| LED1 | LED green | 1 | LG L29K |  |
| LED2 | LED white | 1 | LW L283 | |
| BAT1 | Batteryholder | 1 | - | BC501SM-ND | c100 |
| BAT1 | Batteryholder | 1 | KZH 20SMD-2 | - | c150 |
| BAT | CR 1220 | 1 | CR 1220 VAR | SY033-ND |
| SW1 | Tact Switch Top | 1 | - | EG2531CT-ND |
| J1 | 2x5 Socket | 1 | - | A100866TR-ND, S5714-ND |
| J2 | USB Jack | 1 | USB BWM SMD | 151-1206-1-ND |
| IC1 | STM32F103C8T6 | 1 | STM32 F103C8T6 | 497-6063-ND |
| IC2, IC6 | LP2985 | 1 | LP 2985 IM5-3,3 |  |
| IC3, IC4 | USBLC6-2 | 1 | - | 497-5235-1-ND |


### power supply BOM
| Identifier | Type/Value | Quantity | [Reichelt][reichelt] | [Digikey][digikey] | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R23 | 0.01 Ω | 1 | - | RHM.10MCT-ND |
| R18 | 82 kΩ | 1 | SMD-0603 82K |  |
| R20 | 8,2 kΩ | 1 | SMD-0603 8,2K |  |
| R19 | 1 MΩ | 1 | SMD-1206 1M |  |
| C12 | 150 pF | 1 | NPO-G0603 150P |  |
| C9 | 22 nF | 1 | X7R-G0603 22N |  |
| C4 | 1 µF / 250V | 1 | 1u/250V | 490-3550-1-ND  | |
| C15, C16 | 10 µF | 2 | X5R-G0603 10/6 |  |
| C17 | 100 µF | 1 | X5R-G1210 100 |  |
| D2 | Diode | 1 | BAT 54C SMD |  |
| D3 | Diode | 1 | ES 2GA SMD |  |
| L2 | 680 µH | 1 | L-PISR 680µ |  |
| IC7 | IRF 7470 | 1 | IRF 7470 | IRF7470PBFCT-ND |
| IC5 | LT1619ES8 | 1 | - | LT1619ES8#PBF-ND |

[reichelt]: http://www.reichelt.de
[digikey]: http://www.digikey.de
[mouser]: http://mouser.com
[aliexpress]: http://www.aliexpress.com
