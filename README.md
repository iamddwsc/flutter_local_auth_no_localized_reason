# reason of modification: This is a fork of the original package
# local_auth_android
I modified the original package to remove the need to use localizedReason, it makes the biometric prompt display localized text based on the device's language.

[![pub package](https://img.shields.io/pub/v/local_auth_android.svg)](https://pub.dev/packages/local_auth_android)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# local\_auth\_android

The Android implementation of [`local_auth`][1].

## Usage

This package is [endorsed][2], which means you can simply use `local_auth`
normally. This package will be automatically included in your app when you do,
so you do not need to add it to your `pubspec.yaml`.

However, if you `import` this package to use any of its APIs directly, you
should add it to your `pubspec.yaml` as usual.

[1]: https://pub.dev/packages/local_auth
[2]: https://flutter.dev/to/endorsed-federated-plugin
