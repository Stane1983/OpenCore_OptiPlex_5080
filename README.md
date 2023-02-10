
# OptiPlex 5080

## Configuration

| Specifications      | Detail                       |
| ------------------- | ---------------------------- |
| CPU                 | Intel(R) Core(TM) i5-10500   |
| Integrated Graphics | Intel UHD Graphics 630       |
| Sound Card          | Realtek ALC3246              |
| Ethernet Controller | Intel i219-LM                |

## MacOS Versions Supported:

- macOS Ventura
- macOS Monterey
- macOS Big Sur
- macOS Catalina

## Changelog

### 10-2-2023

#### Update

- `OpenCore` v0.8.8
- `Airportitlwm` v2.2.0
- `AppleALC` v1.7.8
- `CPUFriend` v1.2.6
- `CpuTscSync` v1.0.9
- `IntelBlueToothFirmware` v2.2.0
- `IntelBlueToothInjector` v2.2.0
- `IntelMausi` v1.0.7
- `Lilu` v1.6.3
- `NVMeFix` v1.1.0
- `RealtekRTL8111Ethernet` v2.4.2 (works on some models that come with that contr', doesn't effect intelmausi)
- `VirtualSMC, SMCDellSensors , SMCProcessor, SMCsuperIO` v1.3.0
- `USBInjectAll` latest
- `WhateverGreen` v1.6.3







#### Change

- Fixed IntelMausi enabled set to `false` in config.plist which disabled the connection in some OptiPlex 5080 models.

## What is Working?

- [x] Native CPU Power Management
- [x] Sleep/Wake
- [x] Intel Graphics
- [x] Hardware Acceleration (1.6GB)
- [x] Audio
- [x] Type-C USB
- [x] Type-C: video and audio
- [x] DisplayPort: video and audio
- [x] USB 3.0
- [x] Brightness
- [x] Built-in mic
- [x] Line-in mic
- [x] Bluetooth Intel
- [x] Intel wireless
- [x] Bootcamp assistant
- [x] iMessage and Facetime (tested in ventura)

## Not working:

- Nothing

## BIOS settings

- [ ] Secure boot enabled
- [ ] Fast Boot
- System Configuration → SATA Operation: AHCI
- [x] VTx in System Options
- [x] Intel virtuallization options

## IMPORTANT

Personnaly I had the best results installing Catalina and then upgrading to Ventura (you can do it without any updates as the kexts and OC are up to date (10/2/2023)


Credit to ``omriberchman`` for the fixes and updates    
Credit to ``Stane1983`` for the orignal files.    
Credit to ``KirillSerogodsky`` for the markdown template and ``omriberchman`` for customizing.

