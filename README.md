# StegaImg

Image Steganography built using Flutter and Dart.

Support for Android and IOS only for now. Tested on Android & IOS.

## Android

### Installation

Go to my [Releases page](https://github.com/SathvikTn/StegaImg/releases) and download & install the latest version.

### Usage



## IOS

### Installation

Note: You need a system running mac os and Xcode and flutter installed in it.

To install Xcode (only in macos): 
- Download the latest version from [Apple developer website](https://developer.apple.com/download/all/?q=Xcode) (Preferred) 
or
- Download it from App Store directly.

To install Flutter in macos: 
- Follow steps provided in [Flutter macos doc](https://docs.flutter.dev/get-started/install/macos).

Step 1: Clone this repo to your mac.

Step 2: In Xcode, open Runner.xcworkspace present in StegaImg/stegaimg/ios folder. More info on [Flutter dev doc](https://docs.flutter.dev/deployment/ios#review-xcode-project-settings)

Step 3: Connect your iphone or ipad to the mac system.

Step 4: In Xcode, Select scheme and make sure your device is visible and selected.

Step 5: In Xcode, head over to Product – Scheme – Edit Scheme. Select "Run" from left menu bar and Under "Info", set "Build Configuration" from Debug to Release and uncheck "Debug executable" and finally press the play button to run the app. More on [this](https://pinkstone.co.uk/deploying-your-app-from-xcode-to-a-device-with-release-build-configuration/).

Step 6: Make sure to allow permissions to install. You will encounter an error states "Untrusted Developer, Your device management settings does not allow using an app from ME on this iPhone. You can allow using these apps in Settings". To resolve this, (for iOS 15.2) Settings > General > VPN & Device Management > select the profile to trust. More on [this](https://developer.apple.com/forums/thread/660288).

Step 7: Try to re-run the app again from Xcode and Done.

### Usage



## Reference

- [Photochat](https://github.com/tianhaoz95/photochat)

- [IOS Deployment](https://docs.flutter.dev/deployment/ios)

- More about [running app](https://developer.apple.com/documentation/xcode/running-your-app-in-the-simulator-or-on-a-device) and [schemes](https://help.apple.com/xcode/mac/current/#/dev0bee46f46)

