# lnav-logcat-Android
logcat file description for lnav

For more information, there's a [post](http://javierhz.blogspot.tw/2016/10/debugging-android-logcat-in-macosx-with.html) on www.javierhz.com about this tool and configuration file.

##  Installation
Just copy the .json file into your `~/.lnav/formats/installed folder`

Alternatively, use `lnav -i android-logcat.json` (see: [Installing Formats](https://lnav.readthedocs.io/en/latest/formats.html#installing-formats))

## Usage
`adb logcat -v threadtime | lnav -q`
