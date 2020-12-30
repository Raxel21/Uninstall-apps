# Uninstall pre-installed apps

1. Activate the debugging
2. Install [USB DRIVER](https://developers.android.com/studio/run/oem-usb.html)

## Terminal Commands
```shell
adb shell
pm list packages
pm uninstall -k --user 0 package name

