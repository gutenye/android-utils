Android-Utils, a collection of utils for android
================================================

| Homepage:      |  https://github.com/GutenYe/android-utils       |
|----------------|------------------------------------------------------       |
| Author:	       | Guten                                                 |
| License:       | MIT-LICENL                                                |
| Documentation: | http://rubydoc.info/gems/android-utils/frames                |
| Issue Tracker: | https://github.com/GutenYe/android-utils/issues |

Overview
--------

It contains rsync, ssh, curl, openvpn ..., [a list of binaries](https://github.com/GutenYe/android-utils/tree/master/bin)

Most binaries come from CyanogenMod.

INSTALL
--------

Manual

	$ adb push bin/vim /data/local/tmp/vim

	# enter adb shell with root
	$ mv /data/local/tmp/vim /system/xbin

Auto Install

	# need `adb shell` returns root. like in VallianROM ..
	# cd source directory and run ./install

Contributing
-------------

* Feel free to join the project and make contributions (by submitting a pull request)
* Submit any bugs/features/ideas to issue tracker

Credits
--------

This project is only possible because of the work of [many fine developers from around the world]((https://github.com/GutenYe/android-utils/contributors).

Resources
---------

* busybox https://github.com/dylex/android_external_busybox

* vim libncurses.so https://github.com/sileht/android_external_vim

* bash https://github.com/cvpcs/android_external_bash

* sqlite https://github.com/CyanogenMod/android_external_sqlite

* wget https://github.com/jsha/android-wget

* curl https://github.com/jahrome/curl-android

* openvpn liblzo.so https://github.com/fries/android-external-openvpn

* ssh https://github.com/CyanogenMod/android_external_dropbear

* netcat https://github.com/android/platform_external_netcat

* rsync https://github.com/dylex/android_external_rsync

Copyright
---------

(the MIT License)

Copyright (c) 2011 Guten

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
