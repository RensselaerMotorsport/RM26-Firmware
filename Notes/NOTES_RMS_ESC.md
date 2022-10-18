Relevant Information on Cascadia-Reinhart Motorsports ESC:
* There are many documents that outline everything about the ESC we are using (RMS PM100DX) and they are included in this folder also, but I am going to outline things that matter the most as of right now.
* Relevant Acronyms Explained:
  - VSM - Vehicle State Machine - similar to a finite state machine (motor state information)
* The RMS ESC gives all relevant data needed over CAN bus:
  - Internal States - tells us the state of the motor (start, running, pre-charge, wait, ready, fault, shutdown in progress, etc.). This information is available in the CAN Protocol PDF on page 24.
  - Key Switch Mode - Allows for traditional ignition switch functionality. 


Important Notes:
* Startup requires that the brake be pressed on startup for the ESC to turn on. Needs to just be set to the enumeration connected to the brake light (uses brake pressure to determine state). 
* Need to determine how/when the start state should engage the start sound. Does it engage the sound when HV is just on or whenever the engine is actually "Started."


