Things that I've learned about M1 Build worth noting:
* There is a lot of bloat in the M1 Build firmware in general.
* I started making a new entirely rewritten project and quickly realized that all of the bloat I wanted to remove from the original project was quickly coming back. 
  - This bloat is kind of unavoidable from what I can tell, it gets a little better if you use the VCU Hardware option but I'm unsure if we're able of using that (need to test this).
  - Going to make a very basic test firmware to communicate between the RMS ESC and the M150 ECU to determine if it's possible to use the VCU option and also to test the communication/ESC. 

Notes about general firmware creation:
* The M1 Build User Manual is pretty good but it's still often better to look at the GPA package as an example (example firmware from MoTeC that we have in the RM Google Drive, reach out to Tom Petr if you require this). Additionally, the RM25 is a good example also.

Notes on Enumerations:
* Enumerations are just variables that hold the current global states of things (in a sense at least).
* Something that confused me for awhile was that the original Engine State Object just defaulted to Engine.State.Value, but it wasn't something that was visible because it is a MoTeC specific enumeration (cannot be changed). This can also be done with a custom object (such as Motor State) and I was able to default Motor.State to Motor.State.Value (just simplifies things a little bit).


 


