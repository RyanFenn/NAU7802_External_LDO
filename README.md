NAU7802_External_LDO
===========================================================
NOTES:
* This fork originates from SparkFun's NAU7802 library (https://github.com/sparkfun/SparkFun_Qwiic_Scale_NAU7802_Arduino_Library). From Sparkfun's libary, a fork was created by joesphan to add code so that NAU7802_LDO_EXTERNAL could be used for setting the LDO state. joesphan's libary was then forked to create the current library.
* When the begin() method is called, the LDO value will be set to external now (instead of 3.3V).

CHANGELOG:
* joesphan -> Code added so that the LDO can be set to NAU7802_LDO_EXTERNAL.
* RyanFenn -> Changed .h and .cpp file names and adjusted #include in .cpp file to match.
* RyanFenn -> Code added so that LDO is set to NAU7802_LDO_EXTERNAL when the begin() method is called.


[*SparkFun Qwiic Scale - NAU7802 (SEN-15242)*](https://www.sparkfun.com/products/15242)

The SparkFun Qwiic Scale - NAU7802 is a small breakout board for the NAU7802 that allows you to easily read load cells to measure weight. By connecting the amplifier to your microcontroller you will be able to read the changes in the resistance of the load cell, and with some calibration you'll be able to get very accurate weight measurements. This can be handy for creating your own industrial scale, process control or simple presence detection.

Connect a load cell and the Qwiic Scale translates the data into something your microcontroller can read. The NAU7802 is an ADC with built in gain and I<sup>2</sup>C output to amplify and convert the readings from a standard load cell. A load cell is basically a device that translates pressure or force into electrical signals. In most cases this signal is very small and needs to be amplified. There are many popular chips that read the change and amplify it, but the NAU7802 goes one step further and converts everything to a true I<sup>2</sup>C output.  

The board provides 4 spring terminals to connect your load cell with no soldering required. Additionally, the Qwiic connectors provide an easy interface to connect this board to your microcontroller again with no soldering required. In addition to the I<sup>2</sup>C pins, the board also breaks out an interrupt pin, AVDD to the edge of the board. The differential input signals (plus a second set of input signals) are broken out to the middle of the board as well.

SparkFun labored with love to create this code. Feel like supporting open source hardware? 
Buy a [board](https://www.sparkfun.com/products/15242) from SparkFun!

Thanks to:

* gamix25 for fixing [signed bit error](https://github.com/sparkfun/SparkFun_Qwiic_Scale_NAU7802_Arduino_Library/pull/1)

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **keywords.txt** - Keywords from this library that will be highlighted in the Arduino IDE. 
* **library.properties** - General library properties for the Arduino package manager. 

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfun/Qwiic_Scale)** - Main repository (including hardware files)

License Information
-------------------

This product is _**open source**_! 

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
