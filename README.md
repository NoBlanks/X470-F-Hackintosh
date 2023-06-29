# ASUS ROG STRIX X470-F Gaming Hackintosh

OUTDATED EFI, WILL NOT BE UPDATING THIS, I DO NOT OWN THIS MOTHERBOARD ANYMORE, AND SUPPORT WILL NOT BE PROVIDED ANYWHERE

- Ryzen 5 5600X
- ASUS ROG STRIX X470-F
- Corsair Vengence LPX DDR4-4000 CL16 16GB (2x8GB)
- Patriot Viper Steel DDR4-4000 CL16 16GB (2x8GB)
- Total 32GB RAM, running at 3933 due to infinity fabric limitations
- XPG GAMMIX S11 Pro 1TB M.2 NVME SSD (Windows)
- Some Toshiba 2TB Hard Drive
- WD Blue 500GB SSD (MacOS)
- Gigabyte Radeon RX 6800 Gaming OC
- Intel AX200 (Wifi and Bluetooth)
- Opencore 0.8.5
- MacOS Monterey 12.6.1

# What doesn't work (excluding the issues that only happen on AMD Hackintoshes)

- DRM in Safari, Apple TV+ and iTunes Videos (Can be fixed by installing Catalina and doing DRM fixes)
- Airdrop (Use an Apple Airport card instead)

# Additional Notes
- The SMBIOS is the MacPro7,1 (Mac Pro 2019)
- OpenCore logging is disabled as I wanted it to be disabled, you can reenable it in the config.plist by changing the target to 67 in the Misc section
- There's an AML that disables the main PCIe slot, the AML is currently disabled but can be enabled in the config.plist
- All AMLs are manually compiled 
- AMD Patches are set to 6-Cores, change it if your CPU has more cores, read more here (https://github.com/AMD-OSX/AMD_Vanilla)
- Both USB 2.0 Headers are mapped to bluetooth in the kext, remap if needed

# Opencore Guide
https://dortania.github.io/OpenCore-Install-Guide/

# My PayPal because why not
- https://paypal.me/Blubot?locale.x=en_US
