# E-Droid

Based on Foxy-Droid

https://github.com/kitsunyan/foxy-droid

[![Release](https://img.shields.io/github/v/release/kitsunyan/foxy-droid)](https://github.com/kitsunyan/foxy-droid/releases)
[![F-Droid](https://img.shields.io/f-droid/v/nya.kitsunyan.foxydroid)](https://f-droid.org/packages/nya.kitsunyan.foxydroid/)

## 🗒️ Planned Features

A way to scan a app from any repo using ClamAV
More customization options
## Description

## Credits

Foxy Droid
https://github.com/kitsunyan/foxy-droid

Machiav3lli's fork 
https://github.com/machiav3lli/foxy-droid

### Screenshots

## Building and Installing

Specify your Android SDK path either using the `ANDROID_HOME` environment variable, or by filling out the `sdk.dir`
property in `local.properties`.

Signing can be done automatically using `keystore.properties` as follows:

```properties
store.file=/path/to/keystore
store.password=key-store-password
key.alias=key-alias
key.password=key-password
```

Run `./gradlew assembleRelease` to build the package, which can be installed using the Android package manager.

## License

E Droid is available under the terms of the GNU General Public License v3 or later. Copyright © 2020 kitsunyan.
