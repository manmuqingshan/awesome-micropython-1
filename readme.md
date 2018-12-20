<h1 align="center">
  <img width="400" src="https://raw.githubusercontent.com/mcauser/awesome-micropython/master/logo.svg?sanitize=true" alt="Awesome MicroPython"><br>
</h1>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome MicroPython libraries, frameworks, software and resources.

Inspired by the [Awesome lists](https://github.com/sindresorhus/awesome).

## Contents

- [Libraries](#libraries)
	- [Audio](#audio)
	- [Communications](#communications)
		- [Ethernet](#ethernet)
		- [GPS](#gps)
		- [IR](#ir)
		- [OneWire](#onewire)
		- [Radio](#radio)
		- [RFID](#rfid)
	- [Display](#display)
		- [LCD Character](#lcd-character)
		- [LCD Graphic](#lcd-graphic)
		- [LED Matrix](#led-matrix)
		- [LED Segment](#led-segment)
	- [Sensors](#sensors)
		- [Distance Ultrasonic](#distance-ultrasonic)
		- [Motion Inertial](#motion-inertial)
- [Community](#community)
- [Books](#books)
- [Resources](#resources)
- [Miscellaneous](#miscellaneous)
- [Contributing](#contributing)

## Libraries

### Audio

* [KT403A-MP3](https://github.com/jczic/KT403A-MP3) - Driver for KT403A, used by DFPlayer Mini and Grove MP3 v2.0.
* [JQ6500](https://github.com/rdagger/micropython-jq6500) - Driver for JQ6500 UART MP3 modules.

### Communications

#### Ethernet

* [Official wiznet5k](https://github.com/micropython/micropython/tree/master/drivers/wiznet5k) - Official driver for the WIZnet5x00 series of Ethernet controllers.

#### GPS

* [micropyGPS](https://github.com/inmcm/micropyGPS) - Full featured GPS NMEA sentence parser.

#### IR

* [micropython-necir](https://github.com/MattMatic/micropython-necir) - NEC infrared capture for TL1838 IR receiver LEDs.

#### OneWire

* [Official OneWire](https://github.com/micropython/micropython/tree/master/drivers/onewire) - For devices using the OneWire bus, eg Dallas ds18x20.

#### Radio

* [micropython-radio](https://github.com/peterhinch/micropython-radio) - Protocols for nRF24L01 2.4Ghz radio modules.
* [Official nRF24L01](https://github.com/micropython/micropython/tree/master/drivers/nrf24l01) - Official driver for nRF24L01 2.4Ghz radio modules.

#### RFID

* [micropython-mfrc522](https://github.com/wendlers/micropython-mfrc522) - Driver for NXP MFRC522 RFID reader/writer.

### Display

#### LCD Character

* [Grove_RGB_LCD](https://github.com/dda/MicroPython/blob/master/Grove_RGB_LCD.py) - Driver for SeeedStudio's Grove RGB LCD.
* [micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd) - Driver for I2C 2x16 LCD Screens.
* [python_lcd](https://github.com/dhylands/python_lcd) - Driver for HD44780 compatible dot matrix LCDs.

#### LCD Graphic

* [micropython-oled](https://bitbucket.org/thesheep/micropython-oled) - Collection of drivers for monochrome OLED displays, PCD8544, SH1106, SSD1306, UC1701X.
* [micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544) - Driver for Nokia 5110 PCD8544 84x48 LCD modules.
* [micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920) - Library for simple graphic primitives on ST7920 128x64 monochrome LCD panel using ESP8266 and SPI.
* [MicroPython_PCD8544](https://github.com/AnthonyKNorman/MicroPython_PCD8544) - ESP8266 driver for Nokia 5110 PCD8544.
* [Official LCD160CR](https://github.com/micropython/micropython/tree/master/drivers/display) - Driver for official MicroPython LCD160CR display with resistive touch sensor.

#### LED Matrix

* [micropython-max7219](https://github.com/mcauser/micropython-max7219) - Driver for MAX7219 8x8 LED matrix modules.

#### LED Segment

* [micropython-tm1637](https://github.com/mcauser/micropython-tm1637) - Driver for TM1637 quad 7-segment LED modules.

### Sensors

#### Distance Ultrasonic

* [micropython-hcsr04](https://github.com/rsc1975/micropython-hcsr04) - Driver for HC-SR04 ultrasonic distance sensors.

#### Motion Inertial

* [MPU6050-ESP8266-MicroPython](https://github.com/adamjezek98/MPU6050-ESP8266-MicroPython) - Driver for MPU6050 Accelerometer/Gyroscope on ESP8266.

## Community

* [MicroPython Forum](https://forum.micropython.org/) - Online community of over 3400 users discussing all things related to MicroPython.
* [MicroPython on Twitter](https://twitter.com/micropython?lang=en) - Follow MicroPython on Twitter for latest news and updates.

## Books

* [Programming with MicroPython: Embedded Programming with Microcontrollers and Python](http://shop.oreilly.com/product/0636920056515.do) - by Nicholas H. Tollervey.

## Resources

* [MicroPython](http://micropython.org) - Project website. Test drive the pyboard. Try MicroPython online with unicorn.
* [MicroPython on GitHub](https://github.com/micropython/micropython) - Submit bug reports, follow and join in development on GitHub.
* [MicroPython Official Documentation](http://docs.micropython.org/) - For various ports, including quick reference, general information, examples and tutorials.
* [MicroPython Wiki](http://wiki.micropython.org/Home) - Community generated documentation and examples of the features of MicroPython and the pyboard.
* [MicroPython Newsletter](http://micropython.org/newsletter) - Subscribe to the MicroPython newsletter for news and announcements including new features and new products.
* [MicroPython Store](https://store.micropython.org/) - Where you can buy the pyboard, housings, skins, books, connectors and peripherals.
* [MicroPython on Wikipedia](https://en.wikipedia.org/wiki/MicroPython)

## Miscellaneous

* [MicroPython Kickstarter](https://www.kickstarter.com/projects/214379695/micro-python-python-for-microcontrollers) - 1,931 backers pledged £97,803 to help bring this project to life.
* [MicroPython on the ESP8266 Kickstarter](https://www.kickstarter.com/projects/214379695/micropython-on-the-esp8266-beautifully-easy-iot) - 1,399 backers pledged £28,534 to help bring this project to life.

## Contributing

Contributions and suggestions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mcauser/awesome-micropython/blob/master/contributing.md) first.

## License & Trademarks

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
