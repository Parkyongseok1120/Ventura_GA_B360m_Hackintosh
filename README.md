# Monterey_GA-B360m-Aorus-PRO_Hackintosh


![스크린샷 2022-10-29 오후 3 57 14](https://user-images.githubusercontent.com/41354468/198820199-e0751a61-e674-4bad-a43d-f1e8e48e22b0.png)


# Release version : 

**Latest Version Release** : https://github.com/Parkyongseok1120/Ventura_GA_B360m_Hackintosh/releases/tag/Hackintosh_v2.0

Previous Releases: https://github.com/Parkyongseok1120/Ventura_GA_B360m_Hackintosh/releases


# My PC Setting:

1. OS : MacOS Monterey 12.6
2. CPU : intel i5 8500
3. RAM : Samsung DDR4 Memory 48GB
4. GPU : Sapphire Pulse RX 6600XT 8G
5. Board : Gigabyte b360m aorus pro


# What Works:

1. GPU
2. USB Ports
3. AirDrops(Need to BCM94360cd)
4. BT & Wifi(Need to BCM94360cd or wifi/BT dongle)
5. iCloud 
6. Sleep + Wake up
7. iMessage
8. AppStore
9. Sound

# Not Works:
1. iGPU(Maybe...Confirmation required. It doesn't seem to work.)
2. LAN(My computer is using a USB converter Lan.)

# Tasks to be done before execution:

1. Add SMBIOS content.
2. Bios Setting:

- BIOS->CSM Support disable
- BIOS->Windoews 8/10 Features ->Other OS
- BIOS->Secure Boot->Secure Boot Enable-> disabled
- BIOS->Boot->UEFI
- Peripherals->Super IO Configuration-> Serial Port Disable
- Peripherals->SATA AND RST->SATA Mode selection-> AHCI

# If the GPU is AMD RX 5XX or RX 4XX, but only the black screen is printed:

1. Add keepsyms=1 alcid=1 in 'boot-args'.
2. Check AppleDebug and ApplePanic in 'Misc' -> 'debug'.

in this setting,
The Rx570 worked well when I used it.
