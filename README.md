# unc0ver-jailbreak-for-iOS-12.0-12.1.2

Last updated at: 02/11/2019

01/30/2019 - v3.0.0~b1 was released for public testing with the following changes:

iOS 11.0 - 11.4.1 support for A9/A9X/A10/A10X/A11 devices with voucher_swap by @_bazad

01/30/2019 - v3.0.0~b1 was recompiled to fix the in-app version number

01/30/2019 - v3.0.0~b2 was released for public testing with the following changes:

Fix UI to show that it supports iOS 11.0 - 11.4.1
Update credits for @_bazad

01/30/2019 - v3.0.0~b3 was released for public testing with the following changes:

Fix a bug in installing Cydia

01/30/2019 - v3.0.0~b4 was released for public testing with the following changes:

Fully fix a bug in installing Cydia

01/30/2019 - v3.0.0~b5 was released for public testing with the following changes:

Fix a bug with extracting rsync

01/30/2019 - v3.0.0~b6 was released for public testing with the following changes:

Fix the voucher_swap exploit for the iPhone Plus and X models

01/31/2019 - v3.0.0~b7 was released for public testing with the following changes:

Fix and enable voucher_swap exploit for iPad Air 2

01/31/2019 - v3.0.0~b8 was released for public testing with the following changes:

Fix a possible infinite loop for iOS 11.1 and voucher-swap exploit
Fix a bootstrap error related to libapt/apt7

02/03/2019 - v3.0.0~b9 was released for public testing with the following changes:

Make diagnostics include the log file again

02/03/2019 - v3.0.0~b10 was released for public testing with the following changes:

Enable partial (Export/Un-Export Kernel Task Port, Set HSP4 as TFP0, Dump APTicket, Overwrite Boot Nonce, Log Slide, Log ECID, Disable Auto Updates) iOS 12.0 - 12.1.2 support for 16K (A8X - A12) devices (A12 and A8X excluded for now)
Use a more efficient way for finding the kernel base
Change the order of certain stages
Show an alert at the end of the jailbreak to list the system wide affects that have been done
Increase the reliability of the voucher_swap exploit
Change the default boot nonce generator to 0x1111111111111111
Log the kernel version string on launch
Update the default preference configuration to have Disable Auto Updates on by default
Warning: Partial iOS 12 support does not include Cydia or Substrate due to certain jailbreak patches not working yet. The main use of it is the nonce setter and the auto updates disabler

02/04/2019 - v3.0.0~b11 was released for public testing with the following changes:

Fix bugs in the device / version checker
Fix typos

02/04/2019 - v3.0.0~b12 was released for public testing with the following changes:

Add iOS 12.0 - 12.1.2 support for the restart button

02/04/2019 - v3.0.0~b13 was released for public testing with the following changes:

Fix async_wake
Fix voucher_swap to work correctly on all 16K devices (A8X and A12 still excluded for now)

02/05/2019 - v3.0.0~b14 was released for public testing with the following changes:

Fix jailbreak when old resources package has not been deleted
Fix re-jailbreak when tfp0 is exported

02/05/2019 - v3.0.0~b15 was released for public testing with the following changes:

Fix async_wake again
Improve the code

02/05/2019 - v3.0.0~b16 was released for public testing with the following changes:

Fix a bug in log window
Fix a bug in logging
Add more debugging to RootFS remount

02/05/2019 - v3.0.0~b17 was released for public testing with the following changes:

Fix a bug in extracting bootstrap / installing Cydia

02/06/2019 - v3.0.0~b18 was released for public testing with the following changes:

Fix a theoretical bug in async_wake
Fix a typo
Fix a bug in device / firmware checker

02/06/2019 - v3.0.0~b19 was released for public testing with the following changes:

Fix a logic bug in device / firmware checker

02/07/2019 - v3.0.0~b20 was released for public testing with the following changes:

iOS 11.1 - 11.4.1 support for A7/A7X/A8 devices with v1ntex by @tihmstar
Fix a bug in logging and the log window

02/08/2019 - v3.0.0~b21 was released for public testing with the following changes:

Fix a theoretical bug in downloading the kernelcache from Apple for v1ntex
Fix a possible bug in determining page size
Add more debugging to downloading the kernelcache from Apple for v1ntex

02/10/2019 - v3.0.0~b22 was released for public testing with the following changes:

Extend the partial iOS 12 support with root filesystem remount as R/W
Enable disabling app revokes on iOS 12

02/10/2019 - v3.0.0~b23 was released for public testing with the following changes:

Enable RootFS Restore on iOS 12

02/10/2019 - v3.0.0~b24 was released for public testing with the following changes:

Don't update the kernel version string to make jailbreaking faster and third-party jailbreak detection harder
Switch to a new technique for detecting the jailbroken state
Enable the jailbroken state detection on iOS 12

02/10/2019 - v3.0.0~b25 was released for public testing with the following changes:

