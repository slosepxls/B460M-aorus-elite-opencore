
- OpenCore version : 1.0.1
  
### PC Info

- CPU : Intel 10700
- GPU : AMD RX5700XT
- Motherboard : Gigabyte B460M Arous Elite
- WiFi : Intel AX200

|       Disable        |                 Enable                 |
|   Serial/COM Port    |           EHCI/XHCI Hand-off           |
|         CSM          |           OS type: Windows 10          |
|       CFG Lock       |            SATA Mode: AHCI             |
|      Intel SGX       |          Secure Boot(Option)           |
|                      |                  VT-d                  |



### Easy Secure Boot Setting

#### CUSTOM - Enroll EFI Image

- BOOT/Bootx64.efi

every update change

- OC/opencore.efi
- usr/standalone/i386

one time
 
- kernel/i386/apfs_aligned.efi
- OC/drivers/Openruntime.efi
- OC/drivers/Opencanopy.efi
- OC/tools/CleanNvram.efi
- BOOT/Bootx64.efi

- kernel/i386/apfs.efi
- fud/HPMUtil.efi
- usr/standalone/fud/MultiUpdater.efi
- usr/standalone/i386/apfs_aligned.efi
- usr/standalone/i386/apfs.efi
