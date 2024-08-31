
- OpenCore version : 1.0.1
  
### PC Info

- CPU : Intel 10700
- GPU : AMD RX5700XT
- Motherboard : Gigabyte B460M Arous Elite
- WiFi : Intel AX200


## BIOS Settings

Disable

Serial/COM Port
CSM
CFG LOCK
Intel SGX

Enable

EHCI/XHCI Hand-off
SATA Mode: AHCI
Secure Boot (option)
VT-D
OS Type: Windows 10




### Easy Secure Boot Setting

#### CUSTOM - Enroll EFI Image


BIOS -> SecureBoot -> Key management -> Enroll EFI image



every update change

- OC/opencore.efi (OC Update)
- usr/standalone/i386/boot.efi (macOS Update)

one time

EFI/BOOT/bootx64.efi
EFI/OC/Driver/-.efi
EFI/OC/Tools/-.efi


/usr/standalone/i386/boot.efi
/usr/standalone/i386/apfs_aligned.efi
/usr/standalone/i386/apfs.efi
/usr/standalone/firmware/FUD/MultiUpdater/MultiUpdater.efi
/usr/standalone/firmware/FUD/USBCAccessoryFirmwareUpdater/HPMUtil.efi


### Recommand Save File USB
