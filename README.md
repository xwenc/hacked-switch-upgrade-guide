# Atmosphere & Firmwares upgrade guide

#### 1. Find DeepSea CFW package and Download the latest release, [[Here]](https://github.com/Team-Neptune/DeepSea)
#### 2. Put DeepSea unzip files on your SD Card, modify ``hekate_ctcaer_x.x.x.bin`` to ``payload.bin``
#### 3. Find Sigmapatches crack patch and Download [[Here]](https://sigmapatches.coomer.party/)
#### 4. Upzip sigmapatches files into SD card root directory.
#### 5. Delete the virtual system serial number: Copy ```atmosphere/config_templates/exosphere.ini``` to the SD card root directory and change ```blank_prodinfo_emummc``` to ```1```
#### 6. Virtual system shields Nintendo servers: Edit ```atmosphere/config/system_settings.ini``` file, Cancel comment before ```enable_dns_mitm = u8!0x1 ```,  Create a new file named ```emummc.txt  ``` on the directory of ```atmosphere/hosts/``` and edit 
				# Block Nintendo Servers
				127.0.0.1 *nintendo.*
				127.0.0.1 *nintendo-europe.com
				127.0.0.1 *nintendoswitch.*
				95.216.149.205 *conntest.nintendowifi.net
				95.216.149.205 *ctest.cdn.nintendo.net
#### 7. Find Switch Firmwares package and Download the latest release, [[Here]](https://darthsternie.net/switch-firmwares/)
#### 8. Put Firmwares unzip files on your SD Card
#### 9, Click Power button and choose CFW (EMUMMC) to open system. Enter ```Photo album ->Daybreak->Install-> Select the firmware directory```，click Next button, Click Reboot button after success
#### 10, Plugins: [Tinfoil](https://tinfoil.io/Download), [Awoo-installer](https://github.com/Huntereb/Awoo-Installer)
#### 11. Reference Url: 
[https://marsshen.com/posts/20e16ead/](https://marsshen.com/posts/20e16ead/)
[https://www.bilibili.com/read/cv19076966?from=search](https://www.bilibili.com/read/cv19076966?from=search)
