# foxBMS

foxBMS is a free, open and flexible development environment for the design of
battery management systems. It is the first universal BMS development
environment.

## foxBMS Project Setup
The general setup files for the foxBMS project are found in the
foxBMS-setup repository (https://github.com/foxBMS/foxBMS-setup).
It includes a setup script for Windows (setup.bat) and *nix like systems
(setup.sh) which clone all needed repositories. After cloning the repositories
all needed documentation will be generatedd  automatically. The documentation is
found in directory ./build. Further build instuctions are found by checking
build -h on Windows and ./build -h on *nix link systems.

The general documentation files for the foxBMS project are found in the
foxBMS-documentation repository (https://github.com/foxBMS/foxBMS-documentation).
The sphinx documentation is found in foxBMS-documentation/sphinx while the doxygen
documentation configuration is found in foxBMS-documentation/doxygen. The doxygen
documentation itself is found in the software sources of the primary and secondary
microcontroller.

foxBMS is made out of two Microcontroller Units (MCU), named primary and
secondary. The C code for the primary MCU is found in the repository
foxBMS-primary (https://github.com/foxBMS/foxBMS-primary). The C code for the
secondary MCU is found in the repository foxBMS-secondary
(https://github.com/foxBMS/foxBMS-secondary).

The layout and schematic files for the foxBMS hardware are found in the
foxBMS-hardware repository (https://github.com/foxBMS/foxBMS-hardware).

The foxConda-installer repository contains the installer for the foxConda
environment. This environment provides all the tools necessary to generate
the documentation, compile the code for the MCUs and flash the generated
binaries on the MCUs.

A generated version of the Sphinx documentation can be found at
http://foxbms.readthedocs.io/en/latest/. It explains the structure of the
foxBMS hardware, how to install the foxConda environment and how to use
foxConda to compile and flash the sources.