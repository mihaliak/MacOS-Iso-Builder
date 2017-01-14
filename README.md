# Use

	git clone https://github.com/mihaliak/MacOS-Iso-Builder.git
	cd MacOS-Iso-Builder
	chmod +w build.sh
	./build.sh

# Installing in VirtualBox

1. Create VM
2. Run `VBoxManage modifyvm "{vmname}" --cpuidset 00000001 000306a9 00020800 80000201 178bfbff` in terminal where vmname is name of VM
3. Disable audio in VM settings
4. Boot VM and select .iso
5. In installer select language and in menu bar select `Utilities > Disk Utility`, select VirtualBox disk and `Erase` it and format as `Mac OS Extended (Journaled)`
6. Enjoy

# Credits
Credits to julianxhokaxhiu and fuckbecauseican5
