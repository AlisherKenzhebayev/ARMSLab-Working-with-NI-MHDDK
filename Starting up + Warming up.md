
1. Reading the FAQ on MHDDK
2. [![LINK](http://www.ni.com/tutorial/54496/en/)] is about interacting with chip object
3. Module built contatins a lot of stuff on both iBus and Chip objects. ![LINK](http://www.ni.com/tutorial/54497/en/) is for iBus.


Tips and Tutorials Passages That You Will Need (TTPTYWN):
```
7. Where do I get the Product ID and Vendor ID for my hardware?


In order to register a driver for a device with the operating system, you will need the Product ID and Vendor ID for your device. The Vendor ID for any National Instruments PCI/PXI device is 0x1093, and, for most devices, the Product ID will identify the specific device model. However, all X Series devices have the Product ID 0xC4C4, so you will need to use the Subsystem Product ID to differentiate between X Series models. Finding the IDs will be operating system specific.

Windows:

    Open the Windows Device Manager.
    Right-click on the NI device and select “Properties.”
    From the “Details” tab, select the “Hardware Ids” from the drop-down box.
    The Product ID is the hex number in “DEV_xxxx”, where “xxxx” is the Product ID.

Linux:

    The command line tool lspci can tell you the Product and Vendor ID for all devices in your system.
```
