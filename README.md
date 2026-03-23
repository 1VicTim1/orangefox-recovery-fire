# OrangeFox Recovery for Xiaomi Redmi 12 (fire)

Unofficial OrangeFox Recovery build for Xiaomi Redmi 12 (`fire`).

## Build

- Base: OrangeFox `12.1`
- Output: `boot.img` for recovery-as-boot devices
- Device: Xiaomi Redmi 12 (`fire`)

## Sources

The device tree used for the successful build is included in:

- `device/xiaomi/fire`

The included tree has the compatibility fix that was needed for the current
OrangeFox branch:

- removed obsolete `FOX_VERSION`
- replaced the hardcoded CI path for `FOX_USE_SPECIFIC_MAGISK_ZIP`

## Release Assets

The GitHub release for this repository contains:

- `OrangeFox-R11.3-Unofficial-fire.img`
- `OrangeFox-R11.3-Unofficial-fire.zip`
- `boot.img`

No `.md5` checksum files are included in the release.
