# yarus-cartesian-mk1

Configuration files for Klipper for Yarus cartesian mk1 (Ender3 V3 SE).

## Ender-3 V3 SE:1:GD32F303 CR4NS200320C13

printer_size: 220x220x250
mcu:

- chip: GD32F303RET6
- version: CR4NS200323C13

- Micro-controller architecture: STMicroelectronics STM32
- Processor model: STM32F103
- Bootloader offset: 28KiB
- Communication interface: Serial (on USART1 PA10/PA09)
- Enable extra low-leverl configuration options and "Disable SWD on startup"

If you prefer a direct serial connection, in "make menuconfig" select "Enable extra low-level configuration options" and select serial (on USART3 PB11/PB10), which is broken out on the 10 pin IDC cable used for the LCD module as follows: 3: Tx, 4: Rx, 9: GND, 10: VCC Ports
