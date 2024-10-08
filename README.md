![image alt](https://github.com/Playcpa/Dousuo/blob/ee3f0bae3d652b2b4fb557de2cfa39721b5de61e/IMG_20240811_201721_472.jpg)

# Dousu emulator
`Dousuo` is a script to install preconfigured rootfs with Box86, Box64, Wine and DXVK installed. It allows you to run x86 and x86_64 windows programs (such as games) on Android using Termux.

`Dousuo` is not mobox and box64droid .

Installation
After installation the start command in termux is Dousuo 

```bash
not now 
```


# Configuration
After installing Dousuo some settings and variables can be changed in Dousuo/preferences menu. To install Vulkan/OpenGL drivers you should start Wine and select Mesa and D3D libs in Start Menu -
> Install. To change or add environment variables edit config saved in /sdcard/Dousuo


# Device support all 
>Android

>Android 10+ __no root 

>Android 11+ __root

>Android 12+ __root



`Snapdragon` with Adreno 6xx or Adreno 7xx — 
Turnip + Zink / Turnip + DXVK with better speed.
Qualcomm/Mediatek/Exynos/Mali — VirGL


`Dousuo` has automatic updates, so you don't have to reinstall it so often.
TFM works a lot faster with custom wine.
The most lightweight rootfs.
Proot which is faster than proot-distro.
Chroot with working VirGL for root users
VirGL server with dxtn support (termux virgl doesn't have this). Mesa-VirGL 
18.3.0, 19.1.8, 22.1.7.

Turnip with adreno 610 and 7xx support. Mesa-zink-11.06.22 built from alexvorxx repo which is faster and has better compatibility. D8VK + DXVK + VKD3D and 
WineD3D.

Prefix-tweaks script that automatically installs DirectX, 7-Zip, various registry fixes, better taskmgr and notepad. Custom theme, better fonts which give a lot better look compared to default wine prefix. Better icons. E:\ (Android/data/com.termux/files/Download folder) for faster performance without having to copy games to C:\ drive
Experimental wine-tweaks script that automatically installs downloaded wine, customizes it for better TFM speed and reduces size


## Third party applications

[Box64](https://github.com/ptitSeb/box64) 

[Box86](https://github.com/ptitSeb/box86) 

[Proot](https://github.com/termux/proot) 

[DXVK](https://github.com/doitsujin/dxvk) 

[DXVK-ASYNC](https://github.com/Sporif/dxvk-async)

[DXVK-GPLASYNC](https://gitlab.com/Ph42oN/dxvk-gplasync)

[VKD3D](https://github.com/lutris/vkd3d) 

[D8VK](https://github.com/AlpyneDreams/d8vk) 

[Termux-app](https://github.com/termux/termux-app) 

[Termux-x11](https://github.com/termux/termux-x11) 

[Wine](https://wiki.winehq.org/Licensing)

[Mesa](https://docs.mesa3d.org/license.html) 

[mesa-zink-11.06.22](https://github.com/alexvorxx/mesa-zink-11.06.22)
