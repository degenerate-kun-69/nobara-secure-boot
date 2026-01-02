# Nobara-secure-boot
 shell script to enable secure boot in nobara
## Notes
 The shell script should work for other distributions, as long as you swap line 13 and 14 with your distribution's sbctl package. You can find the exact command from the ## Install part in https://github.com/Foxboron/sbctl
 
## Pre-use steps
 1. Enter your bios, and reset secure boot to setup mode
 2. **DO NOT** enter any other operating system after this. head straight into the nobara boot you want to sign for secure boot
## Usage
Clone and cd into this repository with 
```bash
git clone https://github.com/degenerate-kun-69/nobara-secure-boot.git/ && cd nobara-secure-boot
```
then run the script as root with 

```bash 
sudo sh secureboot-nobara.sh
```
## Issues
Please open an issue in [#issues](https://github.com/degenerate-kun-69/nobara-secure-boot/issues) so i can find the fixes

## Contributions
Everyone is welcome to contribute. fork into this repository and open a pull request along with the description of any changes
