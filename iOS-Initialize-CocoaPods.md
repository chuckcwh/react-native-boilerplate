Use CocoaPods for managing the ios dependencies

---

### Installation 
```
sudo gem install cocoapods -v 1.5.3
```

---

### Version
CocoaPod: 1.5.3

--- 

### Initialize CocoaPod Project
```bash
cd ios && pod init 

# after hitting the command above, edit Podfile to remove TvOS setting
vi Podfile

#create Pod project
pod install
```
---

### How to build

There should be **{{nameOfProject}}.xcodeproj** directory should exist when creating a project from react-native-cli. 

After hitting the command of ``pod install``, **{{nameOfProejct}}.xcworkspace** directory should be created.

Once you create **{{nameOfProejct}}.xcworkspace**, the build won't work on **{{nameOfProject}}.xcodeproj**, and the build should be done from  **{{nameOfProejct}}.xcworkspace**.

Basically  **{{nameOfProejct}}.xcworkspace** is the wrapper project containing **Pods** and **{{nameOfProject}}.xcodeproj**. 