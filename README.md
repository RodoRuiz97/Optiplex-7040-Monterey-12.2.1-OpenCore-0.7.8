# Intel-Core-i5-6500-Monterey-12.2.1-OpenCore-0.7.8
Successfully Installed Monterey on Optiplex 7040


*also Tested on macOS Monterey 12.2.1


PC configuration

•Intel Core i5 (6500) 3.2GHz - 4 Core - 4 Thread

•32GB DDR4

•SSDPEMKF256G8 NVMe INTEL 256GB

•WDS500G2B0A 500GB 2.5" SATA

•Gigabit Ethernet 10/100/1000

•Intel® HD Graphics 530 2GB 4K 


Bios configuration

•F2 key intering in bios

•Default Factory reset

•Uncheck Enable Legacy Option ROMS

•Disable Serial Port

•SATA Operation AHCI

•Disable TPM

•Disable VT

•Graphics auto to intel HD


Apply Save setting and Exit.

*I Created my self with SSDTime WINDOWS 10 x64

°UEFI Variables
In order to run macOS successfully a number of EFI BIOS variables need to be modified. The included OpenCore bootloader contains an updated
modGRUBShell.efi, which includes a setup_var command to help do just that.

the graphics is ok to boot up (macOS Monterey 12.2.1)

°Note: the UEFI Variables will lose after set BOIS to factory default!
