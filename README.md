Adafruit Python DHT Sensor Library
==================================

Python library to read the DHT series of humidity and temperature sensors on a Raspberry Pi or Beaglebone Black.

Designed specifically to work with the Adafruit DHT series sensors ----> https://www.adafruit.com/products/385
It is also know to work with AM2302 based sensors.

This is a fork of https://github.com/adafruit/Adafruit_Python_DHT so that I could put a copy up on PyPi as this hasn't been done by the original author.

Currently the library is only tested with Python 2.6/2.7.

For all platforms (Raspberry Pi and Beaglebone Black) make sure your system is able to compile Python extensions.  On Raspbian or Beaglebone Black's Debian/Ubuntu image you can ensure your system is ready by executing:

````
sudo apt-get update
sudo apt-get install build-essential python-dev
````


The library can be installed using pip

````
pip install adafruit_python_dht
````

or by downloading the source archive from:

PyPi https://pypi.python.org/pypi/Adafruit_Python_DHT othe download link on the right, 

Github https://github.com/hexdump42/Adafruit_Python_DHT

expanding the archive, and executing:

````
sudo python setup.py install
````

You can test by using the script Adafruit_DHT which is installed as part of the distribution.

````
usage: sudo Adafruit_DHT [11|22|2302] GPIOpin#

example: sudo Adafruit_DHT 2302 4 - Read from an AM2302 connected to GPIO #4
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution
