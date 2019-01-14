![Logo](admin/repetier.png)
# ioBroker.repetier
=================

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


## Changelog

### 0.0.1
* (coyote1) initial release

## License

The MIT License (MIT)

Copyright (c) 2018 coyote1 <coyote_f@web.de>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
