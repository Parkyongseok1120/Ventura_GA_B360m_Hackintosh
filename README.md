# Monterey_B360m_Hackintosh
 https://github.com/parkyongsunk/Hackintosh-GA-B360m-aorus-Pro-Monterey

![스크린샷 2022-10-29 오전 1 26 29](https://user-images.githubusercontent.com/41354468/198688380-2e2e14a2-f3b2-45db-b57a-5f61575ecf6e.png)


1. OS : MacOS Montery 12.6
2. CPU : i5 8500
3. RAM : DDR4 Memory 48GB
4. GPU : Sapphire Pulse RX 6600XT 8G
5. Board : Gigabyte b360m aorus pro

BIos Setting

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
1. iGPU(Maybe...Confirmation required.)
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


