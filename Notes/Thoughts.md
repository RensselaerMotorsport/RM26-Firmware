* Should I separate the ESC from the Motor tree structure (so it's standalone)?
* Should I also have a separate Accumulator tree substructure, or should I leave it under the Motor one?
  - What would fall under the accumulator substructure besides BMS?

* Should I just make parameters to hold the CAN information for things like vehicle states?

* May be worth looking into DBC files for easier control over CAN information

* It may be far easier to still use a Simulink model for Traction Control and offload it to a microcontroller/microprocessor instead. Will just need to send and receive information over CAN or a protocol. 
  - If we offload to something like a Raspberry Pi we can also do wireless telemetry in the process.



