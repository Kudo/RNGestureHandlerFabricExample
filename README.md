# Minimal Reproducible Example

For issue: https://github.com/software-mansion/react-native-gesture-handler/issues/1920

Mostly copy from https://github.com/software-mansion/react-native-gesture-handler/tree/af5920b60be74cb19709e3095ca638e7882a77dc/FabricExample but only update metro.config.js for `inlineRequires: false`.

# React Native Gesture Handler example app with Fabric

## Installing & running application

Before running application you need to install all dependencies. To do that:
- In project's root directory run `yarn install`
- In FabricExample directory run `yarn install`

### Android

To run this application on Android you need to have Java 11 active on your computer. You can check which version you are using by running `javac --version`. You can change it by changing `JAVA_HOME` environment variable or in Android Studio settings.

Then you can run this application by `yarn android` or from Android Studio.

### iOS

To run on iOS first go to `FabricExample/ios` and run `pod install`. This will install pods for Fabric architecture.

Then in `FabricExample` run `yarn ios` or run application from Xcode.
