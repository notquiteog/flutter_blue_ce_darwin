# flutter_blue_ce_darwin

The iOS and macOS implementation of [`flutter_blue_ce`][1].

## Usage

This package is [endorsed][2], which means you can simply use `flutter_blue_ce`
normally. This package will be automatically included in your app when you do,
so you do not need to add it to your `pubspec.yaml`.

However, if you `import` this package to use any of its APIs directly, you
should add it to your `pubspec.yaml` as usual.

```yaml
dependencies:
  flutter_blue_ce_darwin:
    git:
      url: https://github.com/notquiteog/flutter_blue_ce_darwin.git
      ref: main
```

## Swift Package Manager

https://docs.flutter.dev/packages-and-plugins/swift-package-manager/for-app-developers

Disable Swift Package Manager in your project

```
flutter:
  disable-swift-package-manager: true
```

[1]: https://github.com/notquiteog/flutter_blue_ce
[2]: https://flutter.dev/to/endorsed-federated-plugin
