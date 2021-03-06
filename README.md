# Hackintosh for Thinkpad X1 Extreme
> This hackintosh you guys made, excited!  ——— Zemin Jiang, the man who changed China.
### Developer: [@Errrneist](https://www.tonymacx86.com/members/errrneist.1550861/)
### *Current Clover Version: 4772*
### *Current macOS Version: 10.14.0*
#### Don't forget to star this project if you like it!



## Instructions
##### Pre-Install
* *FORK* the project to your own repository and clone it to your machine using Github Desktop to make changes.
* For windows drivers, here is the [Driver for BRCM943602BAED](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602BAED.1) to get DW1830 working. Also, here is [Driver for BRCM943602CS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1) if you try to use an [adapter](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/blob/master/IMG/BCMAdapter.jpg) to install the native card used on macbook. These cards are not natively supported by Microsoft so download it before you swap out your wireless card.
##### Clover Bootloader
* If you want to download the EFI Clover Bootloader, you can check out the [Configuration Release](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases).
* Or, if you are interested in the theme I used, check it out over here: [Minimalism](https://github.com/Errrneist/Hackintosh-Theme-Minimalism).
* I recommend users to use [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/) to configure your config.plist to eliminate typos.
* If you cannot mount EFI via Clover Configurator, then here is a *[Guide for mounting EFI using TERMINAL](https://github.com/Errrneist/Hackintosh-Aero-15W/blob/master/Mount%20EFI%20on%20macOS.MD).*
##### Post-Install 
* If you want to see system specs, check out [System Report](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/Hardware).
* Some might also experience [Time sync issues](https://www.tonymacx86.com/threads/fix-incorrect-time-in-windows-osx-dual-boot.133719/) between Windows and macOS. Here is a [Fix](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/timesync-v1.0) credit to [SwampFox82](https://www.tonymacx86.com/threads/fix-incorrect-time-in-windows-osx-dual-boot.133719/).
##### Discussions and News
* Here is another helpful alternative Thinkpad X1 Extreme Clover EFI configuration repository by [zysuper](https://github.com/zysuper/Thinkpad-X1-extreme-EFI). Please check out his work as well as some some issues are addressed in both of our repositories. Star his work as well!
* Bluetooth is not working. A lot of further work needs to be done here. [Intel is embedding BT chips into PCH which does not work in macOS.](https://www.guru3d.com/news-story/intel-makes-wireless-ac-9560-a-bit-more-embedded.html) We also have a long discussion in the issues so check it out if you are interested in this issue. Link below in the Pinned Discussions.
* [Apple won't work with NVIDIA to release graphics card driver for 10.14](https://www.macrumors.com/2018/11/01/nvidia-comment-on-macos-mojave-drivers/). Currently, there is nothing we can do.
* Recently, people on TonyMacX86 are having issue with PM981. PM981 is troublesome for Hackintosh and I am not using it for install. I'm using a Toshiba XG3. However, you can check out [zysuper's repo readme.MD](https://github.com/zysuper/Thinkpad-X1-extreme-EFI/blob/master/readme.md) on ACPI files to make PM981 working.

## Pinned Discussions
* [Main Post on TonyMacX86](https://www.tonymacx86.com/threads/macos-10-14-0-thinkpad-x1-extreme-hackintosh.263916/)
* [Bluetooth Issues with BCM94360 Devices](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3) 
* [Trackpad not working with Clover-booted Windows](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/5)

## Update
##### Recent
* [20190120] Released [v10.14.0.2](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.0.2) according to andyy24 in [Issue#9](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/9) to fix a trackpoint issue.
* [20190111] Got BCM943602CS working. Turned out I didn't stuck it in enough.
* ~~[20190105] I still cannot get BCM943602CS on adaptor working...~~
* [20181225] Happy holiday humans.
* [20181222] I ordered ribbon cable for smartcard slot in China. Will need to design a PCB tho...
* [20181207] My laptop is dead due to I was stupid enough to tear it down without unplug the battery.
* [20181121] Added [Driver for BRCM943602CS in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1).
* [20181120] Added [Driver for DW1830 in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602BAED.1) Also had some [Discussion on getting bluetooth working](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3).

##### Archive
* For earlier update logs, see [Past Update History Archive](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/Updates).

## Specifications
* [Hardware Specifications](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/Hardware)

### Cheers, Errrneist.


