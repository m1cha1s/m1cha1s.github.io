# Time date raferance

I have receantly designed a simple time and date referance circuit based around raspberry pi pico. The circuit has a 4 digit seven segment display that allows it to display time or date depending on which buttons have been pressed. It has 3 sources of clock signal. Two of them are external and one is internal (based on a timer interrupt). The external sources accept 36kHz signal. Time can be set using usb-serial command like interface. The fully documented project can be found [here](https://github.com/m1cha1s/clock_and_time_reference).

### Prototype

![Prototype image](https://github.com/m1cha1s/clock_and_time_reference/raw/main/photos/prototype/IMG_20220126_235642.jpg)