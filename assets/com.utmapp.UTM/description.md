UTM is a full featured virtual machine host for iOS. In short, it allows you to run Windows, Android, and more on your iPhone and iPad. More information at https://getutm.app/

## Features

* 30+ processors supported including x86_64, ARM64, and RISC-V thanks to QEMU as a backend
* Fast native graphics through para-virtualization thanks to SPICE
* JIT based acceleration using QEMU TCG
* Frontend designed from scratch for iOS11+ using the latest and greatest APIs
* Create, manage, run VMs directly from your device

## Notes

* When uninstalling, VMs are not automatically deleted. Make sure to delete unused VMs before uninstalling.
* Some poorly written jailbreak tweaks cause iOS to go into a reboot loop if you run out of storage (regardless if UTM is installed or not). To be safe, make sure you never allocate more storage to a VM than the amount of free space you have.
* Settings do not currently work. This will be fixed in a future version.
