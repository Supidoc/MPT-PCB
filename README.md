# M.P.T.-PCB
The Multipurpose tracker (or just MPT) is a pocket sized device to track you habits. Although it is primarily designed to serve as a habit tracker it can be used for many other things. 

The MPT features a 2.79" 142x428 full color display. To control the device a 4-Way Joystick as well as 5 User Buttons are available.
At the core of the MPT sits an ESP32-S3. The ESP32-S3 has enough power to run the display at 30Hz, features WIFI and Bluetooth LE.
To get accurate timestamps for your habit entries a Microcrystal RTC module is included. The RTC is directly connected to the batteries so that it runs even when the rest of the system is in shutdown.
The whole system is powered by two 10440 570mAH LI-ION batteries by Keepower. The batteries already integrate a protection circuit. MPT features a fuel gauge and a charger to measure battery capacity and charge the device over USB-C. The USB-C Port also serves as the debug interface for ESP's JTAG-Over USB feature.
