# Get started Flutter

[![macOS](https://img.shields.io/badge/macOS-Catalina-black)](https://developer.apple.com/macos/)

https://flutter.dev/

## Running environment
If you don't have the Android device, need to set up the following tools.

* [ ] Xcode: use iOS Simulator
* [ ] Android Studio: use Android Emulator

### Issues
* [idevice_id cannot run on catalina](https://github.com/flutter/flutter/issues/42302)

## Tutorials

* [Write your first Flutter app, part 1](https://flutter.dev/docs/get-started/codelab)
* [Write your first Flutter app, part 2](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt2/index.html?index=..%2F..index#0)
* [Building Layouts](https://flutter.dev/docs/development/ui/layout/tutorial)
* [Animations tutorial](https://flutter.dev/docs/development/ui/animations/tutorial)
* [An introduction to unit testing](https://flutter.dev/docs/cookbook/testing/unit/introduction)
* [Mock dependencies using Mockito](https://flutter.dev/docs/cookbook/testing/unit/mocking)
* [An introduction to widget testing](https://flutter.dev/docs/cookbook/testing/widget/introduction)
* [Adding Google Maps to a Flutter App](https://codelabs.developers.google.com/codelabs/google-maps-in-flutter/index.html?index=..%2F..index#0)

:arrow_upper_right: [Next steps](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt2/#8)

## Tips
### flutter doctor
If you have any troubles, share the following command log.

```
$ flutter doctor -v
```

### flutter dev
If you try the developing Flutter.

```
$ flutter channel dev
$ flutter upgrade
```

### flutter package name
If you create with setting default package name.

```
$ flutter create --org com.yourdomain appname
```
