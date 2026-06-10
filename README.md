# index

## files 0-4 with two Razer Core X connected to USB4 hub
- 0: root=/dev/nvme0n1p2
- 1: root=/dev/nvme0n1p2 pci=realloc=on
- 2: root=/dev/nvme0n1p2 pci=realloc=on,hpmmiosize=256M,hpiosize=2M,hpmemsize=1G,hpbussize=0x33,pcie_scan_all,big_root_window pcie_port_pm=off pcie_aspm.policy=performance thunderbolt.clx=0
- 3: there is no #3
- 4: root=/dev/nvme0n1p2 pci=realloc=on,,hpmmiosize=256M,hpiosize=2M,hpmemsize=1G,hpbussize=0x33,pcie_scan_all,big_root_window


## files 5-6 with single Razer Core X connected to USB4 hub
- 5: root=/dev/nvme0n1p2 pci=realloc=on,,hpmmiosize=256M,hpiosize=2M,hpmemsize=1G,hpbussize=0x33,pcie_scan_all,big_root_window
- 6: root=/dev/nvme0n1p2


## files 6+xxx after hot-plugging a second Razer Core X
- 6: root=/dev/nvme0n1p2


