# Clean your bloated device without root!

## Requirement

- `ADB`
> yay -S android-sdk android-tools
- `Android Mobile`

## Steps

Connect device with `adb` and test with:
```bash
adb decives
```
Run 
```bash
adb shell pm list packages > pkglist
```
