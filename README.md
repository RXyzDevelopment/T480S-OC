# Specification of my ThinkPad T480S

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-8350U (Kaby Lake Refresh)                |
| GPU       | Intel UHD Graphics 620               |
| SSD       | Samsung 980 500GB M.2 NVMe SSD       |
| Memory    | 8GB DDR4 2400Mhz                     |
| Camera    | 720p Camera and IR Camera                        |
| WiFi & BT | Intel AC-8265                        |

# To do fix
- Not booting sometimes and require a force restart (may related to BTPatcher)
- WhatsApp (App Store) sometimes flicker
- Maybe more?

# Compatibility?
Sonoma 14.0 (23A5312d)

# iMessage note
For privacy concern: I wiped my Serial Number, please generate your own.
For how-to, please read: https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo

# Note!
- For sleeping, you have to press power button to wake it from sleep.
- This is only for Intel WiFI Card (AC-8265 in this case)
- It's important to note that the touchscreen on macOS is a bit clunky, best to disable it if you don't really use touchscreen.

# What's Working
- WiFI (Intel AC-8265)
- Trackpad/Trackpoint
- Power Management
- Sleep/closing the lid
- Fan controlling (Please install the YogaSMC app seperately)
- Apple Music Lossless/Dolby (unfairgva)
- USB 3/Type-C
- Audio
- Brightness
- Graphic Acceleration
- Touchscreen (If you have Touch Screen variant, please download VoodooI2CELAN Kext seperately)
- BlueTooth (Remapped fixed it)
- Webcam (Same thing as above) 

# Not working (Sonoma)
- Fingerprint (Touch ID)
- IR Camera (Face ID)
- Maybe more(?)

# Borked 
- HDMI output (color messed up) (Ventura and Sonoma)

# Untested
- WWAN (no WWAN Module)
- Ethernet (no Ethernet cable to test)
- Thunderbolt 3 (no ThunderBolt device-capable to test)
- Lot of stuff I don't bother to test

# Screenshot
- TBD, screenshot soon

# Credit
    Thanks to Acidanthera for providing AppleALC, BrcmPatchRAM, HibernationFixup, Lilu, NVMeFix, OcBinaryData, OpenCorePkg, RestrictEvents, VirtualSMC, VoodooInput, VoodooPS2, and WhateverGreen
    Thanks to OpenIntelWireless for providing AirportItlwm and IntelBluetoothFirmware.
    Thanks to RehabMan and Sniki for providing BrightnessKey
    Thanks to VoodooI2C for providing VoodooI2C.
    And thank you to Hackintosh Discord Server and some people I know from Telegram for helping me out creating this EFI!

#
