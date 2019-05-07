## Introduction

Firebase setup is required for the app to get some of the mobile features.
For the official document, refer to [react-native firebase initial setup](https://rnfirebase.io/docs/v5.x.x/installation/initial-setup)

1. Push Notification 
2. Analytics
3. Crashlytics
4. Database 
5. ...

## Create a project

1. Go to https://console.firebase.google.com
2. Login with ``root account``
3. Create a Project
4. Add Developer & Permission by clicking the gear on the left panel

### Create Project

![Screenshot_2019-04-29_at_2.05.51_PM](uploads/74ab41bb44d62282e87ff4552f17cde8/Screenshot_2019-04-29_at_2.05.51_PM.png)

### Add Developer & Permission

![Screenshot_2019-04-29_at_2.06.29_PM](uploads/2ece0cbf61ac7342281e924314bd3757/Screenshot_2019-04-29_at_2.06.29_PM.png)

![Screenshot_2019-04-29_at_2.06.40_PM](uploads/35a567084b860feaa72b9f35cc5ec938/Screenshot_2019-04-29_at_2.06.40_PM.png)


## Android Setup

1. Click on the gear on the left panel
2. Click on the Project Settings
3. Drag to below on the general tab.
4. Click on Add App
5. Click Android
6. **Input package name**
7. Download **google-services.json**
8. Place under **./android/google-services.json**

![Screenshot_2019-04-29_at_2.07.46_PM](uploads/f9ec028dad2cf5623ec9a91cbdfd4012/Screenshot_2019-04-29_at_2.07.46_PM.png)

![Screenshot_2019-04-29_at_2.07.54_PM](uploads/1905c17076712fc435f6159cc52a7cca/Screenshot_2019-04-29_at_2.07.54_PM.png)

![Screenshot_2019-04-29_at_2.08.09_PM](uploads/bc08d0bd7573746cb57771678bacdb27/Screenshot_2019-04-29_at_2.08.09_PM.png)

## iOS Setup

1. Click on the gear on the left panel
2. Click on the Project Settings
3. Drag to below on the general tab.
4. Click on Add App
5. Click iOS
6. **Input Bundle ID**
7. Download **GoogleService-Info.plist**
8. Place under **./ios/{nameoftheapp}/GoogleService-Info.plist**

## React Native Setup

`` TODO ``