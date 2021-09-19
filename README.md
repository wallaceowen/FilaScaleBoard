# FilaScale

This is a small ESP32-based board designed to fit directly behind a standard 2.8" SPI-driven QVGA TFT touchscreen.
It was built to the requirements of a filament monitoring device.  The board provides:

* Humidity, temperature and weight monitoring of a spool of filament in a drybox
* RFID tag reader
* QVGA display with touchscreen for user interface
* SDCard for logging, local configuration
* Expansion interfaces (two SPI, one I2C, and four uncommitted GPIO on two separate headers)
* Serial communications with a host
* Wifi and bluetooth connectivity

![My board](/filacase.png)


## The firmware
The board runs code for monitoring the humidity and weight of a spool of 3D printer filament in a drybox.
  [GitHub](https://github.com/wallaceowen/FilaScale/tree/master)
The code is C++, and uses the simple Arduino toolchain.
