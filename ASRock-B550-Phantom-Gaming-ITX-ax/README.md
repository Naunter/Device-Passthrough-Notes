- Motherboard: `Asrock B550 Phantom Gaming-ITX-ax`
- UEFI BIOS Version: `B550 Phantom Gaming-ITX/ax P2.30`

- IOMMU groups with ACS patch
  - `pcie_acs_override=downstream,multifunction` is set in `/etc/default/grub`  
```
IOMMU Group 0:
	0000:00:01.0 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Renoir PCIe Dummy Host Bridge [1022:1632]
IOMMU Group 1:
	0000:00:02.0 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Renoir PCIe Dummy Host Bridge [1022:1632]
IOMMU Group 2:
	0000:00:02.1 PCI bridge [0604]: Advanced Micro Devices, Inc. [AMD] Renoir PCIe GPP Bridge [1022:1634]
IOMMU Group 3:
	0000:00:08.0 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Renoir PCIe Dummy Host Bridge [1022:1632]
IOMMU Group 4:
	0000:00:08.1 PCI bridge [0604]: Advanced Micro Devices, Inc. [AMD] Renoir Internal PCIe GPP Bridge to Bus [1022:1635]
IOMMU Group 5:
	0000:00:14.0 SMBus [0c05]: Advanced Micro Devices, Inc. [AMD] FCH SMBus Controller [1022:790b] (rev 51)
	0000:00:14.3 ISA bridge [0601]: Advanced Micro Devices, Inc. [AMD] FCH LPC Bridge [1022:790e] (rev 51)
IOMMU Group 6:
	0000:00:18.0 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166a]
	0000:00:18.1 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166b]
	0000:00:18.2 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166c]
	0000:00:18.3 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166d]
	0000:00:18.4 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166e]
	0000:00:18.5 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:166f]
	0000:00:18.6 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:1670]
	0000:00:18.7 Host bridge [0600]: Advanced Micro Devices, Inc. [AMD] Device [1022:1671]
IOMMU Group 7:
	0000:01:00.0 USB controller [0c03]: Advanced Micro Devices, Inc. [AMD] Device [1022:43ee]
IOMMU Group 8:
	0000:01:00.1 SATA controller [0106]: Advanced Micro Devices, Inc. [AMD] Device [1022:43eb]
IOMMU Group 9:
	0000:01:00.2 PCI bridge [0604]: Advanced Micro Devices, Inc. [AMD] Device [1022:43e9]
IOMMU Group 10:
	0000:02:08.0 PCI bridge [0604]: Advanced Micro Devices, Inc. [AMD] Device [1022:43ea]
IOMMU Group 11:
	0000:02:09.0 PCI bridge [0604]: Advanced Micro Devices, Inc. [AMD] Device [1022:43ea]
IOMMU Group 12:
	0000:03:00.0 Ethernet controller [0200]: Intel Corporation Ethernet Controller I225-V [8086:15f3] (rev 02)
IOMMU Group 13:
	0000:04:00.0 Network controller [0280]: Intel Corporation Wi-Fi 6 AX200 [8086:2723] (rev 1a)
IOMMU Group 14:
	0000:05:00.0 VGA compatible controller [0300]: Advanced Micro Devices, Inc. [AMD/ATI] Cezanne [1002:1638] (rev c8)
IOMMU Group 15:
	0000:05:00.1 Audio device [0403]: Advanced Micro Devices, Inc. [AMD/ATI] Device [1002:1637]
IOMMU Group 16:
	0000:05:00.2 Encryption controller [1080]: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 10h-1fh) Platform Security Processor [1022:15df]
IOMMU Group 17:
	0000:05:00.3 USB controller [0c03]: Advanced Micro Devices, Inc. [AMD] Renoir USB 3.1 [1022:1639]
IOMMU Group 18:
	0000:05:00.4 USB controller [0c03]: Advanced Micro Devices, Inc. [AMD] Renoir USB 3.1 [1022:1639]
IOMMU Group 19:
	0000:05:00.6 Audio device [0403]: Advanced Micro Devices, Inc. [AMD] Family 17h (Models 10h-1fh) HD Audio Controller [1022:15e3]
```

