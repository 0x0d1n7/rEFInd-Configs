# rEFInd-Configs
My rEFInd Boot Manager Configs

In this configs, I added a theme and updated the refind.conf file, hid grubx64.efi file and macOS volume from the boot screen.

Install rEFInd first

https://www.rodsbooks.com/refind/getting.html

Ways to mount the EFI partition

 ~ % sudo mkdir /Volumes/efi
 
 ~ % sudo mount -t msdos /dev/disk0s1 /Volumes/efi
