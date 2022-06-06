# MacOS Monterey on the Framework Laptop

With OpenCore 0.8.0.

https://dortania.github.io/OpenCore-Install-Guide/

This EFI is the end product of the above guide. I suggest you follow the guide for IceLake Laptops, and then compare your EFI to mine.

##### What doesn't work
- Integrated Graphics / IGPU
- Graphics Acceleration / IGPU
- Backlight control / IGPU
- Sound, speaker, microphone / IDT 92HD95
- Integrated Thunderbolt 4
- Goodix Fingerprint scanner
- ALS
- Intel Neural Accelerator

Failed trying to get the AppleIntelICLGraphics driver to load by spoofing as IceLake device-id and AAPL,ig-platform-id.
Failed trying to get audio to work by spoofing TigerLake Intel Smart Sound Controller as Ice Lake Intel Smart Sound Controller.

Framework community forums: https://community.frame.work/t/macos-on-framework-laptop/2957/39

