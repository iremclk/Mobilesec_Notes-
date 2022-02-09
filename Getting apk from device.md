# Getting apk from nox
- adb shell pm list packages
- adb shell pm path com.example.someapp
- adb pull /data/app/com.example.someapp-2.apk path/to/desired/destination

## If apk exist on the Download file on your Device
- go Download file and copy the path then:
- adb pull /storage/emulated/0/Download <target path on your computer>	
