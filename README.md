# Trash
just trash
https://circuitdigest.com/microcontroller-projects/raspberry-pi-dht11-interfacing-with-python-code

DHT sensor and resberry pi display
https://chatgpt.com/c/67f7328a-bcdc-800c-812a-9e43aa2dc5cc

Firebase project
https://chatgpt.com/share/67f6b394-4510-800f-8c64-83b3371757f9

https://www.youtube.com/watch?v=s_-nIgo71_w

multimodel
https://chatgpt.com/share/67f73b0f-a130-8006-8173-a59d9560024c


Client sErver

https://chatgpt.com/c/67f740ff-1894-8006-b24d-0b5e5efaa61c




Check if it's detected

Open the terminal and type:


lsblk



sudo fdisk -l
Look for something like /dev/sda1 — that’s your pendrive.

Mount the USB drive

Create a mount point:

sudo mkdir /mnt/usb
Mount it:

sudo mount /dev/sda1 /mnt/usb
(Replace /dev/sda1 with your actual device name if different.)

Access files

Now you can read/write to /mnt/usb.

💡 Extra Tips:
If the drive is FAT32 or exFAT, it should work out of the box.

For NTFS drives, you might need to install support:


sudo apt install ntfs-3g
Use sudo umount /mnt/usb before unplugging it to avoid data corruption.

