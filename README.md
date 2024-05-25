# OpenCore EFI for ASRock B550-HDV
OpenCore EFI for ASRock B550-HDV motherboard with tested config.plist

## Tested Images
macOS Sonoma(10.14) Recovery ✅

## Tested OSes 
Windows 11 ✅

## Modify config before using

Use GenSMBios to generate serial keys for PlatformInfo in config.plist located at EFI/OC

The Type part gets copied to Generic -> SystemProductName.

The Serial part gets copied to Generic -> SystemSerialNumber.

The Board Serial part gets copied to Generic -> MLB.

The SmUUID part gets copied to Generic -> SystemUUID.

The Apple ROM part gets copied to Generic -> ROM.

Future updates of readme coming soon
