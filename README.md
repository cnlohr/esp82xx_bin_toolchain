# esp82xx_bin_toolchain

This toolchain is intended for use with esp82xx and related projects: github.com/cnlohr/esp82xx

Please untar this file to a `~/esp8266` folder.

```
mkdir -P ~/esp8266
cd ~/esp8266
wget https://github.com/cnlohr/esp82xx_bin_toolchain/raw/master/esp-open-sdk-x86_64-20200810.tar.xz
tar xJvf esp-open-sdk-x86_64-20200810.tar.xz
```

Several esp82xx projects use the offical Espressif nonos SDK instead of the bundled one here. You should probably install that to your home folder using the following commands:

```
cd ~/esp8266
git clone https://github.com/espressif/ESP8266_NONOS_SDK --recurse-submodules
```
