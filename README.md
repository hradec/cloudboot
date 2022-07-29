# easy-netboot
A complete solution for network boot of bare metal over PXE/UEFI/OSX netboot. Runs as a docker container, and sets up everything, from DHCP netboot extensions (without having to change the default DHCP server on the network), TFTP and Grub over PXE/UEFI/OSX netboot. 

It allows to customize the boot proccess by bootstraping a tiny core linux distro, using that to bootchain installations and even full live OSes booted over the network. 

