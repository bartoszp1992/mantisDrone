# Mantis repo

![Mantis photo](images/mantis_white01.jpg)

**"Mantis" is 1,2" printable freestyle/racing 1S tinywhoop**

# 3D printing
- **frame**
: PA12
- **ducts convertible**
: PC/PETG
- **canopy**
: PA12
- **FC cover**
: PA12
- **base**
: PC-CF / PETG-CF
- **tail support**
: TPU


# BOM

## mechanical
- **base**
: printed basebase
- **frame**
: printed mantis frame
- **propellers**
: HQ 31mm Ultralight 3-Blade Propellers (1.0mm Shaft) or NBD Azi 3 blade 31mm
- **PA screws**
: 4x PA M2x15 screws
- **PA nuts**
: 4x PA M2 nuts

## electronic
- **FC**
: BETAFPV Matrix 1S Brushless Flight Controller 4IN1
- **motors**
: HAPPYMODEL SE0702 KV28000
- **camera**
: CADDXFPV ant lite / BETAFPV C03(SD) or P1 air unit(HD)
> for SD: order also CADDXFPV Camera Accessories OSD Menu Board for ant lite camera, and switch video mode to PAL
- **batteries**
: BETAFPV LAVA 1S 260mAh 3.8V HV 80C BT2.0 (x5) - at least one set
- **charger**
: BETAFPV 6 Ports 1S Battery Charger (optionally with adapter)
- **cable**
: USB-C cable for communication
- **VTX**
: Foxeer reaper nano(only for SD 4in1)

## control
- **controller**
: Jumper Bumblebee, or any other with ELRS and edgeTX
- **batteries**
: 2x 18650 any branded Li-Ion cells for controller supply
- **goggle**
: BETAFPV VR03 or any other analog goggles for SD
- **memory**
: 32G SDcard if you want to record your flights

## software
- **FC config**
: betaflight configurator
- **radio config**
: ExpressLRS Configurator

## firmware
If you are building remotely:
> choose analog OSD Protocol and type **OSD_HD** in custom defines, to build firmware with both- digital and analog OSD

Firmware notice

This repository may include firmware binaries and configuration files for flight controllers and ESCs.

Betaflight firmware is licensed under the GNU General Public License v3.0 (GPL-3.0).
Source code is available at: https://github.com/betaflight/betaflight

Bluejay ESC firmware is licensed under the GNU General Public License v3.0 (GPL-3.0).
Source code is available at: https://github.com/bird-sanctuary/bluejay

All respective rights belong to the original authors and contributors.
This repository does not claim ownership of these projects and only redistributes unmodified binaries for convenience.

Binaries are named with their version, target and build identifier where applicable.
