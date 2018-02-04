TWRP Device repository for TCL_P620M (Lineageos)
===========================

For Stock 3.10.65 kernel

Codename:Escape_CM

CPU:MT6735

---------------
##How to compile:

1. Get the latest Lineageos14.1 sources and twrp sources
2. clone this device 
3. cd device/TCL/Escape_CM 
4. patches/apply-patches.sh
5. ./build/envsetup.sh
5. lunch lineage_Escape_CM-userdebug
6. make -jX (where X is the # of your CPU threads +1) recoveryimage

By wyk
