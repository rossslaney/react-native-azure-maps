# Contributing

Contributions are always welcome, no matter how large or small!

## Development workflow

The [example app](/example/) demonstrates usage of the library. You need to run it to test any changes you make.

It is configured to use the local version of the library, so any changes you make to the library's source code will be reflected in the example app. Changes to the library's JavaScript code will be reflected in the example app without a rebuild, but native code changes will require a rebuild of the example app.

If you want to use Android Studio or XCode to edit the native code, you can open the `example/android` or `example/ios` directories respectively in those editors. To edit the Objective-C or Swift files, open `example/ios/AzureMapsExample.xcworkspace` in XCode and find the source files at `Pods > Development Pods > react-native-azure-maps`.

To edit the Java or Kotlin files, open `example/android` in Android studio and find the source files at `react-native-azure-maps` under `Android`.
