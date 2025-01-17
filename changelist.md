# Change list for Estuary v2.2:
1. Formally support D03 based on DTS.
2. Completely compatible for HiKey\D01\D02 and D03 boards.
3. Firstly support booting system from SAS disk for D02 by default.
4. Upgraded kernel to v4.4.
5. Partly enabled ACPI (Only D02).
6. Improved build script:
	- Support native building.
	- Support both USB-Disk\CD-ISO installation methods.
	- Support automatic PXE environment setup.
	- Support to terminate and restart build task druing building.
7. Improved mini-rootfs to support more useful commands.
8. Enabled CentOS firstly.
9. Firstly integrated ODP and MySQL into Estuary.
10. Added collaboration feature in website.
11. Enabled Docker & Armor tools for all distributions.
12. Improved all documents, and change them into markdown format.
13. Fixed most issues found in rc0 & rc1, include but not limited to: UEFI, network, grub, usb compatibility, build and etc.
14. Support D01 better, to enable boot from NorFlash, PXE, SATA.
15. Enable both 32bits and 64bits minirrotfs for different arch.

# Remained issues:
1. ACPI is not available for D03 yet.
2. KVM is not available based on kernel v4.4 yet.
3. PCIE-SATA card can't work well on D03.
4. SATA is very unstable on D02 board.
