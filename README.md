# UP3D
UP 3D Printer Tools

Build status of MaikStohn/UP3D: [![Build Status](https://travis-ci.org/MaikStohn/UP3D.svg?branch=master)](https://travis-ci.org/MaikStohn/UP3D)

Download: [latest](https://github.com/MaikStohn/UP3D/releases/latest)

Instructions: [up3dtools-how-to](http://stohn.de/3d/index.php/2016/03/10/up3dtools-little-how-to)

---

## up3dtranscode: 

G-Code to UpMachineCode (UMC) converter

usage: up3dtranscode input.gcode output.umc

or with nozzle height added as last parameter

usage: up3dtranscode input.gcode output.umc 123.1

---

## upload: 

UpMachineCode (UMC) uploader, sends the umc file to printer and starts a print

usage: upload output.umc

---

## upshell: 

Interactive printer monitor and debugging tool, use to watch printing

usage: upshell

