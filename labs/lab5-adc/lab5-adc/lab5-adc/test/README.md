# Lab 5: Jan Mucha

### Analog-to-Digital Conversion

1. Complete table with voltage divider, calculated, and measured ADC values for all five push buttons.

   | **Push button** | **PC0[A0] voltage** | **ADC value (calculated)** | **ADC value (measured)** | **ADC value (measured, hex)** |
   | :-: | :-: | :-: | :-: | :-: |
   | Right  | 0&nbsp;V | 0   | 0 | 0 |
   | Up     | 0.495&nbsp;V | 101 | 100  | 63 |
   | Down   | 1.203&nbsp;V | 246 | 256 | 100 |
   | Left   | 1.970&nbsp;V | 403 | 409 | 200 |
   | Select | 3.181&nbsp;V | 650 | 640 | 27F |
   | none   | 5&nbsp;V | 1023 | 1023 | 3FF |

### Temperature meter

Consider an application for temperature measurement. Use analog temperature sensor [TC1046](http://ww1.microchip.com/downloads/en/DeviceDoc/21496C.pdf), LCD, and a LED. Every 30 seconds, the temperature is measured and the value is displayed on LCD screen. When the temperature is too high, the LED will turn on.

2. Draw a schematic of temperature meter. The image can be drawn on a computer or by hand. Always name all components and their values.

   ![image](https://user-images.githubusercontent.com/99410528/199301749-0bc132d1-f8c4-4e69-ae17-2c128f57102b.png)

3. Draw two flowcharts for interrupt handler `TIMER1_OVF_vect` (which overflows every 1&nbsp;sec) and `ADC_vect`. The image can be drawn on a computer or by hand. Use clear descriptions of the individual steps of the algorithms.

   ![image](https://user-images.githubusercontent.com/99410528/199301830-e1ae4ad0-876d-4301-b886-94a10ad367d5.png)
