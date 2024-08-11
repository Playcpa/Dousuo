
>Dousuo is a script to install preconfigured rootfs with Box86, Box64, Wine and DXVK installed. It allows you to run x86 and x86_64 windows programs (such as games) on Android using Termux.

>Dousuo is not mobox and box64droid .

Installation
After installation the start command in termux is Dousuo 



Configuration
After installing Dousuo some settings and variables can be changed in Dousuo/preferences menu. To install Vulkan/OpenGL drivers you should start Wine and select Mesa and D3D libs in Start Menu -> Install. To change or add environment variables edit config saved in /sdcard/Dousuo


>Device support all 
>Android

>Android 10+ __no root 

>Android 11+ __root

>Android 12+ __root

~Render~

Snapdragon with Adreno 6xx or Adreno 7xx — Turnip + Zink / Turnip + DXVK with better speed.
Qualcomm/Mediatek/Exynos/Mali — VirGL

Features
Dousuo has automatic updates, so you don't have to reinstall it so often.
TFM works a lot faster with custom wine.
The most lightweight rootfs.
Proot which is faster than proot-distro.
Chroot with working VirGL for root users
VirGL server with dxtn support (termux virgl doesn't have this). Mesa-VirGL 18.3.0, 19.1.8, 22.1.7.
Turnip with adreno 610 and 7xx support. Mesa-zink-11.06.22 built from alexvorxx repo which is faster and has better compatibility. D8VK + DXVK + VKD3D and WineD3D.
Prefix-tweaks script that automatically installs DirectX, 7-Zip, various registry fixes, better taskmgr and notepad. Custom theme, better fonts which give a lot better look compared to default wine prefix. Better icons. E:\ (Android/data/com.termux/files/Download folder) for faster performance without having to copy games to C:\ drive
Experimental wine-tweaks script that automatically installs downloaded wine, customizes it for better TFM speed and reduces size
Third party applications
~ ~ ~ ~ ~ ~
>Box64 MIT license

>Box86 MIT license
~ ~ ~ ~ ~ ~
>Proot GPL-2.0 license

>DXVK Zlib license
~ ~ ~ ~ ~ ~
>DXVK-ASYNC

>DXVK-GPLASYNC
~ ~ ~ ~ ~ ~
>VKD3D LGPL-2.1 license

>D8VK Zlib license
 ~ ~ ~ ~ ~ ~
>Termux-app GPLv3 license

>Termux-x11 GPL-3.0 license

>Wine-stable 
~ ~ ~ ~ ~ ~
>Mesa MIT license

mesa-zink-11.06.22
