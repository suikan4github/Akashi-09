# Akashi-09
Prototype for [LI2026ODP](https://github.com/suikan4github/LI2026ODP).

## Jumper Configuration
- JP1 and JP2
  - 1-2 : Internal regulator
  - 2-3 : External Regulator
- JP3
  - Current measurement. Close it for normal usage.
## Base board configuration
Followings are the configuration of the STM32G0B1RE.
Pin | Function
----|----------
PA5 | SPI1_SCK
PA6 | LOAD
PA7 | SPI1_MOSI
PB0 | BLANK
PC5 | RKEY1
PC4 | RKEY2
PA10| RKEY3

## Caution
Cut the 3.3V regulator of the Nucleo to measure the current of the STM32G0B1RE. Thus the total current can be measured by JP3. 

## Other
- [Schematics](doc/Akashi-09.pdf)

## LICENSE
This board is licensed under [CC0](LICENSE).