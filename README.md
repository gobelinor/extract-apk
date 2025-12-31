Simple Bash script to pull APKs from an Android device using ADB.

### Usage 

```
./extract-apk.sh <appname>
```

APKs are saved into:
```
apks_<appname>/
```

### Requirements 
- `adb` installed
- Android device/emulator connected (ADB enabled)

### Notes
- Supports split APKs
- Stops if multiple packages match the given name
