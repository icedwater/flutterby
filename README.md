# Flutterby

Working through a basic Flutter project from the public introductory [codelab][lab].

This generates a combination of two words when a button is clicked.

The first part of the codelab is to [install][inst] some Android SDK which lets you
then proceed on the editor/environment of your choice, even if it is not VS Code.

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

How this project was created:

    flutter create --project-name flutterby --template app flutterby
    cd flutterby

Now the code can be amended in `lib/main.dart` as needed, go wild and learn by
trying stuff. If you haven't changed anything, the default app is a good demo.
Run it and see:

    flutter run -d mobile_xyz

## Other Resources

Other ideas might be found in the [Cookbook][cook] or the rest of the [docs][doc].

[lab]:  https://docs.flutter.dev/get-started/codelab
[inst]: https://docs.flutter.dev/get-started/install
[cook]: https://docs.flutter.dev/cookbook
[doc]: https://docs.flutter.dev/
