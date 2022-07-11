
# akpu - PVI Connector
With this software you can exchange variables between two [B&amp;R](https://www.br-automation.com) PLCs via PVI.

![akpu](https://github.com/bee-eater/akpu/raw/main/img/akpu_Main.gif)

Supported are all base datatypes and also arrays or structs can be directly communicated.

## Download
Can be found under [Releases](https://github.com/bee-eater/akpu/releases/latest)
- v1.0.0.0 [[Installer](https://github.com/bee-eater/akpu/releases/download/v1.0.0.0/akpu-1.0.0.0-Release-x86.msi)]|[[Portable](https://github.com/bee-eater/akpu/releases/download/v1.0.0.0/akpu-1.0.0.0-Release-x86.zip)]

## Use case
- Transfer physical handwheel data to an ARSim instance

## Requirements
- PVI Runtime [Download](https://www.br-automation.com/de/downloads/software/automation-netpvi/pvi-development-setup/)

The application was developed and tested with PVI 4.10!

## How to use
- Just download, execute and have a look at the startup guide :-)
- In order to use it portable, just create a file named "portable" in the root directory. ATTENTION: If the directory is not wirtable (e.g. not run as admin) the settings will be saved in %LOCALAPPDATA%\\akpu\\...

## Additional Information
This application is not an official B&amp;R product! For this reason the use is at your own risk and there is NO claim on support or maintenance.

