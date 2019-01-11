![Logo](admin/repetier.png)
# ioBroker.repetier
=================

Adapter für die Datenabfrage von Repetier-Server für 3d Drucker.

Folgende Daten werden abgefragt:

- Temperatur Extruder
- Temperatur Bett
- Name Druckteil
- Layerhöhe
- Gesamte Druckzeit
- gedruckte Zeit
- Druckstatus in %
- Firmware
- Flow in %
- Speed in %


## Konfiguration:

IP Adresse vom Repetier Server eingeben, den Port (default 3344) und den API-Key (findet man im Repetier-Server WebUI. Einstellungen -> Globale Einstellungen -> Konnektivität) Danach noch die vorhandenen Druckernamen eintragen (Dieser Name muss mit dem Namen in Repetier-Server überinstimmen)

## Contributors

- coyote

## Changelog

### 0.0.1
* (coyote) initial release

## License

The MIT License (MIT)

Copyright (c) 2018 Coyote <coyote_f@web.de>

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
