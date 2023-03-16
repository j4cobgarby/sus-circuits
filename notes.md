# Tasks

 - **Divert Power**: potentiometer sliders and LED bars controlled by microcontroller
 - **Calibrate Distributor**: servo motors and push buttons
 - **Keypad**: cherry switches?

# Infrastructure

 - **Door "Locking"**

# Microcontroller options

 - ATmega32u4: can integrate it directly on the PCBs, and very cheap, also can install the arduino bootloader on it
 - ESP32: more expensive but has inbuilt wireless communication

# Communication options

 - Depending on the microcontroller we use it might be easy to wirelessly communicate between microcontrollers to a central server, however there could then be a lot of crosstalk
 - Every task device could be wired by ethernet to a switch
