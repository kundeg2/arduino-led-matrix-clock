# matrix_clock

An LED-matrix clock made with Arduino, using a DS3231 RTC module and 4 MAX7219 LED-matrix controllers. It also has an ambient light sensor for controlling the brightness.

For making the byte codes representing the numbers from 00 to 59, I wrote a simple C code, which you can find in byte-generator.txt. Also, I made a small amount of self correction to the RTC module in order to make it more accurate.

## Configuration

### Ambient Light Sensor

S - A0

### RTC module

SCL - D9

SDA - D10

### LED-matrix Modules

DIN - D7

CS - D5

CLK - D6
