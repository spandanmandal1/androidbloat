# Clean your bloated device without root!

## Requirement

- ADB
>Depending on your package manager the package name might vary
```bash
yay -S android-sdk android-tools
```
- Android Mobile

## Steps

Connect device with `adb` and test with:
```bash
adb devices
```
Run 
```bash
adb shell pm list packages > pkglist
```
> For modify host file mobile must be rooted
