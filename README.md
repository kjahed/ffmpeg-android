[FFmpeg-Android](http://hiteshsondhi88.github.io/ffmpeg-android/)
==============

* FFmpeg for Android compiled with x264
* Supports Android L
* [FFmpeg Android Library](https://github.com/hiteshsondhi88/ffmpeg-android-java)

Supported Architecture
----
* armv7
* armv7-neon
* aarch64
* x86
* x86-64

Instructions
----
* Set environment variable
  1. export ANDROID_NDK={Android NDK Base Path}
* Run following commands to compile ffmpeg
  1. sudo apt-get --quiet --yes install build-essential git autoconf libtool pkg-config gperf gettext yasm python-lxml
  2. ./init_update_libs.sh
  3. ./android_build.sh
* To update submodules and libraries you can use ./init_update_libs.sh command
* Find the executable binary in build directory.

License
----
  check files LICENSE.GPLv3 and LICENSE
