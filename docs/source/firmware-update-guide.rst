Firmware Update Guide
=====================

Follow these steps to successfully update the firmware on your 4G Telemetry module.

Prerequisites
-------------
Ensure you have downloaded the required files from the `4G-Telemetry GitHub Releases page <https://github.com/area65tech/4G-Telemetry/releases>`_. You will need the firmware ``.bin`` file and the flasher utility ``.zip`` archive.

Step-by-Step Instructions
-------------------------

1. **Download the Release Files**
   Navigate to the GitHub releases page and download the latest firmware ``.bin`` file alongside the flasher utility.

2. **Extract the Flasher Utility**
   Locate the downloaded flasher ``.zip`` file and extract its contents to an easily accessible folder on your computer. Open the extracted folder and launch the flasher application.

3. **Identify and Select the COM Port**
   You must select the correct COM port corresponding to your module in the flasher utility. If you are unsure which COM port to use, follow these steps:

   * Leave the flasher utility open and unplug the module from your computer.
   * Take note of the COM ports currently available in the list.
   * Plug the module back into your computer.
   * The COM port list will update (or the port number will increase). Select the newly appeared COM port.

   .. note::
      If the module is not read by your computer and no new COM port appears, you need to download and install the `CH340 driver <https://cdn.sparkfun.com/assets/learn_tutorials/8/4/4/CH341SER.EXE>`_. 

4. **Select the Firmware File**
   Within the flasher utility, use the file selection option to browse for and select the firmware ``.bin`` file you downloaded in Step 1.

5. **Flash the Firmware**
   Start the flashing process by pressing the flash button. Do not disconnect the module during this time. The update is complete only when the flasher utility displays a "Mission Completed" message.