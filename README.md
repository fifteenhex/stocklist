# stocklist

I have a lot of junk and I need a list to track it so here we are.

# CPU/MCU/SoC

## Chips

| vendor                 | part number     | package | quantity | location    | notes         | source      |
|------------------------|-----------------|---------|----------|-------------|---------------|-------------|
| Atmel                  | ATMega16u4-aur  | TQFP 44 | 2        |             |               |             |
| AllWinner/SoChip       | S3              | BGA     | 5        |             |               |             |
| AllWinner              | V3s             | TQFP    | 7        |             |               |             |
| Atmel                  | ATMega32u2-mu   | VQFN 32 | 2        |             |               |             |
| Atmel                  | ATMega32u4-au   | TQFP 44 | 2        |             |               |             |
| MStar                  | MSC316D         | BGA     | 10       |             |               |             |
| Motorola               | MC68SEC000      | QFP 64  | ~15      |             |               |             |
| Motorola               | MC68VZ328AG     | QFP     | 2        |             | DragonBall VZ |             |
| Motorola               | MC68SZ328       | BGA     | 4        |             |               |             |
| Motorola               | MC68060RC50     | PGA     | 4        | pikachu can | 71e41j        |             |
| Motorola               | MC68EC060RC75   | PGA     | 1        |             |               |             |
| NXP                    | LPC1114FN28     | DIP 28  | 3        |             |               |             |
| NXP                    | LPC812M101J     | SOP20?  | 4        |             |               |             |
| Silicon Laboratories   | EFM32GG842F1024 | QFP 64  | 2        |             |               |             |
| Silicon Laboratories   | EFM32WG322F256  | QFP 64  | 1        |             |               |             |
| Silicon Laboratories   | EFM32GG230F1024 | QFN 64  | 2        |             |               |             |
| Silicon Laboratories   | EFM32ZG222F32   | QFP 48  | 1        |             |               |             |
| Silicon Laboratories   | EFM32ZG110F32   | QFN 24  | 1        |             |               |             |
| Zilog                  | Z84C0020VEG     | PLCC 44 | 4        |             |               |             |
| WinChipHead            | CH552E          | MSOP 10 | 20       |             | 8051 + USB    |             |
|                        |                 |         |          |             |               |             |
| SigmaStar              | SSD210          | QFN68   |          |             |               |             |
| raspberry pi           | pi pico         | module  | 2        | pikachu can | Cortex M0 x 2 |             |
| wdc                    | w65c02s6tpg-14  | DIP     | 1        | pikachu can | 6502          |             |
| hisilicon              | hi3518erncv300  | QFN     | 10       | A           | Cortex A7 SoC |             |

## 8086/8086 chips

| vendor                 | part number     | package | quantity | location    | notes         | source      |
|------------------------|-----------------|---------|----------|-------------|---------------|-------------|
| NEC                    | uPD8088D        | DIP 40  | 9        |             | 8088          | eleshop     |
| Intel                  | P8088           | DIP 40  | 2        | pikachu can | 8088          | wakamatsu   |
| AMD                    | p8088           | DIP 40  | 2        | pikachu can | 8088          | eleshop     |
| NEC                    | upd8253c-2      | DIP 24  | 2        | 8088 stuff  | PIT           | kashinoki   |
| NEC                    | udp8237ac5      | DIP 40  | 2        | 8088 stuff  | DMAC          | kashinoki   |
| NEC                    | udp8255ac-2     | DIP 40  | 2        | 8088 stuff  | PIO           | kashinoki   |
| TMP                    | tmp8259ap       | DIP 28  | 2        | 8088 stuff  | PIC           | kashinoki   |
| NEC                    | d8251afc        | DIP 28  | 13       | tubes box   | UART          | eleshop     |

## SoM

| vendor                 | part number     | package | quantity | location | notes         |
|------------------------|-----------------|---------|----------|----------|---------------|
| Wireless tag           | IDO-SOM2D01-V1  | LGA     | 1        |          |               |

# Logic

## Standard

| vendor                 | part number      | package | quantity  | location | notes         | source    |
|------------------------|------------------|---------|-----------|----------|---------------|-----------|
| Toshiba                | 74hc595          | DIP     | 4         |          |               |           |
| Toshiba                | 74h273ap         | DIP     | 4         | logic    |               | akizuki   |
| TI                     | sn74lvc1g00dbvr  | sot23-5 | 15        |          |               |           | 
| TI                     | sn74lvc1g240dbvr | sot23-5 | 10?       |          |               |           |
|                        | 74ahc1g125w5     | sot32-5 |           | logic    |               |           |
| TI                     | sn74hc574n       | DIP     | 2         | logic    |               | eleshop   |
| TI                     | sn74hc161n       | DIP     | 8         | logic    | counter       | chip1stop |
| TI                     | sn74hc245n       | DIP     | 3         | logic    | bus trans     | kashinoki |

