Devices in Testbench
* ECU
* PDM
* RMS ESC
* BMS
* IMD (eventually, leave a spot for it)
* Motor (eventually, leave this to Amar)

Work with Amar for the ESC & BMS connections

All important files/datasheets should be in our RM GitHub:
https://github.com/RensselaerMotorsport/Firmware/tree/main/Notes 

Important Connections
* CAN Connections
* 3 busses on the ECU that connect to everything else
  * 1 bus is 500kbps (CAN Bus 3)
    - IMD Connects to this eventually and likely the C125 Dash (irrelevant right now)
  * 2 busses at 1Mbps (CAN Busses 1 & 2)
    - ESC on CAN Bus 1
    - BMS and PDM on CAN Bus 2
  * CAN connections should be twisted (Lauren can explain how to do this)
  * CAN connections need termination resistors
    - Except for the IMD (built-in)
    - Ask Chris about this, he has the best method for this
* 12V power to all devices (from current 12V batteries we have)
  * Hot connection of 12V battery goes to the PDM
* GND connections should go back to a small star ground which connects to the GND of the battery.
* Need to have RJ45/Ethernet Connector for the ECU made


More needs to be done but this is a good start.




