# Lab 1: JAN MUCHA

### Morse code

1. Listing of C code which repeats one "dot" and one "comma" (BTW, in Morse code it is letter `A`) on a LED. Always use syntax highlighting, meaningful comments, and follow C guidelines:

```c
int main(void)
{
    uint8_t led_value = LOW;  // Local variable to keep LED status

    // Set pin where on-board LED is connected as output
    pinMode(LED_GREEN, OUTPUT);

    // Infinite loop
    while (1)
    {
       led_value = HIGH;
       digitalWrite(LED_GREEN, led_value);
       _delay_ms(SHORT_DELAY);
        
       led_value = LOW;
       digitalWrite(LED_GREEN, led_value);
       _delay_ms(250);
      

       led_value = HIGH;
       digitalWrite(LED_GREEN, led_value);
       _delay_ms(LONG_DELAY);
      
       led_value = LOW;
       digitalWrite(LED_GREEN, led_value);
       _delay_ms(250);

       
    }

    // Will never reach this
    return 0;
}
```

2. Scheme of Morse code application, i.e. connection of AVR device, LED, resistor, and supply voltage. The image can be drawn on a computer or by hand. Always name all components and their values!

   ![scheme_lab1](lab1_scheme.png)
