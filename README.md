# Ruk-A-Tuk iOS & Android App

[![App Store](https://linkmaker.itunes.apple.com/htmlResources/assets/en_us//images/web/linkmaker/badge_appstore-lrg.svg)][appstore]
[![Google Play](https://play.google.com/intl/en_gb/badges/images/badge_new.png)][googleplay]

[appstore]: https://itunes.apple.com/us/app/ruk-a-tuk/id1273614449?ls=1&mt=8
[googleplay]: https://play.google.com/store/apps/details?id=com.rukatuk.app&hl=en_GB

The official iOS and Android mobile App for Ruk-A-Tuk Promotions.

![screenshots](https://user-images.githubusercontent.com/510174/29857420-7f34880c-8d50-11e7-8baa-feb5659534d5.png)

## Requirements
- [Node](https://nodejs.org) `4.x` or newer
- [React Native](http://facebook.github.io/react-native/docs/getting-started.html) for development
- [Android Studio](https://developer.android.com/studio/index.html) for Android development
- [Xcode](https://developer.apple.com/xcode/) for iOS development
- [Android SDK](https://developer.android.com/sdk/) `23.0.1` or newer for Android development
- [Genymotion](https://www.genymotion.com/) for Android emulation
- [YARN](https://yarnpkg.com/) - for dependency management

## Installation

Clone this repo

```sh
$ git clone git@github.com:akilb/rukatuk-mobile.git
$ cd rukatuk-mobile
$ yarn install or npm install
```

Create a `.env` file and add the following:

```
GOOGLE_MAPS_API_KEY=ENTER_GOOGLE_MAPS_API_KEY
```

[firebase]: https://firebase.google.com/
[firebase-ios-setup]: https://firebase.google.com/docs/ios/setup#add_firebase_to_your_app
[firebase-android-setup]: https://firebase.google.com/docs/android/setup#manually_add_firebase

This application uses [Firebase][firebase] for analytics, crash reporting and push notifications. You can use your own firebase account when running the app.

- *[iOS]* Follow the add firebase to your app instructions [here][firebase-ios-setup] to generate your GoogleService-Info.plist file if you haven't done so already. Place this file in the ios/Rukatuk directory.
- *[Android]* Follow the manually add firebase to your app instructions [here][firebase-android-setup] to generate your google-services.json file if you haven't done so already. Place this file in the android/app/ directory

## How to start

```sh
$ react-native run-android
$ react-native run-ios
```
