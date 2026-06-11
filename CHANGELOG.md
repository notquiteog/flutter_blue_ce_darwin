## 2.3.8+ce.1
* Rename the forked package to `flutter_blue_ce_darwin`.
* Preserve unspecified `setOptions` values and support concurrent service discovery per peripheral.
* Improve service/characteristic resolution when duplicate service UUIDs are present.
* Preserve the first CoreBluetooth discovery error until the final discovery result is emitted.

## 4.0.1
* fix unrecognized selector sent to instance (regression from 4.0.0)

## 4.0.0
* Use bytes instead of hex for platform communication (#1130)

## 3.0.0
* Update platform interface version to 3.0.0

## 2.0.1
* Add log color

## 2.0.0
* Combine the packages previously published as flutter_blue_ce_ios and flutter_blue_ce_macos
* Add support for Swift Package Manager
* Replace void return types with bool return types
