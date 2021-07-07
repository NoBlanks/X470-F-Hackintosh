# Ryzentosh (A new Intel Hackintosh is probably better tho)

- Ryzen 7 2700 (at 4GHz)
- ASUS ROG STRIX X470-F
- Team T-Force Valcan TUF Alliance 32GB (2x16gb) 3600 CL19 (running at 3466MHz CL16-18-19-35-40)
- XPG GAMMIX S11 Pro 1TB M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive (Windows)
- WD Blue 500GB SSD (MacOS)
- MSI GT 710 1GB GDDR3
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.7.1
- MacOS Monterey Dev Beta 1

# What doesn't work (excluding most of the issues that only happen on AMD Hackintoshes)

- DRM in Safari, Apple TV+ and iTunes Videos (Can be fixed by installing Catalina and doing DRM fixes)
- Airdrop (can be fixed with an Apple Airport card or in a later update of AirportItlwm)
- macOS 12 Monterey Dev Beta 2 and Public Beta 1 doesn't work due to the AMD patches, until then, wait for new AMD patches

# Additional Notes
- The SMBIOS is the MacPro7,1 (Mac Pro 2019)
- OpenCore logging is disabled as I weanted it to be disabled, you can reenable it in the config.plist by changing the target to 67 in the Misc section
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- ALL AMLs are manually compiled 

# Work in Progress


# Opencore Guide
https://dortania.github.io/OpenCore-Install-Guide/

# My Socials
- Discord: NoBlanks#7321
- Twitter and Instagram: @noblanks_

# My PayPal because why not
- https://paypal.me/Blubot?locale.x=en_US