Add more debugging to the root filesystem remount
Clean up some logic for log window pipes

02/10/2019 - v3.0.0~b26 was released for public testing with the following changes:

Clean up the root filesystem remount

02/11/2019 - v3.0.0~b27 was released for public testing with the following changes:

Significant reliability improvements to the voucher_swap exploit on iOS 12

02/15/2019 - v3.0.0~b28 was released for public testing with the following changes:

Add the v3ntex exploit by @tihmstar with major improvements from @Jakeashacks and @notcom, only for the iPad Air 2 and iPad Mini 4 models running iOS 12.0 - 12.1.2 (for now)

02/22/2019 - v3.0.0~b29 was released for public testing with the following changes:

Full-fledged iOS 12.0 - 12.1.2 support for A8X-A11 devices with Cydia and Substrate by @saurik
Important Notes:
Delete OTA file from Settings - Storage if present and reboot before attempting the jailbreak to prevent a possible bootloop
This versions contains full-fledged Cydia and Substrate support for iOS 12 on compatible devices that are listed above. This means that Cydia and Tweaks are fully functional
Some repos may not function with Cydia/APT yet due to a bug in Apple's code on iOS 12 (See https://twitter.com/sbingner/status/1099050396557893632)
This is considered to be safe to try as long as you make sure you have no downloaded OTA file
It is still possible to restore or downgrade your device to iOS 12.1.1~b3 to use this jailbreak even if you are on iOS 12.1.3 or up (See https://twitter.com/Pwn20wnd/status/1093191940831567872)
Reboot and re-attempt the jailbreak if it gets stuck at "Extracting Cydia..."

02/22/2019 - v3.0.0~b30 was released for public testing with the following changes:

Update libapt in bundled packages
Change how ldrestart is called to something that supposedly makes it more reliable

02/23/2019 - v3.0.0~b31 was released for public testing with the following changes:

Attempt to make renaming the system snapshot safer by improving assertion

02/23/2019 - v3.0.0~b33 was released for public testing with the following changes:

Bundle LetMeBlock by @PoomSmart to make blocking revokes via adding entries to hosts file work on iOS 12
Bundle NoBetaAlert by @parrotgeek1 to hide the iOS beta expiry alert
Attempt to fix a stability issue in reloading system daemons

02/24/2019 - v3.0.0~b33 was released for public testing with the following changes:

Attempt to fix a stability issue with reloading system daemons that was known for causing the device to get stuck with a spinning wheel and eventually rebooting itself (Note: If you still experience this issue, you should use the RootFS Restore feature and re-attempt the jailbreak again before filing a new issue)
Fix a bug in loading tweaks without reloading system daemons
Fix a bug in assertion
Important Notes:
It is highly recommended to turn on the Airplane Mode before attempting the jailbreak

02/25/2019 - v3.0.0~b34 was released for public testing with the following changes:

Fix the root cause of the "Reload System Daemons" failures on iOS 12
Add an apt lists cache file to ease load on repositories

02/26/2019 - v3.0.0~b36 was released for public testing with the following changes:

Double version number bump to prevent possibly confusion caused by a previous mistake regarding the version numbers
Greatly improve the reliability of loading tweaks
Improve the reliability of loading patchfinder64
Update the APT lists cache file for repositories
Important Notes:
The incompatible versions of the "Apple File Conduit "2" (arm64/KPPLess)" package have been found to cause the jailbreak to fail to load tweaks. - If you are having this issue, please jailbreak without enabling tweaks, update or uninstall this package and re-jailbreak
Many extensions are known to cause issues with the iOS 12 due to the lack of proper iOS 12 compatibility. - Please be careful with what you install
It is highly recommended to turn on the Airplane Mode before attempting the jailbreak

02/27/2019 - v3.0.0~b37 was released for public testing with the following changes:

Enable partial 4K (A7/A8) support on iOS 12 to allow setting a nonce and disabling auto updates
Update the APT lists cache file for repositories

02/28/2019 - v3.0.0~b38 was released for public testing with the following changes:

Fix the v1ntex exploit
Fix a theoretical bug in determining the device support status
Fix a theoretical bug in the UI
Update the APT lists cache file for repositories

03/03/2019 - v3.0.0~b39 was released for public testing with the following changes:

Make it install NoBetaAlert only if the device is running a beta firmware and remove if it is not
Make it install LetMeBlock only if the device is running iOS 12.0 or higher and remove if it is not
Improve the nvram patch to increase the performance of the jailbreak
Add more code for debugging possible issues
Fix Clear Diagnostics Data
Fix a kernel memory leak
Update the offsets cache to not cache an unused offset
Dump the nvram variables list
Fix jailbreaking after a unsuccessful bootstrap extraction
Reload mDNSResponder before backboardd when loading tweaks without enabling Reload System Daemons
Update the APT lists cache file for repositories
Update the local APT repo
