# Small-Linux-Bootloader

This is a small linux bootloader with initrd support. It support the X86-64 architecture. 

This is intended for educational only.

This script will compile everything for you:

* The kernel
* The initrd 
* The bootloader 

And then it will pack them and lunch it with QEMU.
You should see this:
![alt text](https://github.com/arnaudmeauzoone/Small-Linux-Bootloader/blob/master/kernel-boot.png)

To run it just run 

```shell
./build.sh
```
