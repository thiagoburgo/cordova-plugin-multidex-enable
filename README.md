# Multidex for Cordova

Enable Multidex for Cordova Android apps with over 64K methods.

When your app and the libraries it references exceed 65,536 methods, you encounter a build error that indicates your app has reached the limit of the Android build architecture.

Move past this limitation by enabling an app configuration known as multidex, which allows your app to build and read multiple DEX files.

More information can be found at https://developer.android.com/studio/build/multidex.html

## Installation

```bash
cordova plugin add cordova-plugin-multidex-enable
```

## Supported platforms

* Android
