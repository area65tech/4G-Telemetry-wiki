Hardware Integration
====================

Interface Options
-----------------

The AREA65 module supports four communication interfaces that can operate simultaneously.

Connector Pinout
----------------

.. image:: hardware_interfaces.webp
   :alt: Hardware Interfaces

The AREA65 module features the following hardware interfaces:

+---+-------------+---------------------------------------------+
| # | Interface   | Description                                 |
+===+=============+=============================================+
| 1 | 4G SMA      | 4G cellular antenna connector               |
+---+-------------+---------------------------------------------+
| 2 | GPS SMA     | GPS antenna connector                       |
+---+-------------+---------------------------------------------+
| 3 | CAN         | CAN 2.0 bus interface                       |
+---+-------------+---------------------------------------------+
| 4 | Nano SIM    | Nano SIM card slot for cellular connectivity|
+---+-------------+---------------------------------------------+
| 5 | SPI         | SPI interface (3.3V TTL)                    |
+---+-------------+---------------------------------------------+
| 6 | I2C         | I2C interface (3.3V TTL)                    |
+---+-------------+---------------------------------------------+
| 7 | UART        | UART interface (TTL, 5V)                    |
+---+-------------+---------------------------------------------+
| 8 | USB-C       | USB-C connector for power and data          |
+---+-------------+---------------------------------------------+
| 9 | MicroSD     | MicroSD card slot for data logging          |
+---+-------------+---------------------------------------------+

UART
^^^^

+-----+----------+
| Pin | Function |
+=====+==========+
| GND | Ground   |
+-----+----------+
| 5V  | 5V Power |
+-----+----------+
| TX  | Transmit |
+-----+----------+
| RX  | Receive  |
+-----+----------+

**Baud Rate:** 57600 (fixed)
**Voltage:** 5.0V TTL

CAN 2.0
^^^^^^^

+---------+----------+
| Pin     | Function |
+=========+==========+
| GND     | Ground   |
+---------+----------+
| 5V      | 5V Power |
+---------+----------+
| CANL    | CAN Low  |
+---------+----------+
| CANH    | CAN High |
+---------+----------+

**Protocol:** CAN 2.0A/B
**Speed:** Configurable

SPI
^^^

+------+---------------------+
| Pin  | Function            |
+======+=====================+
| MOSI | Master Out Slave In |
+------+---------------------+
| MISO | Master In Slave Out |
+------+---------------------+
| SCK  | Serial Clock        |
+------+---------------------+
| CS   | Chip Select         |
+------+---------------------+
| GND  | Ground              |
+------+---------------------+
| 5V  | 5V Power             |
+------+---------------------+

**Voltage:** 3.3V TTL

I2C
^^^

+-----+-------------+
| Pin | Function    |
+=====+=============+
| GND | Ground      |
+-----+-------------+
| 5V  | 5V Power    |
+-----+-------------+
| SCL | Serial Clock|
+-----+-------------+
| SDA | Serial Data |
+-----+-------------+

**Voltage:** 3.3V TTL
**Address:** Configurable

Power Requirements
------------------

+-----------+-------------------------+
| Parameter | Value                   |
+===========+=========================+
| Voltage   | 5V DC                   |
+-----------+-------------------------+
| Current   | 1A minimum              |
+-----------+-------------------------+
| Connector | USB-C or interface pins |
+-----------+-------------------------+

Mechanical Dimensions
---------------------

+----------------+-------------------------+
| Dimension      | Value (mm)              |
+================+=========================+
| Length         | 78                      |
+----------------+-------------------------+
| Width          | 57                      |
+----------------+-------------------------+
| Height         | 24                      |
+----------------+-------------------------+
| Weight         | 45g                     |
+----------------+-------------------------+
| Mounting Holes | 2x Ø3.3mm through holes |
+----------------+-------------------------+