## Single Gate 

| vendor                 | part number      | package | quantity  | location | notes              | source    |
|------------------------|------------------|---------|-----------|----------|--------------------|-----------|
|                        | 74hc1g125w5      | sot23   | 5         | logic    | 3 state bus buffer | akizuki   |

## FPGA/CPLD

| vendor                 | part number      | package | quantity | location | notes         |
|------------------------|------------------|---------|----------|----------|---------------|
| Lattice                | ICE5LP1K-SG48ITR | QFN 48  | 5        |          |               |
| Lattice                | ICE5LP4K-SG48ITR | QFN 48  | 2        |          |               |
| Lattice                | ICE40LP1K-QN84   | QFN 84  | 2        |          |               |
| Lattice                | ICE40LP384-SG32  | QFN 32  | 9?       |          |               |
|                        |                  |         |          |          |               |

# Interface

| vendor                 | part number     | package | quantity | location | notes                                                                             |
|------------------------|-----------------|---------|----------|----------|-----------------------------------------------------------------------------------|
| Holtek                 | HT42B534        | SOP 8   | Too many |          | USB->UART PoS                                                                     |
| WCH                    | CH340E          |         | lots     | USB box  | https://datasheet.lcsc.com/lcsc/2305301024_WCH-Jiangsu-Qin-Heng-CH340E_C99652.pdf |
| NEC                    | uPD8251AFC      | DIP     | 13       |          | USART                                                                             |
| Zilog                  | Z84C9010VEG     | PLCC 84 | 4        |          | Z80 IO chip                                                                       |
| Zilog                  | z8523016vsc     | PLCC    | 2        | Box 1    | SCC                                                                               |

## Ethernet

| vendor                 | part number     | package | quantity | location | notes                                                                             |
|------------------------|-----------------|---------|----------|----------|-----------------------------------------------------------------------------------|
| Crystal                | CS8900A-IQ3Z    | QFP     | 3        |          |                                                                                   |


## USB

| vendor                 | part number     | package | quantity | location | notes                                                                             |
|------------------------|-----------------|---------|----------|----------|-----------------------------------------------------------------------------------|
| Will Semiconductor     | WUSB3801        | DFN     | 15       |          |                                                                                   |

# DC-DC/LDO/PMIC/Charger/Load Switch

| vendor                 | part number     | package | quantity | location     | notes         | source  |
|------------------------|-----------------|---------|----------|--------------|---------------|---------|
|	Qorvo                  | ACT8865QI305-T  | TQFN 32 | 2        |              |               |         |
| Everanalog             | EA3036C         |         | LOTS     |              | 3 x DC-DC     |         | 
| Everanalog             | EA3056          |         | 100      |              |               |         |
| Silergy                | SY8205FCC       |         | lots     | dc-dc etc box| step down     |         |
| richtech               | RT8059gj5       | sot 23  | lots     | dc-dc etc box| buck          | taobao  |
| Injoinic               | ip6103          |         | 30       | dc-dc etc box| pmic          |         |
|                        | lxdc55faaa-203  |         | 1        |              | dc-dc         |         |
| TI                     | tps63001drcr    | QFN     | 4        | dc-dc etc box| buck-boost    | digikey |
| TI                     | lmz20502silt    | LGA     | 5        | dc-dc etc box|               | digikey |
| TI                     | lmz10503tze-adj | xxx     | 1        | dc-dc etc box|               | digikey |
| ablic                  | s-812c33ay-b-g  |         | 5        | dc-dc etc box| 3.3v 50mA LDO | akizuki |
| ablic                  | s-812c50ay-b-g  |         | 6        | dc-dc etc box| 5v 70ma LDO   | akizuki |
| MICRONE                | me6206a33xg     | sot     | 2        | dc-dc etc box| 3.3v 300mA LDO| aitendo |
| torex                  | xc6206p332      | sot     | LOTS     | dc-dc etc box| 3.3v LDO      | taobao  |
| microchip              | mcp1640t        | sot     | 2        | dc-dc etc box| boost         |         |
| microchip              | tc962epa        | dip8    | 4        | dc-dc etc box| hv dc-dc conv |         |
| murata                 | okl-t/3-w5n-c   | LGA     | 2        | dc-dc etc box| dc-dc module  | akizuki |

## Charger

