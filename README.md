# ESP32_CNC_SHIELD_V1.2_30PIN
 30PIN VERSION OF CNC SHIELD
 
 ![My Image](Images/Esp32_Cnc_Shield_30Pin_Front.png)

I was looking for ESP32 devkits for my ESP32_CNC_SHIELD and found a 30 pin version. I made it so big because i needed space for the traces, as i sometimes loose some accurancy milling it out. If it works as intended i`ll make a SMD version.

I have to verify if it´s needed to provide a MOSFET for the mist and add some 5V pins for the endstops and probe.

Just checked that this configuration is working and published the header file to copy in Machines(GCan_Cnc_Shield.h).

When the SD-card module arrives i'll check if it works correctly. 
Today it arrived , so i installed and it worked fine.

Installed the ESP_Cnc_Shield on my CNC machine, adjusted all values from the Arduino Uno: steps, limits, homing directions, etc.
It´s marvelous to work from the web interface, then execute from the sd-card. 
You can even disconnect the web interface once started, it will run to the end of the program.

Next up is to add a powersupply (StepDown) 24V to 5V 500mA(9V 500mA) wich the VIN needs to be able to remove the USB adapter.
