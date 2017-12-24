TWRP Device 
Device:TCL ono/TCL_P620M
Codename:Escape_CM
CPU:MT6735


##How to compile:

1. Get the latest Lineageos14.1 sources and twrp sources
2. rm -r system/sepolicy 
3. git clone http://github.com/rote66/android_system_sepolicy.git -b los-14.1-ono system/sepolicy
4. ./build/envsetup.sh
5. lunch lineage_Escape_CM-userdebug
6. make -jX (where X is the # of your CPU threads +1) recoveryimage

By wyk
