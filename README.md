[Android Ice Cold Project](http://aicp-rom.com) on x86 (AICP-x86)
-----------------------------------------------------------------


Download the AICP-x86 source code, based on Android-x86--Cyanogen-x86 and AICP
------------------------------------------------------------------------------

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Repo initialization:

    $ repo init -u https://github.com/AICP-x86/manifest.git -b mm6.0


sync repo :

    $ repo sync --no-tags --no-clone-bundle

***

Building
--------

After the sync is finished, please read the [Building the image instructions from the Android-x86 site](http://www.android-x86.org/getsourcecode) on how to build.

   $ . build/envsetup.sh && lunch android_x86-eng

   $ make iso_img

Remember to `make clobber` every now and then!

Or
---

[Download the latest build of AICP-x86](https://drive.google.com/open?id=0B73McXwkxx69azg0RUtJWVVvaHM)

[Video](https://drive.google.com/open?id=0B73McXwkxx69azg0RUtJWVVvaHM)

[ScreenShots](https://drive.google.com/open?id=0B73McXwkxx69RmNUZlJya1E2NlU)

[Feedback](https://drive.google.com/open?id=1JgxzRaXV-9gWIwHA3ehppgAA1EfhEJQgAWeQdQktk5A)
