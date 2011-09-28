Android-Utils, a collection of utils for android
================================================

binaries come from CyanogenMod.

Utils
------

* busybox https://github.com/dylex/android_external_busybox

* vim libncurses.so https://github.com/sileht/android_external_vim

* bash https://github.com/cvpcs/android_external_bash

* sqlite https://github.com/CyanogenMod/android_external_sqlite

* su

* wget https://github.com/jsha/android-wget

* curl https://github.com/jahrome/curl-android

* openvpn liblzo.so https://github.com/fries/android-external-openvpn

* ssh https://github.com/CyanogenMod/android_external_dropbear

* netcat https://github.com/android/platform_external_netcat

* rsync https://github.com/dylex/android_external_rsync

# INSTALL

	$ adb push bin/vim /sdcard/vim
	$ adb push lib/libncurses.so /sdcard/libncuses.so

	# enter adb shell with root
	$ mv /sdcard/vim /system/xbin
	$ mv /sdcard/libncurses.so /system/lib
