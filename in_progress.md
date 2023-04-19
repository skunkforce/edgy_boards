# Edgy Boards In Progress
## Ethernet
### Switches 
**b034** 5 port switch using KSZ8895

**Status:** Legacy, on hold untill the chips are availible.

**b035** 7 port gigabit switch using KSZ9477

**Status:** Legacy, abandoned untill the chips are availible again.

**b042** 7 port gigabit switch using KSZ9897

**Status:** Legacy, abandoned untill the chips are availible again.

**b098** 5 port gigabit switch with 5 (S/R/G)MII interfaces using SJA1105.

**Status:** Legacy, initial.

**b119** 8 port 100Mbit switch using RTL8309N

**status** [ordered](https://github.com/skunkforce/b119_8_port_100BASE-T_switch_RTL8309N/releases/tag/v1.0rc)

**b118** 5 port 100Mbit switch using TRL8305N

**status** [ordered](https://github.com/skunkforce/b118_5_port_100BASE-T_switch_RTL8305N/releases/tag/v1.0rc)

### Connectors
**b004** 100BASE-T connector featuring a Würth 7499211121A RJ45 connector with builtin magnetics and PoE rectifier.

**Status:** [ordered](https://github.com/skunkforce/b004_ethernet_to_019_100BASE-T_and_rectified_PoE/releases/tag/v1.0rc).

**b039** gigabit SGMII cage.

**Status:** Legacy, review needed.

**b095** osf.009 100BASE-T M12 connector.

**Status:** [ordered](https://github.com/skunkforce/b095_100BASE-T_M12/releases/tag/v1.0rc)


### Magnetics

**b099** 100BASE-T magnetics featuring 749013011A

**status** [ordered](https://github.com/skunkforce/b099_100BASE-T_magnetics_749013011A/releases/tag/v1.0rc)

**b009** 1000BASE-T magnetics in phy to device configuration featuring WE7490220122.

**Status:** Legacy, potential problem with 009 pinning.

**b060** 1000BASE-T magnetics in extractor/injector configuration featuring WE7490220122.

**Status:** Legacy, ordered.

**b116** 1000BASE-T using PT61020

**status** [ordered](https://github.com/skunkforce/b116_1000BASE-T_magnetics_PT61020/releases/tag/v1.0rc)

### Phys
**b108** 1Gbit PHY featuring ADIN1300

**status** in development.

**b007** 100Mbit PHY featuring LAN8742A

**Status:** Legacy, tested with b004.

**b008** 100Mbit PHY featuring KSZ8081RND

**Status:** Legacy, not finished.

**b037** gigabit phy using KSZ9031

**Status:** Legacy, abandoned untill the chips are availible again.

**b040** gigabit phy using DP83822

**Status:** Legacy, abandoned untill the chips are availible again.

**b041** gigabit phy ad RMII master using DP83822

**Status:** Legacy, abandoned untill the chips are availible again.

**b054** gigabit phy using DP83848

**Status:** Legacy, abandoned untill the chips are availible again.

**b078** 100Mbit MAC + PHY with SPI interface W5500

**Status:** [ordered](https://github.com/skunkforce/b078_Ethernet_MAC-PHY_WIZ5500/releases/tag/v1.0rc).

**b108** gigabit PHY using ADIN1300BCPZ

**status** [ordered](https://github.com/skunkforce/b108_gigabit_PHY_RGMII_ADIN1300BCPZ/releases/tag/v0.1rc)

### PoE
**b011** PoE++ Rectifier using LT4321

**status:** Legacy, ordered, not tested.

**b012** PoE Rectifier using MB10FTR

**status:** [ordered](https://github.com/skunkforce/b012_PoE_rectifier_MB10FTR/releases/tag/v1.0rc)

**b027** PoE++ PD using LT4275

**status:** Legacy, initial.

**b029** PoE++ PSE using LTC4266

**status:** Legacy, initial.

**b033** PoE PD with 3 Watt flyback DCDC using MP8007 and POE30P50. 
See also **b093** for 7 Watt and **b075** for 13 Watt.

**Status:** Legacy, needs improvement.

**b093** PoE PD with 7 Watt flyback DCDC using MP8007 and POE70P50. 
See also **b033** for 3 Watt and **b075** for 13 Watt.

**Status:** [ordered](https://github.com/skunkforce/b093_PoE_PD_DCDC_isolated_flyback_MP8007/releases/tag/v1.0rc)

**b075** PoE PD with 13 Watt flyback DCDC using MP8007 and POE13P50. 
See also **b033** for 3 Watt and **b093** for 7 Watt.

**Status:** [ordered](https://github.com/skunkforce/b075_PoE_PD_DCDC_5V_13W_isolated_flyback_MP8007/releases/tag/v1.0rc)

**b076** PoE PD with flyback DCDC using SI3404

**Status:** Legacy, ordered.

**b077** PoE PD buck DCDC using SI3404

**Status:** Legacy, incapable of large loads, being investigated.

**b115** 4x PoE PSE 13W using TPS23861

**status** [ordered](https://github.com/skunkforce/b115_4x_PoE_PSE_13W_TPS23861/releases/tag/v1.0rc)


## USB
**b006** 4 port USB hub featuring GL850G.

**Status:** Legacy, tested.

**b094** 7 port USB hub featuring USB2517.

**Status:** Legacy, ordered.

**b082** 4 port USB hub featuring USB2514B.

**Status:** Legacy, unfinished.

**b017** USB to debug edge using FT2232

**Status:** Legacy, ordered.

**b070** USB to debug V3MODS

**Status:** Legacy, ordered.

**b021** USB to I2C host using FT260S

**Status:** Legacy, unfinished.

**b022** USB to I2C device using FT201XS

**Status:** Legacy, ordered.

**b120** USB to USB-A connector.

**status** [ordered](https://github.com/skunkforce/b120_008_USB_to_USB-A_GSB12121/releases/tag/v1.0rc)

## 1-wire
**b043** 1wire to I2C bridge using DS28E18

**Status:** Legacy, ordered, not tested.

**b044** 1wire to SPI bridge using DS28E18

**Status:** Legacy, ordered, not tested.

**b045** 1wire to RJ45 connector

**Status:** Legacy, review needed.

**b048** I2C 1wire master DS2484R

**Status:** Legacy, review needed.

## RS485
### transceiver
**b067** RS485 transceiver featuring MAX485. 

**status** [initial design](https://github.com/skunkforce/b067_RS485_transceiver_MAX485).


## CAN
**b087** CAN controller with SPI interface featuring MCP2515

**status** Legacy, initial design.


### FD
**b065** CAN FD controller with SPI interface featuring MCP2517FD

**status** Legacy, ordered.

**b066** CAN FD transceiver featuring TJA1441

**status** Legacy, ordered.


## Regulator
### Switching step-down
**b063** Isolated 5v-5v DCDC.

**Status:** Legacy, ordered.

**b069** 4.5V to 75V input 5A buck DCDC MIC28515.

**Status:** Legacy, ordered.

**b068** 6.5V to 28V input 5A buck DCDC AOZ2152EQI-28.

**Status:** Legacy, ordered.

**b025** USB to 4x DCDC 

**Status:** Legacy, tested.

**b057** 4.5V to 75V buck converter MAX17760
Output current 300ma

**Status:** Legacy, needs review.

**b085** 4.2V - 18V input 2A buck converter AP6220

**Status:** Legacy, ordered.

**b114** 12V-76V to 3.3V 3A using BD9G341

**status** [ordered](https://github.com/skunkforce/b114_dcdc_step_down_12V-76V_in_3.3V_3A_out_BD9G341/releases/tag/v1.0rc)

**b113** 4.5V - 40V to 3.3V 600ma buck using AP64060

**status** [ordered](https://github.com/skunkforce/b113_4.5v-40v_600ma_buck_converter_AP64060/releases/tag/v1.0rc)

### switching step-up

**b102** battery cell DCDC step up featuring TPS61021A

**status:** [ordered](https://github.com/skunkforce/b102_dcdc_stepup_TPS61021A/releases/tag/v0.1rc).

### LDO
**b002** features a TC1017 producing 3.3V output from a 5 volt input. 
Output current 200ma.

**Status:** [ordered](https://github.com/skunkforce/b002_5v_to_3.3v_LDO_TC1017/releases/tag/v1.0rc)

**b121** 5V to 3.3V 2A LDO featuring LD39200PU.

**status** [Ordered](https://github.com/skunkforce/b121_5v_to_3.3v_2A_LDO_LD39200PU/releases/tag/v1.0rc)

## Microcontroller
**b018** breakout of the RP2040 including flash memory.

**Status:** Legacy, [b018v2.2rc missing I2C resistors, basic functionality otherwise tested](https://github.com/skunkforce/edgy_boards_legacy/releases/tag/b018v2.2rc)

[b018v2.3rc ready to order](https://github.com/skunkforce/edgy_boards_legacy/releases/tag/b018v2.3rc)

**b019** breakout of the STM32F042.

**Status:** Legacy, finished but not ordered (or tested) because STM32F042 is out of stock.

**b080** breakout of the STM32G030.

**Status:** Legacy, ordered.

**b023** breakout of the STM23F723IE

**Status:** Legacy, outdated and probably dorment untill the chips are availible again.

**b026** breakout of STM32F7 144 pin TQFP

**Status:** Legacy, outdated and probably dorment untill the chips are availible again.

**b030** breakout of STM32F7 100 pin TQFP

**Status:** Legacy, outdated and probably dorment untill the chips are availible again.

**b032** breakout of STM32F7 100 pin TFBGA

**Status:** Legacy, outdated and probably dorment untill the chips are availible again.

**b028** STM32F042 with just one I2C connector.

**Status:** Legacy, abandoned.

**b020** STM32F745 breakout.

**Status:** Legacy, abandoned untill the chip is availible again.

**b053** STM32F107 64TQFP breakout.

**Status:** Legacy, abandoned untill the chip is availible again.

**b090** STM32WL55 LoRa breakout.

**Status:** Legacy, initial.

## system on a module
### standard SOM connector layout
It is common for boards which connect to a SOM to connect to multiple interfaces. Therefore it is advantagous to standardize the interface connector layout of SOMs such that connecting boards can connect at multiple points. 

Using the standard 16mm distance between connectors the order of connected interfaces is:
USB
UART
I2C
SPI
DebugEdge

**b049** Raspberry Pi compute module 4 with isolated flyback PoE. 

**Status:** Legacy, this board is essentially a composition of b076, b080 and a CM4. development of this is paused untill those are fully tested.

**b071** Raspberry Pi compute module 4. 

**Status:** Legacy, waiting for tests of b049.

**b107** VAR-SOM breakout

**status** [ordered](https://github.com/skunkforce/b107_VAR-SOM_breakout/releases/tag/v0.2rc)

## Pinconnectors

## ADC
**b013** ADS868x

**status:** Legacy, ordered, not tested.

**b031** ADS8688 8X differential SPI ADC

**status:** Legacy, tested.

**b059** ADS8168 8X differential SPI ADC 1MSPS

**status:** Legacy, review needed.

**b056** ADS131M08 8X differential SPI ADC 32kSPS

**status:** [ordered](https://github.com/skunkforce/b056_8x_diff_SPI_ADC_ADS131M08/releases/tag/v1.0rc)

**b081** MCP3428 4X 16 bit differential I2C ADC with PGA 15SPS

**status:** [ordered](https://github.com/skunkforce/b081_I2C_4x_diff_ADC_MCP3428/releases/tag/v1.0rc)

**b091** ADS131A04 4X differential SPI ADC 128kSPS

**status:** Legacy, initial.

**b110** 4x MUX PGA ADC using ADS1120

**status** [ordered](https://github.com/skunkforce/b110_4x_mux_pga_adc_ADS1120/releases/tag/v1.0rc)

## DAC
**b024** 4x DAC with I2C interface using MCP4728.

**Status:** Legacy, ordered, not tested.

## Isolators
**b036** I2C isolator featuring ADUM1251

**Status:** Legacy, ordered, not yet tested.

**b055** SPI isolator and DCDC featuring ADUM5411

**Status:** Legacy, unfinished.

**b064** SPI isolator and DCDC featuring ADUM5401

**Status:** Legacy, unfinished.

**b062** SPI isolator featuring MAX14483

**Status:** Legacy, unfinished.

## Memory
**b046** I2C eeprom M24C02

**Status:** Legacy, test needed.

**b079** SPI SD card

**Status:** Legacy, ordered.

**b073** QSPI EEPROM

**Status:** Legacy, ordered.

**b072** QSPI EEPROM W25Q

**Status:** Legacy, ordered.

**b096** MAC address chip 11AA02E48 or 11AA02E64

**Status:** Legacy, initial.

## battery management
### holders
**b104** 2 cell AA battery holder

**status:** [ordered](https://github.com/skunkforce/b104_2cellAA_battery_holder/releases/tag/v1.0rc)

**b117** 2 cell AAA battery holder

**status** [in development](https://github.com/skunkforce/b117_2cellAAA_battery_holder)

### chargers
**b105** 2 cell NiMh charger featuring DS2711E

**status:** [ordered](https://github.com/skunkforce/b105_2cell_charger_NiMh_DS2711E/releases/tag/v0.1rc)

## Sensors
### angle

**b089** 3 axis accelerometer LIS3DHTR.

**Status:** Legacy, initial.

### hall effect

**b015** MLX91205.

**status:** Legacy, not finished.

**b047** HDC1080.

**status:** Legacy, review needed.

**b092** TMCS110.

**status:** Legacy, initial.

### temperature

**b106** SPI thermocouple featuring MAX31855

**status:** [v1.0 not ordered](https://github.com/skunkforce/b106_SPI_thermocouple_MAX31855/releases/tag/v1.0rc)

**b101** I2C temperature sensor

**status:** [ordered](https://github.com/skunkforce/b101_I2C_temperature_sensor_MCP9844/releases/tag/v1.0rc)

**b083** 4x PT100 to I2C using MCP3428.

**status:** Legacy, ordered.

**b088** temp humid SHT30-DIS.

**status:** Legacy, initial.

## Analog
**b050** analog preamp using LMV601

**Status:** Legacy, review needed.

**b112** 16x1 analog MUX using ADG706

**status** [ordered](https://github.com/skunkforce/b112_16x1_analog_mux_ADG706/releases/tag/v1.0rc2)

**b109** 8x2 analog MUX using ADG707

**status** [ordered](https://github.com/skunkforce/b109_8x2_analog_mux_ADG707/releases/tag/v1.0rc)

## Other
**b058** RTC MCP79410

**Status:** Legacy, review needed.

**b061** 40 pin pi 4 connector breakout

**Status:** Legacy, tested.

**b097** GPIO to RGB-LED

**Status:** Legacy, initial.

**b074** resistive power supply tester

**Status:** Legacy, initial.

**b111** ck etoggle right angle switch E103MD1ABE

**status** [ordered](https://github.com/skunkforce/b111_ck_etoggle_right_angle_switch_E103MD1ABE/releases/tag/v1.0rc)

