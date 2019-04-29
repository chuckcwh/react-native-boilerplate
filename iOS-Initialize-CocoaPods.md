Use CocoaPods for managing the ios dependencies

---

## Installation 

```
sudo gem install cocoapods -v 1.5.3
```

## Version

CocoaPod: 1.5.3

## Initialize CocoaPod Project

```bash
cd ios && pod init 

# after hitting the command above, edit Podfile to remove TvOS setting
vi Podfile

#create Pod project
pod install
```

## How to build

There should be **.xcodeproj** directory should exist when creating a project from react-native-cli. 

After hitting the command of ``pod install``, **.xcworkspace** directory should be created.

Once you create **.xcworkspace**, the build won't work on **.xcodeproj**, and the build should be done from  **.xcworkspace**.

Basically  **.xcworkspace** is the wrapper project containing **Pods** and **.xcodeproj**. 