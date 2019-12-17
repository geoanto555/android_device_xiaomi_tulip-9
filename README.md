# android_device_xiaomi_tulip
Building TWRP for Xiaomi Redmi Note 6 Pro

Working

ADB

Decryption userdata test miui 11 Global stable 11.0.1.0

Screen brightness settings

Correct screenshot color

MTP


To compile

build/envsetup.sh 

export ALLOW_MISSING_DEPENDENCIES=true 

lunch omni_tulip-eng  

make -jX recoveryimage 
