# Firmware

This respository currently contains two major projects:
* RM25 Project - This was the final firmware design for RM25 (2021-2022 competition car).
* WIP RM26 Project - This project is the most up-to-date version of the 2022-2023 competition car's firmware.

To be able to edit this/work on this firmware the following are needed:
* MoTeC M1 Build - Firmware editing software for our current ECU (MoTeC M150).
* A license file (the license file is a bit hard to get, reach out to Thomas Petr if you require it).


Additional Notes Worth Mentioning:
* MoTeC uses a suite of companion softwares for working with the ECU, broken up into: M1 Build, M1 Tune, i2 (in our case i2 Pro), and C125 Dash Manager.
* M1 Build - Creates the structure of the firmware.
* M1 Tune - Takes that structure and allows you to input calibration files, tuning of (in the past) engines, launch control, traction control, e-throttle algorithms, and needed for data logging (pulling data from the RJ45 Comm port on the car).
* i2 Pro - This takes the data logged from the ECU on the car and plots it in meaningful ways (very powerful for diagnosing issues and determining how to make the car perform better.
* C125 Dash Manager - This is the dedicated software needed to adjust the firmware of the C125 dash logger that we use (allows for changing the display for the driver). It also allows for more functionallity but that has been mainly what has been used for in the past. It mainly acts as a pass-through for more analog voltage/temperature ports and ability to read GPS data.

I will add the C125 dash firmware when I get the chance, but I need to get it off of an SSD on my computer that died (waiting on a M.2 to Thunderbolt dock).
* Received the dock, just need to get the information off of it (haven't had the time and it's not crucial right now).




