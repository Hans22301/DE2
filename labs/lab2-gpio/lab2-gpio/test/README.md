# Lab 2: Jan Mucha

### GPIO control registers

1. Complete the table for DDRB and PORTB control register values.

   | **DDRB** | **PORTB** | **Direction** | **Internal pull-up resistor** | **Description** |
   | :-: | :-: | :-: | :-: | :-- |
   | 0 | 0 | input  | no  | Tri-state, high-impedance |
   | 0 | 1 | input  | yes | Pxn will source current if ext. pulled low.|
   | 1 | 0 | output | no  | Output low |
   | 1 | 1 | output | no  | Output high |

### GPIO library

2. Complete the table with code sizes from three versions of the blink application.

   | **Version** | **Size [B]** |
   | :-- | :-: |
   | Arduino-style     | 480 |
   | Registers         | 172 |
   | Library functions | 182 |

### Traffic light

3. Scheme of traffic light application with one red/yellow/green light for cars, one red/green light for pedestrians, and one push button. Connect AVR device, LEDs, resistors, push button (for pedestrians), and supply voltage. The image can be drawn on a computer or by hand. Always name all components and their values!


   ![image](https://user-images.githubusercontent.com/99410528/195104771-217c7d84-0f56-4b2a-8f09-7c525d0dd4df.png)
