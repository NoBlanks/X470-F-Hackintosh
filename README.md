# Ryzentosh

- Ryzen 7 2700 (at 4GHz)
- ASUS ROG STRIX X470-F
- Team T-Force Valcan TUF Alliance 32GB (2x16gb) 3600 CL19 (running at 3400MHz CL16-18-18-35-45)
- XPG GAMMIX S11 Pro 1TB M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive (Windows)
- WD Blue 500GB SSD (MacOS)
- MSI GT 710 1GB GDDR3
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.6.8
- MacOS Big Sur 11.2.3

# What doesn't work

- DRM
- Airdrop

# Additional Notes
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- The USB-EC AML was manually compliled but should work normally, if not working, then you should use the prebuilt USB-EC from Dortania here (https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)
- If anyone else is using this EFI (and not using Dortania guide) then make sure to change the serial number, board number, UUID and the ROM (MAC Address)
- If you have some SICKKKKK RGB and want to be able to change it in macOS, you can use OpenRGB from here (https://gitlab.com/CalcProgrammer1/OpenRGB)
