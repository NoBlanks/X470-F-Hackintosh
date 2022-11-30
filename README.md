# Ryzentosh (A new Intel Hackintosh is probably better tho)

OUTDATED EFI, WILL NOT BE UPDATING THIS

- Ryzen 5 5600X
- ASUS ROG STRIX X470-F
- Corsair Vengence LPX DDR4-4000 CL16 16GB
- Patriot Viper Steel DDR4-4000 CL16 16GB
- XPG GAMMIX S11 Pro 1TB M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive (Windows)
- WD Blue 500GB SSD (MacOS)
- Gigabyte Gaming OC RX 6800
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.8.5
- MacOS Monterey 12.6.1

# What doesn't work (excluding most of the issues that only happen on AMD Hackintoshes)

- DRM in Safari, Apple TV+ and iTunes Videos (Can be fixed by installing Catalina and doing DRM fixes)
- Airdrop (can be fixed with an Apple Airport card or in a later update of AirportItlwm)

# Additional Notes
- The SMBIOS is the MacPro7,1 (Mac Pro 2019)
- OpenCore logging is disabled as I weanted it to be disabled, you can reenable it in the config.plist by changing the target to 67 in the Misc section
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- ALL AMLs are manually compiled 
- AMD Patches are set to 6-Cores, change it if your CPU has more cores

# Work in Progress


# Opencore Guide
https://dortania.github.io/OpenCore-Install-Guide/

# My PayPal because why not
- https://paypal.me/Blubot?locale.x=en_US
