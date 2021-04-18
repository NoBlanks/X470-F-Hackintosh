# Ryzentosh (A new Intel Hackintosh is probably better tho)

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

# What doesn't work (properly) (that's confirmed)

- DRM in Safari (Imagine watching Netflix and Hulu lol, DRM should work fine in other browsers)
- Apple TV+ and iTunes Videos 
- Airdrop (can be fixed with an Apple Airport card or in a later update of AirportItlwm)
- Discord crashing every time you join a voice call (can be fixed, search it up on Google or smth)

# Additional Notes (If anyone ever somehow encounters this on Google)
- OpenCore logging is disabled as I weanted it to be disabled, you can reenable it in the config.plist by changing the target to 67
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- All the AMLs were manually compliled but should work normally, if not working, then you should use the prebuilt AMLs from Dortania or make your own (not much of a pain in the ass as I thought)
- Make sure to add the serial number, board number, UUID and the ROM (MAC Address) if anyone is using this (for testing ofc, seriously tho, learn to make your own EFI here: https://dortania.github.io/OpenCore-Install-Guide/) 
- If you have some SICKKKKK RGB and want to be able to change it in macOS, you can use OpenRGB from here (https://gitlab.com/CalcProgrammer1/OpenRGB)
- The Windows 10 EFI folder is contained in this EFI folder so you might be able to dual boot Windows and macOS on the same drive but having them on separative drives is SOOOOOOOOOOOO much better, remove the Microsoft folder in the EFI if you don't need to dual boot with Windows on the same drive or if you're installing Windows and need to use software such as Fuzedrive or StoreMI

# My Socials
- Discord: NoBlanks#7321
- Twitter and Instagram: @noblanks_
