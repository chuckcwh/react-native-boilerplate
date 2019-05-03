Fastlane is the tool provides automation for the mobile build.
Fastlane can deploy the app to [Fabric - Beta](https://www.fabric.io/home), Playstore, iTunesConnect. 

Fastlane has various features; 

1. automated version bump
2. build 
3. deploy to [**playstore**, **beta app**, **itunes connect**]
4. distribute to testers group
5. ...

## Configuration

### iOS 

#### ios/fastlane/Appfile

1. change **bundle name** (ex. com.plus65.boilerplate)
2. change **apple_id** (ex. vincent.rafols@plus65.com.sg)
3. change **itc_team_id** (see below for how to get)
4. change **team_id** (see below for how to get)

#### ios/fastlane/Fastfile

1. change **the username** for getting the certificate (ex. vincent.rafols@plus65.com.sg)

---
### Android

#### android/fastlane/Appfile

1. change package name (ex. com.plus65.boilerplate)
2. get the ``swipe-google-service-account.json``, and replace it under ``./android/app/`` (see below for how to get)

#### android/fastlane/Fastfile

1. change **api_token**
2. change **build_secret**

---
## Customized script

For the script, please refer ``ios/fastlane/Fastfile``, ``android/fastlane/Fastfile``.

1. checking the branch
2. checking the env
3. auto-increment version number
4. build
5. deploy
6. add tag

## Related Links

1. https://fastlane.tools/
2. https://docs.fastlane.tools/
3. https://www.fabric.io/home

## Additional Information 

### itc_team_id, team_id

* team_id can be found https://developer.apple.com/account/#/membership
* itc_team_id can be found ``todo``

### swipe-google-service-account.json 

This file can be generated from https://play.google.com/apps/.

1.go to API acccess
2. create service account
3. download json 
4. place under ``android/app/{name}.json``