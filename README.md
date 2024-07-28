# Bambino.Plusuino
BBP overhaul

STM32F070CBT6, 93C66WP
|PORT  |CONN       |DESC                          |SW         |           |
|------|-----------|------------------------------|-----------|-----------|
| PA0  | CON2.4    | SW4                          | 1CUP      |           |
| PA1  | CON2.5    | SW5                          | 2CUP      |           |
| PA2  | CON2.3    | SW3                          | STEAM     |           |
| PA3  | CON2.2    | SW2                          | MILK_FOAM |           |
| PA4  | CON2.1    | SW1                          | MILK_TEMP |           |
| PA5  | PT3       | steam pressure sensor        |           |           |
| PA6  | IC5       | TAB8                         |           |           |
| PA7  | NTC1 1K   | coil NTC                     |           | R105      |
| PA8  | CON2.8    | OEN_B                        |           |           |
| PA9  | T_CON.2   | USART1_TX                    |           |           |
| PA10 | T_CON.3   | USART1_RX                    |           |           |
| PA11 | TAB5      | 3WV                          |           | ISO5, Q8  |
| PA12 | TAB6      | dump valve                   |           | ISO1, Q2  |
| PA13 | P_CON.3   | SWDIO                        |           |           |
| PA14 | P_CON.4   | SWCLK                        |           |           |
| PA15 | EEPROM.CS |                              |           |           |
| PB0  | IC6       | zero-cross detector          |           |           |
| PB1  | NTC2 1K   | pitcher NTC                  |           | R107      |
| PB2  | NTC1 2.2K | coil NTC pullup              |           | R106      |
| PB3  | EEPROM.SK |                              |           |           |
| PB4  | EEPROM.DO |                              |           |           |
| PB5  | EEPROM.DI |                              |           |           |
| PB6  | TAB10     | heater SSR                   |           | ISO4, Q10 |
| PB7  | ISO2      | z-c enable?                  |           | ISO2, Q18 |
| PB8  | TAB4      | vibe pump                    |           | ISO3, Q13 |
| PB9  | CON4      | air pump                     |           |           |
| PB10 | NTC2 2.2K | pitcher NTC pullup           |           | R109      |
| PB11 | CON3      | flow meter                   |           | Q12       |
| PB12 | CON2.7    | RST_B                        |           |           |
| PB13 | CON2.10   | CLK                          |           |           |
| PB14 | CON2.6    | SERIN                        |           |           |
| PB15 | CON2.9    | LATCH                        |           |           |
| PC13 | WKUP2     | CON2.[3, 4, 5] diodes        |           |           |
| PC14 | CON6      | water tank level reed switch |           |           |
| PC15 | CON5      | steam wand switch            |           |           |
| NRST | P_CON.6   |                              |           |           |

BD8379
|PIN  |LED     |DESC         |
|-----|--------|-------------|
| D0  |        |             |
| D1  | LED3,4 | 2CUP        |
| D2  | LED5,6 | 1CUP        |
| D3  | LED7,8 | STEAM       |
| D4  | LED9   | MILK_FOAM.L |
| D5  | LED10  | MILK_FOAM.M |
| D6  |        |             |
| D7  | LED11  | MILK_FOAM.H |
| D8  | LED16  | MILK_TEMP.L |
| D9  | LED15  | MILK_TEMP.M |
| D10 | LED14  | MILK_TEMP.H |
| D11 |        |             |


DF14-7S-1.25C(10)
| |P_CON |
|-|------|
|1|3V3   |
|2|      |
|3|SWDIO |
|4|SWCLK |
|5|      |
|6|NRST  |
|7|GND   |

DF14-4S-1.25C(10)
| |T_CON|
|-|-----|
|1|3V3  |
|2|TX   |
|3|RX   |
|4|GND  |
