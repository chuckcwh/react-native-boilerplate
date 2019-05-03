CodePush is the library to help the deployment for the mobile app. 
If the developer uses store release, the update will not be effective right away.
For those hotfixes or simple feature changes, this could be deployed by using CodePush.

## How it works

CodePush provides the wrapper for the **javascript bundle**. CodePush will communicate with the server, and see if there is an update available. The developer can set the policy for updating the js bundle. Please check the links from the bottom.

## Install the code-push cli 

```bash
npm install -g code-push-cli
```

## Create an app 

1. Go to https://appcenter.ms
2. Create App (ios, android) 
- should create different projects for each platform
3. Copy the deployment key

## Custom setting

Create 3 different environments for each staging, uat, production.
3 different keys will be generated and **these keys should be saved under config/codepush.js**


## Related Links

1. https://appcenter.ms
2. https://github.com/Microsoft/react-native-code-push
3. https://github.com/Microsoft/code-push/tree/master/cli

