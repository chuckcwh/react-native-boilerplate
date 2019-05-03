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
2. Create an Organization
3. Create App under the organization that created from step 2 (ios, android) 
- should create different projects for each platform
4. From left menu, go to Distribute-Codepush.
5. Generate environment (**Production**, **Staging**, **Uat**)
4. Copy the deployment key, and save in the **config/codepush.js**

## Related Links

1. https://appcenter.ms
2. https://github.com/Microsoft/react-native-code-push
3. https://github.com/Microsoft/code-push/tree/master/cli