| vendor                 | part number     | package | quantity | location     | notes         | source |
|------------------------|-----------------|---------|----------|--------------|---------------|--------|
|	richtek                | RT9525          | QFN     | 9        | dc-dc etc box| lipo charger  | taobao |

## Load switch

| vendor                 | part number     | package | quantity | location      | notes         | source |
|------------------------|-----------------|---------|----------|---------------|---------------|--------|
|	Silergy                | SY6288AAAAC     | sot23-6 | 50?      | dc-dc etc box | active high   | taobao |
| Silergy                | SY6283A         | DFN     | 20?      | dc-dc etc box |               | taobao |
| Silergy                | SY6283DRC       | DFN     | 40       | dc-dc etc box |               | taobao |
| Microchip              | MIC2505-1YM     |         | 3        | dc-dc etc box |               |        |

# PSU

| vendor                 | part number     | package | quantity | location                    | notes         |
|------------------------|-----------------|---------|----------|-----------------------------|---------------|
| cosel                  | PBA50F-36       | block   | 2        | Brown bookcase, brown boxes | 36V mains PSU |

# RTC

| vendor                 | part number     | package | quantity | location | notes         |
|------------------------|-----------------|---------|----------|----------|---------------|
| Haoyu Microelectronics | HYM8563T        | MSOP    | 10       |          |               |

# Connectors

## USB

| vendor                 | part number     | package | quantity | location | notes                                                                                           |
|------------------------|-----------------|---------|----------|----------|-------------------------------------------------------------------------------------------------|
|                        | TYPE-C-31-M-12  |         | 50       |          | USB-C 12 pin                                                                                    |
|                        | USB-C break out |         | ?0?      | USB box  | https://www.amazon.co.jp/gp/product/B0978MK2R5/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1 |
|                        | mini usb        |         | too many | USB box  |                                                                                                 |

## IC Sockets 

| vendor                 | part number         | package | quantity | location | notes                                                                                           | source    |
|------------------------|---------------------|---------|----------|----------|-------------------------------------------------------------------------------------------------|-----------|
|                        | DIP 4 Round narrow  |         | 3        | tube box |                                                                                                 | kashinoki |
|                        | DIP 20 Round narrow |         | 3        | tube box |                                                                                                 | kashinoki |
|                        | DIP 28 Round narrow |         | 4        | tube box |                                                                                                 | kashinoki |
|                        | DIP 32 Round wide   |         | 3        | tube box |                                                                                                 | kashinoki |
|                        | DIP 40 Round wide   |         | 3        | tube box |                                                                                                 | kashinoki | 

# Memory

## Flash/EEPROM

| vendor                 | part number           | package | quantity | location | notes                 |
|------------------------|-----------------------|---------|----------|----------|-----------------------|
| ST                     | M27C160-100F1         | DIP     | 11       |          | recycled              |
| Longsys                | FS35ND01G-S1Y2QWFI000 | WSON 8  | 9        |          | 1GBit SPI NAND        |
| Winbond                | 25q128jvsq            |         | lots     |          | 128mbit SPI NOR       |
| Winbond                | 25q128jvpm            | wson-8  | 10       |          | 128mbit SPI NOR       |
| Winbond                | 25q128fveg            | wson-8  | 8        |          | 128mbit SPI NOR       |
| SST/Microchip          | 39sf040 70-4c-phe     | DIP 40  | 8        |          |                       |
| EON                    | en29f0021-70ji        | PLCC    | 2        | box 1    | Flash? check part num |
| Microchip              | 24lc256               | DIP 8   | 4        | A        | i2c eeprom            |

## SRAM

| vendor                 | part number           | package | quantity | location                     | notes           |
|------------------------|-----------------------|---------|----------|------------------------------|-----------------|
| Hitachi                | HM62256LP-12          | DIP 28  | 13       |                              | 32Kx8           |
| Dallas                 | DS1747W-120+          | DIP     | 1        | Brown bookcase, in black box | Timekeeper SRAM |
| Motorola               | mcm6306dj15           | SOJ     | 12       | box 1                        | 32Kx8           |

# Misc

| vendor                 | part number     | package  | quantity | location | notes         |
|------------------------|-----------------|----------|----------|----------|---------------|
| TI                     | TS3A27518EPWR   | TSSOP 24 | 9?       |          |               |
|                        |                 |          |          |          |               |

# Diodes

| vendor                 | part number     | package  | quantity | location | notes         |
|------------------------|-----------------|----------|----------|----------|---------------|
| ??                     | SVR05           | SOT23-6  | LOTS!    |          | ESD diode pack|
|                        |                 |          |          |          |               |

## LEDS

