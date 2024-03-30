Prerequisite tools:

nRF Connect SDK 2.5.0 
Toolchain: 2.5.0

board: nRF9160 DK

Calibration factor used is 2000 grams. you can use accoridng to your application.
If you want to store your calibration parameters in Flash, you can use settings_subsystem API in zephyr RTOS.

Note:
    you can use different board for your applicaiton,
    you just to need to change the overlay file.