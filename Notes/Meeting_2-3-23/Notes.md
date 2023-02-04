Physical Pins to ESC:
* 6 digital switch
  * FWD EN
  * Reverse EN
  * Brake Switch
  * Regen Disable
  * Ignition Input
  * Start INput

CAN Information to ECU:
* Motor Temp.



Accumulator Cooling Fans
* Handled by BMS
  * Look into this to make sure it is viable
* May need to buy splitter (likely)


Accelerator
* Accelerator controls torque
* Derivative of pedal position
  * Slip-Aim curves 
* Slip-Ratio between rear wheels and front wheels
  * Take average of front wheel speeds for reference speed to determine slip


IMD 
* Likely just a warning/fault signals through CAN 


Precharge
* PDM acts as relays 


Back EMF in AIR
* Look into outside circuitry


ESC
* Measuring cooling from temp probes goes to ESC analog inputs, then passed to ECU through CAN
* IGBT Temps
* Faults

Driver Tune
* Strength dial for TC/LC combined
  * LC Enable - Toggle button that overrides
  * After ~20Mph auto switches
  * Talk to George to make sure this is okay
* Driver curves dial - not linear, can be changed for different drivers
* Regen Braking Strength Dial



BSPD
* Separate logic for LV (HV shutoff is separate)


BMS
* Avg Temperature
* Max Cell Temperature/list of cells above
* Cell ID for knowing where cells are
* Minimum Cell Voltage
* Max Cell Voltage


Temps/Pressure for Radiators
* Talk to Jack
* Wants many things



