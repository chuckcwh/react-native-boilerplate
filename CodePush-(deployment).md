**CodePush** is the library to help the deployment for the mobile app. 
If the developer uses store release, the update will not be effective right away.
For those hotfixes or simple feature changes, this could be deployed by using **CodePush**.

## How it works

**CodePush** provides the wrapper for the **javascript bundle**. **CodePush** will communicate with the server, and see if there is an update available. The developer can set the policy for updating the js bundle. Please check the links from the bottom.

## Install the code-push cli 

```bash
npm install -g code-push-cli
```

## Custom scripts

Please check the codepush script from script/codepush*.js
This script does several steps;

1. check branch
2. check env from config/env.json
3. check platform
4. deploy by using codepush 
5. add tag

```bash
# Run the script
node scripts/codepush.js --platform ios

# or 
yarn codepush-ios:staging
yarn codepush-ios:uat
yarn codepush-ios:production
yarn codepush-android:staging
yarn codepush-android:uat
yarn codepush-android:production
```

# Useful Commands

```
code-push login
code-push whoami
code-push logout
code-push app list
code-push deployment ls <appName> [--displayKeys|-k]
```

## Create an app 

1. Go to https://appcenter.ms
2. Create an **Organization**
3. Create **App** under the **organization** that created from step 2 (ios, android) 
4. From left menu, go to **Distribute-CodePush**.
5. Generate **environments** (**Production**, **Staging**, **Uat**)
4. Copy the deployment key, and save in the **config/codepush.js**

## Related Links

1. https://appcenter.ms
2. https://github.com/Microsoft/react-native-code-push
3. https://github.com/Microsoft/code-push/tree/master/cli

