# android_device_Alps_Fire
Nougat ROMs building tree for Alps Power Plus powered by Stain995
- **AICP 12.1**

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | mt6582 1.3GHz
Kernel  | 3.10.54
GPU     | Mali-400MP
Memory  | 2GB RAM
Shipped Android Version | 5.0
Storage | 16GB
Display | 5.3" 720 x 1280 px
Camera  | 13mp Rear, 5mp front




# Build Commands :-

  * repo init -u https://github.com/Stain995/platform_manifest.git -b n7.1
  * repo sync --no-tags --no-clone-bundle --force-sync -c -j8
  * lunch aicp_Fire-userdebug
  * brunch Fire

#[ Note: all device and vendor tree is included in platform manifest so no need to clone it again and again! ]

# Credits/Thanks to:-

 * tribetmen
 * Stain995
 * SamSanuch
 * a7raj
