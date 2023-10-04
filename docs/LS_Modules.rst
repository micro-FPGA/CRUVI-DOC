List of CRUVI LS (Low Speed) modules
====================================

CR00001 SPI Flash BGA24
-----------------------
.. image:: LS_Modules/CR00001-01-3D.jpg

This module is a simple SPI Flash add-on board. Can be assembled with any SPI flash in BGA24 6x8 mm package. 
I2C identification EEPROM is provided. 
Note that only 3.3V SPI Flashes are supported by the standard CRUVI LS hosts. It is allowed to use CR00001 with 1.8V Flash if your CRUVI LS host board supports 1.8V VCC for the LS slot.

+-------+----------+-------+
| CRUVI | Net Name | Note  |
+=======+==========+=======+
| 1     | I2C SDA  |       |
+-------+----------+-------+
| 2     | I2C SCL  |       |
+-------+----------+-------+
| 3     | SPI DQ3  |       |
+-------+----------+-------+
| 4     | SPI CS   |       |
+-------+----------+-------+
| 5     | SPI DQ2  |       |
+-------+----------+-------+
| 7     | SPI DQ1  |       |
+-------+----------+-------+
| 8     | SPI SCK  |       |
+-------+----------+-------+
| 9     | SPI DQ0  |       |
+-------+----------+-------+
| 6     | GND      |       |
+-------+----------+-------+
| 10    | VCC      | 3.3V  |
+-------+----------+-------+


CR00002 SPI Flash SO8
---------------------

This module is a simple SPI Flash add-on board. Can be assembled with any SPI flash in SO8 package. 
I2C identification EEPROM is provided. There is optional additional I2C EEPROM on board.
Note that only 3.3V SPI Flashes are supported by the standard CRUVI LS hosts. It is allowed to use CR00002 with 1.8V Flash if your CRUVI LS host board supports 1.8V VCC for the LS slot.



