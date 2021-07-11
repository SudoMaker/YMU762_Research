# YMU762_Research

## Register Map
  
| Offset | Description |
| --- | --- |
| 0000 | MA_INTERRUPT_FLAG_REG |
| 0001 | MA_DELAYED_WRITE_REG |
| 0002 | MA_IMMEDIATE_WRITE_REG |
| 0003 | MA_IMMEDIATE_READ_REG |
| 0004 | MA_BASIC_SETTING_REG |
| 0005 | MA_POWER_MANAGEMENT_DIGITAL_REG or MA_PLL_SETTING_1_REG |
| 0006 | MA_POWER_MANAGEMENT_ANALOG_REG or MA_PLL_SETTING_2_REG |
| 0007 | MA_ANALOG_EQVOL_REG |
| 0008 | MA_ANALOG_HPVOL_L_REG |
| 0009 | MA_ANALOG_HPVOL_R_REG |
| 000a | MA_ANALOG_SPVOL_REG |
| 000b | MA_LED_SETTING_1_REG |
| 000c | MA_LED_SETTING_2_REG |
| 000d | MA_MOTOR_SETTING_1_REG |
| 000e | MA_MOTOR_SETTING_2_REG |
| 000f | ? |

#### REGISTER MA_PLL_SETTING_1_REG: PLL SETTING REGISTER 1

| U-0 | U-0 | U-0 | U-0 | U-0 | U-0 | U-0 | U-0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | PLLDIV4 | PLLDIV3 | PLLDIV2 | PLLDIV1 | PLLDIV0 |
| bit 7 |  |  |  |  |  |  | bit 0 |

`bit 7-5`&ensp; **Unknown**

`bit 4-0`&ensp; **PLLDIV<4:0>: PLL Divider**


OMG Markdown sucks
