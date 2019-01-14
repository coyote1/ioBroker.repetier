# Documentation

ioBroker adapter to retrieve data from Repetier-Server for 3d printers.

The following data is requested:

- Temperature Extruder
- Temperature Bed
- Name Print Part
- Layerheight
- Printed Time complete
- Printed Time
- Rest time
- Print status in %
- Firmware
- Flow in %
- Speed in %


## Configuration:

Enter the IP address of Repetier server, enter port (default 3344) and API key (can be found in the Repetier-Server WebUI Settings -> Global Settings -> Connectivity). Then enter the existing printer names (this name must agree with the name in Repetier-Server and printer names must be entered in alphabetical order).
