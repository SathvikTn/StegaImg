# StegaImg

Image Steganography built using Flutter and Dart.

Tested and Support for Android and IOS only for now. 

Website is at [here](https://sathviktn.github.io/StegaImg/).

## Table of Contents

- [Android](#android)
  - [Installation](#installation)
  - [Usage](#usage)

- [IOS](#ios)
  - [Installation](#installation-1)
  - [Usage](#usage-1)

- [References](#references)

## Android

### Installation

Go to my [Releases page](https://github.com/SathvikTn/StegaImg/releases) and download & install the latest version.

### Usage

#### 1. Encode

https://user-images.githubusercontent.com/43294216/177149812-dc89bf45-1153-4606-a232-8ca8638a536d.mp4

#### 2. Decode

https://user-images.githubusercontent.com/43294216/177149884-76e922fb-8589-44a4-b59a-2620d42a1dfd.mp4

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

#### 1. Permissions

https://user-images.githubusercontent.com/43294216/176703937-f03b576d-03f7-4856-a603-8985ccf3325f.mp4

#### 2. Encode

https://user-images.githubusercontent.com/43294216/176704125-52b69830-720c-4098-aa60-059e81a02ef2.mp4

#### 3. Decode

https://user-images.githubusercontent.com/43294216/176704260-d14b4cf6-a775-4924-b1e6-dad63b52bdfb.mp4

## References

- [Photochat](https://github.com/tianhaoz95/photochat)

- [IOS Deployment](https://docs.flutter.dev/deployment/ios)

- More about [running app](https://developer.apple.com/documentation/xcode/running-your-app-in-the-simulator-or-on-a-device) and [schemes](https://help.apple.com/xcode/mac/current/#/dev0bee46f46)

