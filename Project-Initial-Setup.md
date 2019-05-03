## 1. Change the name & package name of the Project

```bash
# change the app name & package name
node scripts/initialize/index.js NewAppName com.plus65.NewAppName

# The above script will do the following in sequence.
# 1. change the name of the app by using grep & sed
# 2. rename the file for ios/android by using find & mv
# 3. rename package name by using grep & sed 

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

``todo`` 

## 5. CodePush Setup

[CodePush](CodePush-(deployment))

## 6. Fabric.io - Beta App Setup

``todo`` 

## 7. Extra

* Mapbox
* Codepush Deploy Script
* Fastlane Deploy Script
* Force Update