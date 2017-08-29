# RMC-300 Raspberry Pi yocto  

1. image.bb for build Raspberry with Qt5, GStreamer1.0 support 
2. patch for OpenMAX IL support 
3. patch for fix Qt5 Raspberry Pi2 support


# How to build
1. clone https://github.com/Rock1965/rmc-300-yocto.git
2. cd rmc-300-yocto
3. git submodule init
4. git submodule update
5. yocto-base/poky-fido/oe-init-build-env build-rpi2 (build-rpi)
6. bitbake kongja-rpi-qt5-image
