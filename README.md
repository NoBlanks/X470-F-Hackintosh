# Ryzentosh (A new Intel Hackintosh is probably better tho)

- Ryzen 7 2700 (at 4GHz)
- ASUS ROG STRIX X470-F
- Team T-Force Valcan TUF Alliance 32GB (2x16gb) 3600 CL19 (running at 3400MHz CL16-18-18-35-45)
- XPG GAMMIX S11 Pro 1TB M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive (Windows)
- WD Blue 500GB SSD (MacOS)
- MSI GT 710 1GB GDDR3
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.6.9
- MacOS Big Sur 11.5 Beta 1

# What doesn't work (properly) (that's confirmed)

- DRM in Safari, Apple TV+ and iTunes Videos (Can be fixed by installing Catalina and doing DRM fixes)
- Airdrop (can be fixed with an Apple Airport card or in a later update of AirportItlwm)
- Discord crashing every time you join a voice call (can be fixed and happens on every AMD hackintosh, search it up on Google or smth)

# Additional Notes
- The SMBIOS is the MacPro7,1 (Mac Pro 2019)
- OpenCore logging is disabled as I weanted it to be disabled, you can reenable it in the config.plist by changing the target to 67 in the Misc section
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- The Windows 10 EFI folder is contained in this EFI folder, remove the Microsoft folder if you're installing Windows on a separate drive or booting anything else that's not Windows 10
- ALL AMLs are manually compiled 

# Work in Progress
- USB Map the second internal USB 2.0 header

# Opencore Guide
https://dortania.github.io/OpenCore-Install-Guide/

# My Socials
- Discord: NoBlanks#7321
- Twitter and Instagram: @noblanks_

# My PayPal because why not
- https://paypal.me/Blubot?locale.x=en_US
