# hackintosh-Yoga-3-Pro

Files for hackintoshing the Lenovo Yoga 3 Pro

## Acknowledgements

_[RehabMan](https://github.com/RehabMan)_ - helped with getting the graphics working and provided the inital config.plist file.

## What works

- Intel HD 5300 integrated graphics with HiDPI 1600x900
- native power management
- WiFi
- audio
- battery status (apply patches in DSDT_battery.txt)
- built-in webcam
- iMessage, if you follow [this guide](https://www.tonymacx86.com/threads/an-idiots-guide-to-imessage.196827/)

## What doesn't work

- touchpad
- bluetooth
- built-in microphone
- sleep (doesn't work with laptops anyways)
- Siri (lack of built-in microphone, didn't test with 3.5mm jack mic yet)

## Instructions

0. Set pre-allocated DVMT to at least 64MB (96MB or 128MB recommended) by `setup_var 0x18c 0x4`
1. Make a bootable usb the [vanilla way](https://www.reddit.com/r/hackintosh/comments/68p1e2/ramblings_of_a_hackintosher_a_sorta_brief_vanilla/).
2. copy contents of hackintosh stuff into the Install MacOS High Sierra partition for post install.
3. Perform post install and enjoy!