| vendor                 | part number     | package  | quantity | location     | notes                             | source |
|------------------------|-----------------|----------|----------|--------------|-----------------------------------|--------|
| kingbright             | kcsa56-123      | LGA      | 10       | incoming box | 14x8mm 7 seg, green, common anode |        |

# Dev board/module

| vendor                 | part number       | package    | quantity     | location                 | notes                    |
|------------------------|-------------------|------------|--------------|--------------------------|--------------------------|
| adafruit               | trinket 3v        | mobule     | 1            | unsorted modules         | attiny usb breakout      |
| adafruit               | trinket 5v        | mobule     | 1            | unsorted modules         | attiny usb breakout      |
| CJMCU                  | CJMCU-2557        | module     | 1            |                          | BQ25570 energy harvester |
| CJMCU                  | CJMCU-25504       | module     | 1            | unsorted modules         | BQ25504 energy harvester |
| espressif              | esp32-wrover-b    | lga module | 5            |                          | ESP32                    |
| Sipeed                 | Dan Dock          |            | 1            |                          | K210                     |
| Sipeed                 | K210 module       |            | 1 (2?)       |                          | K210                     |
| Sipeed                 | Maix bit          | Dev board  | 1 (2?)       |                          | K210                     |
| Sipeed                 | Longan nano       | Dev board  | 2            |                          | GD RISC-V                |
| Sipeed                 | Lichee Tang nano  | Dev board  | 2 (1 LCD)    |                          | Gowin FPGA               |
| Sipeed                 | Tang primer 25K   | Dev board  | 2 (1 SDRAM)  |                          | Gowin FPGA               |
| Firefly                | core-rk3308y      | lga module | 1            |                          | RK3308                   |
| Beagle                 | BeagleBone White  |            | 1            |                          |                          |
| Beagle                 | PocketBeagle      |            | 3 (1 broked) |                          |                          |
| ST                     | STM32F4 discovery |            | 1            |                          |                          |
| TI                     | CC3000BOOST       |            | 1            |                          |                          |
| TI                     | EK-LM4F120XL      | Dev board  | 1            | Brown bookcase, black box|                          |
| Olimex                 | AM3352-SOM-EVB    |            | 1            |                          |                          |
| Renesas                | YRDKRX62N         |            | 1            |                          | RX62N, LCD is broked     |
| Renesas                | YRDKSH7216(W)     |            | 1            |                          | SH2A                     |
| GlobalScale            | Espressobin       | SBC        | 2            |                          |                          |
| NVidia                 | Jetson Nano       | SBC        | 1            |                          |                          |
| Nordic                 | nRF52840          | Dev board  | 1            | Brown bookcase, blue box |                          |
| minibox                | picosam           | SBC        | 2            |                          | 1 with LCD               |
| TTGO                   | t7_v1.4           | Dev board  | 1            |                          | ESP32                    |
| TTGO                   | t18_3.0           | Dev board  | 1            |                          | ESP32                    |
| XMOS                   | startkit          | Dev board  | 1            | Brown bookcase, white box|                          |
| Core                   | GR Peach          | Dev board  | 1            |                          | Renesas RZ1/A            |
| waveshare              | RP2040 zero       |            | 2            | unsorted modules box     |                          |
| olimex                 | MOD-ENC644J600    | Module     | 1            | pikachu can              |                          |
| ???                    | digispark at85    | module     | 1            | pikachu can              | Clone                    |
| muselab                | icesugar nano     | module     | 2            | unsorted modules box     | ice fpga breakout        |
| muselab                | usb-hs-bridge v1.0| module     | 1            | unsorted modules box     | CH347 breakout           |
|                        | ice40_fpga_pico   | module     | 1            | unsorted modules box     | ice fpga breakout        |
|                        | flappyboard       | module     | 3            | unsorted modules box     | ch32v203g6 breakout      |

# Tools

| vendor                           | part number        | package    | quantity     | location              | notes                                           | source  | 
|----------------------------------|--------------------|------------|--------------|-----------------------|-------------------------------------------------|---------|
| Dangerous Prototypes             | open logic sniffer |            | 1            |                       | Logic analyzer, input buffer is probably broked |         |
| Dangerous Prototypes             | bus blaster v3c    |            | 1            |                       | FT2232 JTAG, ktlink buffer flashed              |         |
| [150w electronic load][150wload] |                    |            | 1            |                       |                                                 |         |
| WCH                              | WCH-LinkE-R0-1v3.FP|            | 1            |                       | WCH RISC-V debugger                             |         |
| muselab                          | nanoDLA v1.3       | object     | 1            | pink chupa chups ball | pulseview LA dongle                             |         |
| ????                             | analyzer 24MHz 8CH | object     | 1            | pink chupa chups ball | pulseview LA dongle                             |         |
| segger                           | jlink edu mini     | thing      | 1            | pink chupa chups ball | JTAG                                            |         |
|                                  |                    |            |              |                       |                                                 |         |
|                                  |                    |            |              |                       |                                                 |         |
| Adafruit                         | ft232h             | thing      | 1            | unsorted modules box  | ft232h breakout                                 | akizuki |

