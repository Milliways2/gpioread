# gpioread
**gpioread** is a replacement for the deprecated wiringpi gpio readall utility on Raspberry Pi.

gpioread has the advantage of displaying the ACTUAL programmed GPIO function set by Device Tree on boot rather than the default.

gpioread runs on all Pi models with 40 pin expansion header, including Pi4 and Raspberry Pi Model B Rev 2 with 26 pin expansion header.

This has enhanced functionality - it reports actual configured function on GPIO (useful on the Pi4 with additional modes).
gpioreadc is an enhanced version which displays power pins in colour


As a bonus it is usable on remote machines using the pigpio remote access capability.
The Pi must have remote access enabled.

Run with `gpioread IPaddress`


**Prerequisites**

Requires `python3-pigpio` to be installed and `pigpiod` running
