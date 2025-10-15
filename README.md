# Samsung Disable Force Encryption
## Disable File Encryption (DFE) for Samsung devices with erofs partitions
This is a custom recovery-flashable script designed to disable file-based encryption (FBE v2) on Samsung device with the s5e8845 SoC. This fix "0 MB internal storage" issues, and decrypts /data.

## Use with caution.
! Haven't test on slot _b , but it'll probably work.
## Supported Device
- Samsung Galaxy S25
- Samsung Galaxy S24
- Samsung Galaxy S23


## Installation
1. Boot into custom recovery
2. Copy Samsung_DFE.zip to your device. Recommended path is on '/tmp'
3. Install as zip
4. Format /data when prompted (required to fully disable encryption).
5. Reboot to system.

## Developer Notes
This script was written with the help of OpenAI, especially for the EROFS handling.
This modifies your vendor and super partitions, and it will nuke your /data too, so please back up your data.

## License
This project is licensed under the [MIT License](https://github.com/Lyinceer/SM-A556E_DFE/blob/main/LICENSE).

## Credits
- [blackeangel](https://github.com/blackeangel) for UKA utils.
- And to all Contributors in every repositories and scripts I used.
-afaneh92 (https://github.com/afaneh92) for converting to work on non A/B devices

