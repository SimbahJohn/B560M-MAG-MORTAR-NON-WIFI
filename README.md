# B560M-MAG-MORTAR-NON-WIFI
EFI Hackintosh B560M MSI MAG MORTAR NON WIFI

|            |                                       |
| --------   |---------------------------------------|
| Mobo       | MSI-MAG-B560-MORTAR-NON-WIFI              |
| CPU        | Intel(R) Core(TM) i5-11400F            |
| RAM        | GSKILL DDR4 3600  8GBx2            |
| GPU        | RX 6600 SAPPHIRE PULSE            |
| Network    | Realtek PCIe 2.5Gb Ethernet (RTL8125) |
| WIFI       | Intel 8265 + BT 4.2                            |
| Disk       | TEAM MP33 512GB PCIE 3.0                     |
| Input      | G102 Logitech RGB-SYNC                |
| Bootloader | OpenCore 0.8.5 Release                |
| System     | macOS 12.6                          |

## Changelog
### 2022/10/27

1. Initial Upload

# BIOS settings

    Disable Fast Boot
    Disable MSI Fast Boot
    Disable Intel VT-D
    Disable CFG Lock
    
### Recommend BIOS version 7D42v14 - (BIOS not macth = DYOR)
MAG B560M MORTAR NON WIFI DDR4 BIOS download link https://www.msi.com/Motherboard/MAG-B560M-MORTAR/support
![tbTDlD](#####)

### Resizable BAR (ReBAR)

AMD Radeon 6600 cards support ReBAR. To activate this feature you must:

Enable it in BIOS menu (usually next to Above 4G Decoding option, ReBAR is displayed when enabling this other option)
Set config file.plist in order for OpenCore to boot with ReBAR enabled, you have to set the value of Boot >> Quirks >> ResizeAppleGpuBars=0 (instead of -1, default value).

Note: UEFI >> Quirks >> ResizeGpuBars must always be -1.

I have tested the card with ReBAR on and off and I have not noticed any difference. If any of you who read this, i need your help to confirm this, maybe testing using Windows, and Compare it. Thank You.

# Detail:
[Contact Me: ###### "Instagram")

![rvDuwd](###)
![hxJksr](###)
![P03Pnp](###)
![qpfYRs](###)
![aENnOp](###)
![abCFJ0](###)
![Xriq1v](###)
![vvGd6Y](###)

## Geekbench5 Benchmark
![g1](###)
![g2](###)
