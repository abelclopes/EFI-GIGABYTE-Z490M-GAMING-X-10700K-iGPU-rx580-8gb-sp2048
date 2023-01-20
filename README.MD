# Gigabyte Z490M Gaming X + i7 10700K + iGPU + rx 580 2048sp
<br>
you will need to change the bios of the rx 580 8gb 2048sp

<br>
Change bios and check compatible card: [Tutorial](https://www.youtube.com/watch?v=2D71w_jB4MI)

<br>
configure vda: [Tutorial](https://www.youtube.com/watch?v=CpyExVjCeMY&t)

**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.8

## Complete hardware specs
- Intel i7 10700K @ Stock
- Gigabyte Z490M Gaming X
- iGPU UHD 630
- 16Gb DDR4

## What works
- macOS Big Sur, macOS Catalina and macOS Monterey, Ventura
- Audio
- HDMI/DP
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- N/A

## Kexts used:
- AppleALC.kext
- IntelMausi.kext
- Lilu.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## EFI With only ipgu
[EFI-GIGABYTE-Z490M-GAMING-X-10700K-iGPU](https://github.com/abelclopes/EFI-GIGABYTE-Z490M-GAMING-X-10700K-iGPU)


## Geekbench Results:
- N/A :(

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 10th Intel Gen - Comet Lake](https://github.com/abelclopes/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE)

## Discord - Universo Hackintosh
- [Access Discord](#)