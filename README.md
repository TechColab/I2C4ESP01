# I2C4ESP01
Carrier board for all components needed for a simple I2C on ESP-01 project.  

Designed to fit a 1590A aluminium box with a cut-out for 0.96" OLED display - just under 20x40mm  
Yes, the WiFi still works!  
Yes, there's enough space for the Qwiic connector wires under the ESP-01.  

Flexible, milti-purpose design with essential and common components, power-bus and a mini-patch bay for intermediary components. 
E.g. pull-ups, resistor-dividers, R-C filters etc.  
Accept ESP-01S and ESP-01 with pads to use RST and CHPS or tie them to 3v3 by JP2.  
JP1 allows option to dump power capacitor to GND upon unplugging the DC barel jack.  

## Changes from Rev 0.2 to Rev 0.3
Fixed missing GND connection for Qwiic connector.
