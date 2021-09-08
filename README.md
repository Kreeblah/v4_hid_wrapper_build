# v4_hid_wrapper_build
Build environment resources for [v4_hid_wrapper](https://github.com/tkoecker/v4_hid_wrapper) and a pre-built Intel hex file to flash to an assembled device.

In order to flash the binary, just run:

    avrdude -p atmega32u4 -P YOUR_DEVICE_PORT -c avr109 -U flash:w:FILE_NAME:i
