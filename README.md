# droid-vnc-server

VNC server for Android, tested working with h3droid

## Getting started

Make sure Android SDK and NDK are installed

kitkat build:
bash build.sh -a 19



Specify API level with `-a`

Use `-w` flag to build the wrapper libs; AOSP source is required at `../aosp`

Wrapper libs for API 19 to 25 have been prebuilt in [](nativeMethods/libs/armeabi-v7a/) and should work out of the box
