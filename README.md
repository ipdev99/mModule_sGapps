## sGapps 10 arm64

**_Magisk Module_  
sGapps Min for Android 10 arm64**

### Caution
Since Gapps are normally an integral part of the system, it will still be treated as such.  
Google apps will still update and be added to userdata.  
_This is a problem since the apps in userdata will still try to run if the module is disabled._  
**Disabling this module will cause an _infinite boot_ due to missing permissions and/or core files.**

- **To remove/disable this module.**
 - Uninstall all updates, clear all cache and stored files related to the apps in this module.
 - Logout of your Google account.
 - Disable module and reboot.  

**The remove/disable steps may not work properly..**  

### Description
- Minimal Gapps.
 - Files pulled from Google Pixel 3aXL _2019-Dec._  

### Download
Available in the releases tab. [Link](https://github.com/ipdev99/mModule_sGapps/releases)

### Install
- Copy the zip file to the device.
- Open Magisk Manager, select Modules and then Install from storage.
- Reboot device

### Recent changes and To-Do
- Work-In-Progress.
- Completely ALPHA status..
- Not planned for long-term support. _(Currently a work-a-round for devices that can not mount system ReadWrite in custom recovery.)_
- _sGapps-min_ is now down to 50 MB.
- _To-Do - sGapps-small_
  - _Figure out the odd revert in gBoard theme when included in the module._
- _To-Do - sGapps-big_
  - _Figure out the odd settings error(s) when Pixel launcher and stock overlays are included in the module._

### Notes
- Feel free to use, change, improve, adapt.  
 - Remember to share.  

### Credits
- The Android Community and everyone who has helped me learn through the years.
- John Wu (@topjohnwu) for all things Magisk.
