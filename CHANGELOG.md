# Changelog

## Version 2.1

__Hardware:__

- Change to new Safety Relays with direct monitoring of hardware limit switches, updated the schematics accordingly
- Corrected some minor mistakes in the mechanical BoM (e.g. wrong electronics enclosure)
- Added 4C Fuse to the control lines of the stepper motor drivers
- Change to new 5V power supply
- Mounted RUMBA32, Raspberry Pi and DMT542 drivers on DIN rails
- Changed motor connectors to shielded GX20 connectors
- Changed to external sensor boxes for hardware and software limit switches, additionally changed the connectors on the sensors to M12 connectors and the connector to the enclosure to a GX20 connector
- Added 3D printed parts for sensors, cable chains and motor connectors
- Fixed mistake in Breakoutboard layout (Base and Collector of Q1 were swapped)

__Software:__

- Changed installation instructions for the software: Moonraker instead of Octoprint
- Added virtual sensors to printer.cfg
- Added option for Moonraker control to GUI program

__Documentation:__

- Mechanical assembly instructions are now in markdown format
- Updated the electrical assembly instructions for the new hardware

## Version 2.0

- Electronics changed to Rasperry Pi and Rumba32
- Other simplifications e.g. in the power management board
- Up to 6x stepper motor drivers
- Improved safety concept with hardware safe-torque-off and soft and hard limit switches
- New software

## Version 1.0

- Electronics based on Beagle Bone Black and BeBoPr++
- outdated
