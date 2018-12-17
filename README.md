# Mission Statement

This is a repository of code I've modified for use with an Anycubic Kossel Plus 3D printer. Built in code based on the Marlin 1.1.8 framework.


# Marlin 3D Printer Firmware

Additional documentation can be found at [The Marlin Documentation Project](https://www.marlinfw.org/).


# Custom Functions and Features
## Filament Change: Work in Progress

Function to heat the extruder and reverses motor on the filament intake. Prompts user to manually retract the loaded filament as well during this process. Click the control knob when displayed prompt has been completed. The filament intake motor will now drive forwards to help feed new filament in. Click once for cooldown procedures at this point. Click twice at any time to end function.

## Emergency Stop: NOT YET
## Detailed Print Progress: NOT YET

On print pause or manual stop, the printer will display the line number the print was aborted at. This will allow one to better troubleshoot or restart a particular print job.

## Networking Features and Monitoring: NOT YET

I plan on adding an ESP01 ESP8266 wifi module to the Trigorilla board. Thingiverse [resource](https://www.thingiverse.com/thing:2798147).

## UI Optimization on the LCD Display: NOT YET
