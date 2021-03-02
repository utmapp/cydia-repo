UTM is a full featured virtual machine host for iOS. In short, it allows you to run Windows, Android, and more on your iPhone and iPad. More information at https://getutm.app/

This package **requires** AppSync Unified from Karen's Repo. Make sure to add [https://cydia.akemi.ai/][1] to your repository list before installing!

**Note upgrading from < v2.0.22:** The old version of this package installs UTM to /Applications (just like other jailbreak apps). This was an issue because UTM uses sandboxed features and was partially broken when installed that way. Since AppSync Unified was released for iOS 14, UTM now installs the sandboxed IPA directly and as a result your old VMs will not be visible. If you had an older version installed, you need to move your VMs from `/var/mobile/Documents` to a temporary location and then open it from the built-in Files app to import it into the UTM sandbox location. Then, you can delete the old files.

## Features

* 30+ processors supported including x86_64, ARM64, and RISC-V thanks to QEMU as a backend
* Fast native graphics through para-virtualization thanks to SPICE
* JIT based acceleration using QEMU TCG
* Frontend designed from scratch for iOS11+ using the latest and greatest APIs
* Create, manage, run VMs directly from your device

## Notes

* When uninstalling, the app and data are not deleted automatically. You can use the built-in Files app to delete data (under UTM) and the UTM app from your home screen.
* Some poorly written jailbreak tweaks cause iOS to go into a reboot loop if you run out of storage (regardless if UTM is installed or not). To be safe, make sure you never allocate more storage to a VM than the amount of free space you have.

[1]: cydia://url/https://cydia.saurik.com/api/share#?source=https://cydia.akemi.ai/