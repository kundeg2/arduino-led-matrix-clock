# matrix-clock

This repository is an LED matrix clock made with Arduino, the DS3231 RTC module and the MAX7219 LED matrix controller. It also has an ambient light sensor for controlling the brightness of the clock.

For making the byte codes representing the numbers from 00 to 59, I wrote a simple C code, which you can find in byte-generator.exe.
Also, the RTC module isn't so accurate, thus I made a bit of a self correction. It sets the clock forward 1 second in every 3 days.

## Configuration

### Ambient Light Sensor

S - A0

### RTC module

SCL - D9

SDA - D10

### LED Matrix Modules

DIN - D7

CS - D5

CLK - D6
