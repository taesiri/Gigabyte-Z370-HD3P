# Gigabyte-Z370-HD3P

Open Core EFI folder for my Hackintosh - macOS Monterey (12)

![Image](Images/Info.png)

## Notes

⚠️ Pelase change the Serial number in SMBios before

This is still a WIP. 

* USB Bluetooth finally works thanks to [`BlueToolFixup.kext`](https://github.com/taesiri/Gigabyte-Z370-HD3P/tree/main/EFI/OC/Kexts/BlueToolFixup.kext)
    * Airdrop works
    * Handoff works
    * Shared Clipboard works
    * Trackpad and BT Mouse works
    * Monterey's feature Airplay works - Can mirror iPhone/iPad on the Mac without any app
    * Sidecar doesn't work!
* CPU information is wrong. The CPU is `Intel Core i7-8700K`
* USB Mapping is not quite right, but I am not gonna fix it.
* These [CSR USB Bluetooth](https://www.amazon.com/Bluetooth-Adapter-EKSEN-Transmitter-Receiver/dp/B078Y6HK4T) did not work for me, I am using [Asus USB-BT400](https://www.asus.com/us/Networking-IoT-Servers/Adapters/All-series/USBBT400/)

## Acknowledgment

All of the Kext files are taken from [Dortania's](https://dortania.github.io/builds/) website.

## Config

| Hardware    	| Detail                       	|
|-------------	|------------------------------	|
| CPU         	| Core i7 - 8700K              	|
| Motherboard 	| Gigabyte Z370 HD3P           	|
| RAM         	| 4x16GB Geil 2400Mhz          	|
| VGA         	| Radeon RX 5600 XT OC           |
| Storage     	| Samsung 970 EVO 250GB - NVMe 	|
| WiFi Card   	| TP-Link AC1900 Archer T9E    	|
| Bluetooth   	| Asus USB-BT400              	|
