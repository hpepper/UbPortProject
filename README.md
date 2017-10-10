# UbPortProject
UB port project folder

## References
* https://wiki.ubports.com/wiki/How-to-install-UBports-on-your-device
* https://github.com/MariusQuabeck/magic-device-tool

1. start with a brand new Nexus 5
2. sudo apt install android-tools-fastboot
3. 



# Troubleshooting

## Troubleshooting ubport installation

#### lsusb doesn't show the phone
Wrong cable.

### magic-device-tool

This problem isn't seen when the phone is detectable

'fastboot devices' repoert a line

tried: I'm guessing this is due to a missing 'fastboot' command
  Nope, didn't fix it.

```
Detecting device

./devices/nexus5/android/bootloader.sh: line 88: syntax error near unexpected token `else'
./devices/nexus5/android/bootloader.sh: line 88: `else'
```
/snap/magic-device-tool/289/devices/nexus5/android/bootloader.sh

#### adb: unable to open file backup.ab
Try installing:

sudo apt install android-tools-adb
