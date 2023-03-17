# Tasks

 - **Divert Power**: potentiometer sliders and LED bars controlled by microcontroller
 - **Calibrate Distributor**: servo motors and push buttons
 - **Keypad**: cherry switches?
 - **Keycard**: Light gates to specify a speed (Making it as painful as in-game)
 - **Fix Wiring**: Using real wires, and RGB LEDs to change the desired arrangements

# Infrastructure

 - **Door "Locking"**: Light that can be triggered by the impostors, signals to players they cannot pass 
 - **Emergency Meeting**: Big old button, maybe causes all player phones to vibrate?
 - **Admin**: Actual cameras connected up to some pi's. Scatter these around
 - **Medbay**: 

# Microcontroller options

 - ATmega32u4: can integrate it directly on the PCBs, and very cheap, also can install the arduino bootloader on it
 - ESP32: more expensive but has inbuilt wireless communication

# Communication options

 - Depending on the microcontroller we use it might be easy to wirelessly communicate between microcontrollers to a central server, however there could then be a lot of crosstalk
 - Every task device could be wired by ethernet to a switch
 - Another option is to ommit communication from the 'tasks', and have the phone/rfid confirming the task log it. This would also allow 'faking' a task
