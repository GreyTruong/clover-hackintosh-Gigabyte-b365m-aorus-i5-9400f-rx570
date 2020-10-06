# clover-hackintosh-Gigabyte-b365m-aorus-i5-9400f-rx570
This is EFI for Install MacOS Catalina 10.15.7. In order to install MacOS on Gigabyte mainboard by Clover, we should configure the Bios like below:

Fast Boot : Disabled
VT-d : Disabled
Storage Boot Operation Control: UEFI (bắt buộc)
XHCI Hand-off: Enabled (bắt buộc)
CSM Support: Disabled (nếu có)
Windows 8 Features: Other OS (nếu có)
Security Device Support: Disabled
Network Stack : Disabled
Legacy USB Support: Auto
LAN PXE Boot Option ROM: Disabled
Advanced Memory Settings Extreme Memory Profile: Bạn thiết lập là Profile1 nhé.


+ for dGPU:
Initial Display Output: PCIe x1 Slot
Integrated Graphics : Disabled

+ for iGPU:
Initial Display Output: iGFXIntegrated Graphics (hoặc Internal Graphics) : Enabled
DVMT Pre-allocated: 128MB, (for 2k or 4k display, up to 256MB or emore)
Above 4G Decoding: Enabled
