# EFI-Motherboard-X79-OpenCore-Hackintosh

### OpenCore

[OpenCore 0.7.7](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x 

### Hardware

- Motherboard: huanan-x79
- CPU: Intel Xeon E5-2450v2
- GPU: Coloerfire AMD HD 7750 1G
- Ethernet: Realtek RTL8100(G) Family Controller

#### PS:
 - All USB ports are customized well.(only usb2.0)
 - Wireless Connection & Bluetouch don't be customized.

### Bios Setup

| Name | Option |
| ----- | --- |
|Advanced->USB Configuration->XHCI Hand-off|Enabled|
|Advanced->USB Configuration->EHCI Hand-off|Disabled|
|Advanced->Super IO Configuration->Serial Port 0 Configuration ->Serial Port|Disabled|
|Boot->Quiet Boot|Disabled|
|Boot->Fast Boot|Disabled|
|Boot->CSM parameters->Launch CSM|Disabled|

