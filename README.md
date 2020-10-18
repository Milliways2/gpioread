# gpioread
**gpioread** is a replacement for the deprecated wiringpi gpio readall utility on Raspberry Pi.

gpioread has the advantage of displaying the ACTUAL programmed GPIO function set by Device Tree on boot rather than the default.

gpioread runs on all Pi models with 40 pin expansion header, including Pi4 and Raspberry Pi Model B Rev 2 with 26 pin expansion header.

This has enhanced functionality - it reports actual configured function on GPIO (useful on the Pi4 with additional modes).

gpioread by default displays power pins in colour.
To restore non-coloured output uncomment the 2 lines # non-coloured output and comment out # coloured output.

gpioread has been refactored to allow use as a module (NOTE to use as a module it must be saved as gpioread.py)

gpioreadp displays pull on Raspberry Pi4 using the raspi-gpio utility.

As a bonus gpioread is usable on remote machines using the pigpio remote access capability.
The Pi must have remote access enabled.

Run with `gpioread IPaddress`


**Prerequisites**

Requires `python3-pigpio` to be installed and `pigpiod` running
