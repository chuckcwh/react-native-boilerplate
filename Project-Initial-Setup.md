## 1. Change the name & package name of the Project

```bash
# change the app name & package name
# script does below steps
# 1. change the name of the app by using grep & sed
# 2. rename the file for ios/android by using find & mv
# 3. rename package name by using grep & sed 
node scripts/initialize/index.js NewAppName com.plus65.NewAppName

# install libraries
yarn install 
cd ios && pod install # cocoapods should be installed 

# run the app on ios
yarn ios
```

Please refer to this link for installing cocoapods [iOS - Initialize CocoaPods](iOS-Initialize-CocoaPods).


## 2. Firebase Setup

[Firebase](Firebase)

## 3. iOS Setup

[iOS](iOS)

## 4. Android Setup

[Android](Android)

## 5. CodePush Setup

[CodePush](CodePush-(deployment))

## 6. Fastlane

[Fastlane](Fastlane-(deployment))

## 7. Change App Icon, Splash screen

1. Change the splash image from the src/images/splash.png
2. Change the Splash Image from android/app/src/main/res/mipmap-xxx/launch_screen.png
3. Change App Icon Image  from android/app/src/main/res/mipmap-xxx/ic_launcher.png
4. Change Splash Image from ios/boilerplate/Base.Iproj/LaunchScreen.xib

## 8. Extra

* Mapbox 
* Force Update (TODO)