[150wload]: https://www.diymore.cc/products/150w-ldm-digital-electronic-load-discharge-capacity-tester-usb-voltmeter-ammeter?_pos=3&_sid=4049f80b9&_ss=r "150w load"


# VFD

| vendor                           | part number                     | package    | quantity     | location              | notes                                           |
|----------------------------------|---------------------------------|------------|--------------|-----------------------|-------------------------------------------------|
|                                  | noritake vfd with usb interface |            | 2            | Old skool display box |                                                 |

# Oscillator / xtal

| vendor                 | part number     | package   | quantity | location | notes                                                                             |
|------------------------|-----------------|-----------|----------|----------|-----------------------------------------------------------------------------------|
| ???                    | ???             | 4 pin can | 10       | box 1    | 6mhz 5v(?) osc                                                                    |
| ???                    | ???             | 4 pin can | 10       | box 1    | 8mhz 5v(?) osc                                                                    |
| ???                    | ???             | 4 pin can | 10       | box 1    | 10mhz 5v(?) osc                                                                   |
| Raltron                | c019025         | 4 pin can | 3        | box 1    | 100mhz 3.3v osc                                                                   |

# Misc

| vendor                 | part number     | package   | quantity | location    | notes                                                                             |
|------------------------|-----------------|-----------|----------|-------------|-----------------------------------------------------------------------------------|
| ??                     | 2.54mm jumper   |           | lots     | box 1       |                                                                                   |
| ??                     | db15 on ribbon  | thing     | 1        | pikachu can |                                                                                   |

# Passives

| vendor                 | part number         | package   | quantity | location    | notes                                                                             |
|------------------------|---------------------|-----------|----------|-------------|-----------------------------------------------------------------------------------|
| samsung                | cl05b154k05nnnc     | 0402      | ~1000    | A           | 0.15uF 16V X7R 0402                                                               |
| samsung                | cl05a105kq5nnnc     | 0402      | ~1000    | A           | 1uf 6.3v x5r 0404                                                                 |   
| yageo                  | rx0402fr-07200kl    | 0402      | ~1000    | A           | 200k 1% 1/16w 0402                                                                |
| yageo                  | rc0402fr-071ml      | 0402      | ~1000    | A           | 1M 1% 1/16w 0402                                                                  |
| yageo                  | rc0402jr-0722rl     | 0402      | ~1000    | A           | 22ohm 55 1/16w 0402                                                               |
| yageo                  | rc0402fr-07510kl    | 0402      | ~1000    | A           | 510k 1% 1/16w 0402                                                                |
| yageo                  | rc0402fr-07390rl    | 0402      | ~1000    | A           | 390ohm 1% 1/16w 0402                                                              |
| yageo                  | rc0402jr-07110kl    | 0402      | ~1000    | A           | 110K 5% 1/16w 0402                                                                |
| murata                 | grj155r60j106me11d  | 0402      | ~500     | A           | 10uf 6.3v x5r 0402                                                                |
|                        | 0603waf1001t5e      | 0603      | ~400     | A           | 0603 1K                                                                           |
|                        | 0603waf4701t5e      | 0603      | ~400     | A           | 0603 4.7k                                                                         |
|                        | rc0603jr-07110rl    | 0603      | ~300     | A           | 0603 110ohm                                                                       |

## super cap

| vendor                 | part number         | package   | quantity | location    | notes                                                                             |
|------------------------|---------------------|-----------|----------|-------------|-----------------------------------------------------------------------------------|
| elpa                   |                     | TH        | 2        | passives box| 5.5v 0.1f                                                                         |

# Driver

| vendor                           | part number        | package    | quantity     | location              | notes                                           | source  | 
|----------------------------------|--------------------|------------|--------------|-----------------------|-------------------------------------------------|---------|
| mitsubishi                       |m54564p             | DIP        | 2            | incoming box          | source darlington array                         | akizuki |

# Backlog

- MMA7660FC - accelerometer
- RTL8309N - 8 port ethernet switch
- STM32L011D3P6 - stm32 mcu
- MMBT3904 (1AM) - NPN transistor

