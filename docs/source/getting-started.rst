Getting Started
===============

Package Contents
----------------

- AREA65 4G Telemetry Module
- 4G + GPS 2-in-1 Antenna
- 4-Pin XH Cable
- 6-Pin XH Cable
- USB-C Cable

Initial Setup
-------------

SIM Card Installation
^^^^^^^^^^^^^^^^^^^^^

1. Make sure that the module is powered off (unplug the module from all power sources).
2. Open the module with 2mm Hex key, by unscrewing the 4 M2.5 bolts on the base of the module.
3. Insert Nano SIM card into the SIM holder (by sliding the sim holder cover).
4. Ensure SIM has active data plan.
5. Put the lid back on, and reinsert the M2.5 bolts with the 2mm Hex key.

Wifi Setup
^^^^^^^^^^^^^^^^^^^^^

1. Connect the module to a computer through the USB or the Type C port. 
2. Ensure that the correct COM port is selected. Open the serial monitor on Arduino IDE or similar applications.  
3. To reset the wifi connection, type 'reset_wifi'. This will reset the current wifi settings in the module. 
4. Open your phone or laptop and connect to the wifi 'AREA65-TELEM-XXXX'.
5. Open the pop-up to connect to the Wifi you would like the module to be connected to. 
6. Press connect. 

Antenna Connection
^^^^^^^^^^^^^^^^^^

1. Connect 4G antenna wire to 4G SMA connector (by twisting the connector, twist it until is is handtight).
2. Connect GPS antenna wire to GPS SMA connector.

Power Connection
^^^^^^^^^^^^^^^^

Connect 5V @ 1A power via:

- USB-C port (recommended for setup)
- Communication interface pins (CAN, UART, I2C)

Cloud Platform Access
^^^^^^^^^^^^^^^^^^^^^

1. Visit AREA 65 Live Monitoring platform (`4G Telemetry GUI <https://4g-telemetry-gui.area65tech.com>`_)
2. log in with the username and password given in the package (default username and password is the serial number)
3. Configure dashboard and data visualization

Next Steps
----------

- :doc:`arduino-library` - Use Area65Sender library for Arduino projects
- :doc:`hardware-integration` - Connect sensors
- :doc:`api-reference` - Data protocol details
- :doc:`troubleshooting` - Common issues
