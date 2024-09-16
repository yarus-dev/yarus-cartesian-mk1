Suitable for:           Ender-3V3 SE
Motherboard:            HWCR4NS200320C13
Main chip model:        GD303RET6
Main control digits:    32 Bit
oscillator:             8MHz
EPROM:                  24C16F
Driver model:           MS35774
usb chip:                    CH340G
level chip:                 HX711

Setup Tim , DIR to STEP: 20ns
STEP Minimum High Level Time: 100ns
STEP Minimum Low Level Time: 100ns
Hold Time, DIR to STEP: 20ns
Filtering Time for STEP and DIR Glitches: 13ns-30ns

PDN: Automatic Current Decay Mode Input Control. When in low level, enable the automatic current attenuation function at a standstill. he automatic current decay function is enabled by pulling down Driver UART pin. When the operating current is about 50% , the power dissipation can be reduced to 33%.


|PIN| Name| Description|
|---|---|---|
|1|||
|2|||
|3|||


PC15 filament sensor
PA1 carriage hotend heater
PC13 carriage crtouch servo deploy ("IN")
PC14 carriage crtouch sense ("OUT")
PA0 carriage FAN1 heatbreak radiator
PC1 carriage FAN2 print cooling
PC5 carriage hotend thermistor
PB2 bed heater
PC4 bed thermistor
PA4 height SCK (HX711) 
PC6 height DO
PA15 endstop Z (optional)
PA7 eeprom SDA (sot23-5 24C16F) 
PA8 eeprom SCL
PD0 oscillator (8MHz)
PD1 oscillator
PA9 UART TX
PA10 UART RX
PC0 LED
PA2 display TX (IDC 3)
PA3 display RX (IDC 4)
PB0 display buzzer (IDC 6)
PB1 display encoder button (IDC 5)
PA11 display encoder (IDC 7)
PA12 display encoder (IDC 8)
PC3 stepstick enable
PB14 stepstick Z UART
PB13 stepstick Y UART
PB12 stepstick X UART
PB15 stepstick E UART (R89 not populated)
PB6 stepstick Z step
PB5 stepstick Z dir
PB8 stepstick Y step
PB7 stepstick Y dir
PC2 stepstick X step
PB9 stepstick X dir
PB4 stepstick E step
PB3 stepstick E dir
PA5 endstop X; stepstick E (others not tested) standby
PB10 stepstick X diag (stallguard)
PB11 stepstick Y diag (stallguard)
PA6 endstop Y
PD2 sdcard SDIO_CMD
PC12 sdcard SDIO_CK
PC11 sdcard SDIO_D3
PC10 sdcard SDIO_D2
PC9 sdcard SDIO_D1
PC8 sdcard SDIO_D0
PC7 sdcard inserted