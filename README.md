THIS IS NOT COMPLETE EFI AND README
SLOSE1 HACKED and DELETED!! I LOVE YOU CHINA❤️❤️🖕❤️❤️

need

USB 3.0 PATCH
OC 1.0.0
Clean Args
Clean readme..

- OpenCore version : 1.0.0
### PC Info

- CPU : Intel 10700
- GPU : AMD RX5700XT
- Motherboard : Gigabyte B460M Arous Elite

	
|       Disable        |                 Enable                 |
| :------------------: | :------------------------------------: |
|      Fast Boot       |           Above 4G decoding            |
|  Re-Size BAR Support |            Hyper-Threading             |
|   Serial/COM Port    |           EHCI/XHCI Hand-off           |
|         CSM          |           OS type: Windows 10          |
|       CFG Lock       |            SATA Mode: AHCI             |
|      Intel SGX       |   Secure Boot(first install disable)   |
|                      |                  VT-d                  |



### Secure Boot Setting - old
  
#### CUSTOM - Enroll EFI Image

- BOOT/Bootx64.efi

- OC/opencore.efi

- OC/drivers/Openruntime.efi

- OC/drivers/Opencanopy.efi

- OC/tools/CleanNvram.efi

- OC/tools/boot.efi <- I found that the boot.efi of macOS might be different. Please import and add the boot.efi separately from /usr/standalone/i386 in finder.

- kernel/fud/HPMUtil.efi

- kernel/fud/MultiUpdater.efi

- kernel/i386/apfs_aligned.efi

- kernel/i386/apfs.efi

