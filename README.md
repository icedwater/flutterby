# Flutterby

Working through a basic Flutter project from the public introductory [codelab][lab].

This generates a combination of two words when a button is clicked.

We assume that the [install steps][inst] are already done and some Android SDK is
already on the system, since the codelab chooses to go with Android first.

## Architectures

- Linux
- Android

## Creating an Android Emulator

To run on an Android device, you may want to create an emulator first. There is
a barebones version in the Flutter SDK:

    flutter emulators --create --name mobile_xyz

Now that emulator is ready for launch in subsequent runs:

    flutter emulators --launch mobile_xyz

And to run on that emulator:

    flutter run -d mobile_xyz

## Getting Started

Other ideas might be found in the [Cookbook][cook] or the rest of the [docs][doc].

[lab]:  https://docs.flutter.dev/get-started/codelab
[inst]: https://docs.flutter.dev/get-started/install
[cook]: https://docs.flutter.dev/cookbook
[doc]: https://docs.flutter.dev/
