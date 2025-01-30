# Minibadge-Display-5x3
 Battery-powered 5x3 SAINTCON Minibadge display

## Description
Battery-powered RP2040 controlled 5x3 minibadge display

MCU: RP2040

Battery: 606090 5000mAh + JST XH 3 pin 2.54mm

BMS: BQ25895

LEDs: WS2812B-2020

## Costs

| Completed?    | Purchase type    | Price   | Cost per item       |
| ------------- | ---------------- | ------- | ------------------- |
| No            | Parts            | $161.01 | $3.22               |
| No            | Main PCB         | $69.00  | $1.38               |
| No            | PCBA             | $101.84 | $2.04               |
| No            | Batteries        | $215.00 | $4.30               |
| No            | Front PCB        | $50.01  | $1.00               |
| No            | PCB Shipping     | $150.00 | $3.00               |
| No            | Battery Shipping | $100.00 | $2.00               |
| **Item quantity** |                  | **Total**   | **Total cost per item** |
| 50            |                  | $846.86 | $16.94              |

| Completed?    | Purchase type    | Price   | Cost per item       |
| ------------- | ---------------- | ------- | ------------------- |
| No            | Parts            | $131.22 | $5.25               |
| No            | Main PCB         | $28.70  | $1.15               |
| No            | PCBA             | $57.11  | $2.28               |
| No            | Batteries        | $107.50 | $4.30               |
| No            | Front PCB        | $37.50  | $1.50               |
| No            | PCB Shipping     | $80.00  | $3.20               |
| No            | Battery Shipping | $53.35  | $2.13               |
| **Item quantity** |                  | **Total**   | **Total cost per item** |
| 25            |                  | $495.38 | $19.82              |

## BOM

|Designator                                                                                        |Footprint                                                 |Quantity|Value            |LCSC Part #|
|--------------------------------------------------------------------------------------------------|----------------------------------------------------------|--------|-----------------|-----------|
|C1, C12, C13, C14, C15, C16, C17, C18, C19                                                        |0603                                                      |9       |4.7μF            |           |
|C10, C11, C20, C21, C22, C23, C24, C25, C26, C27, C28, C29, C34, C35, C36, C37, C38, C39, C40, C41|0402                                                      |20      |0.1μF            |           |
|C2, C3, C6, C7, C9                                                                                |0603                                                      |5       |10μF             |           |
|C31                                                                                               |0402                                                      |1       |1µF              |           |
|C32, C33                                                                                          |0402                                                      |2       |15pF             |           |
|C4                                                                                                |1206                                                      |1       |40μF             |C426659    |
|C5                                                                                                |0402                                                      |1       |47nF             |           |
|C8                                                                                                |0402                                                      |1       |1µF              |C52923     |
|D1                                                                                                |D_SMB                                                     |1       |20v 5A           |C14651     |
|D2, D3, D4, D5, D6, D7, D8, D9                                                                    |LED_WS2812B-2020_PLCC4_2.0x2.0mm                          |8       |WS2812B-2020     |C5349955   |
|J1                                                                                                |PinSocket_2x05_P2.54mm_Vertical_SMD                       |1       |Board to Board   |           |
|J2                                                                                                |JST_XH_S3B-XH-SM4-TB_1x03-1MP_P2.50mm_Horizontal          |1       |BATT JST         |C161860    |
|L1                                                                                                |L_Vishay_IHLP-2525                                        |1       |2.2µH            |C540967    |
|P1                                                                                                |USB_C_Receptacle_HRO_TYPE-C-31-M-12                       |1       |USB_C_Plug_USB2.0|C165948    |
|R1                                                                                                |0603                                                      |1       |5.23kΩ           |           |
|R10, R9                                                                                           |0402                                                      |2       |27.4Ω            |           |
|R11, R12, R13, R14, R15, R16                                                                      |0603                                                      |6       |10kΩ             |           |
|R2                                                                                                |0603                                                      |1       |260Ω             |C861779    |
|R3                                                                                                |0603                                                      |1       |30.1kΩ           |           |
|R4, R5                                                                                            |0603                                                      |2       |5.1k             |           |
|R6, R7, R8                                                                                        |0603                                                      |3       |1kΩ              |           |
|SW1                                                                                               |SW_Push_1P1T_XKB_TS-1187A                                 |1       |USB BOOT         |C318884    |
|U1                                                                                                |Texas_RTW_WQFN-24-1EP_4x4mm_P0.5mm_EP2.7x2.7mm_ThermalVias|1       |BQ25895          |C80200     |
|U10                                                                                               |Crystal_SMD_Abracon_ABM8G-4Pin_3.2x2.5mm                  |1       |ABM8-272-T3      |C20625731  |
|U2                                                                                                |SOIC-8_5.23x5.23mm_P1.27mm                                |1       |W25Q32JVSS       |C82344     |
|U3                                                                                                |QFN-10-RSE                                                |1       |TS3USB221A       |C128396    |
|U4, U5, U6, U7                                                                                    |SOT-223-3_TabPin2                                         |4       |AP7361C-33E      |C500795    |
|U8                                                                                                |SOIC-8_3.9x4.9mm_P1.27mm                                  |1       |TPM8837C         |C7436831   |
|U9                                                                                                |QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm_ThermalVias           |1       |RP2040           |C2040      |
