## Dashboard 

![Screenshot_2019-04-29_at_2.13.13_PM](uploads/69d0b2ddf41f2e6004204ad6879ad096/Screenshot_2019-04-29_at_2.13.13_PM.png)

## Certificate

There are several uses of certificates. 

1. Build (development)
2. Build (distribution)
3. Push Notification
4. ...

## How to create certificate

In order to register the certificate to applde developer console, should make csr(certificate sigining request) file first.

1. hit ``open /Applications/Utilities/Keychain\ Access.app``
2. Menu - Keychain Access - Certificate Assistant - Request Certificate from a certificate authority
3. input email address 
4. input common name
5. check on **saved to disk**
6. request certificate from apple 
7. ``Downloaded file should be saved on somewhere, this will be shared with other developers``
---

### Creating a **.certSigningRequest** file from Keychain.app

![Screenshot_2019-04-29_at_2.21.23_PM](uploads/bd31537510b2cf3a6e28a04894f73c66/Screenshot_2019-04-29_at_2.21.23_PM.png)
---

### Request certificate from Apple

![Screenshot_2019-04-29_at_2.25.06_PM](uploads/4a2e114571dd9b80d9d3ff7af546b87d/Screenshot_2019-04-29_at_2.25.06_PM.png)
---

### Download & store the **.cer** file

Double click on the .cer file in order to save public & private key of the certificate on your Keychain.app. After this, you will be able to find the certificate under **My Certificate** tab. 

![Screenshot_2019-04-29_at_2.27.18_PM](uploads/3c6e7a82715367183061c16c3062839b/Screenshot_2019-04-29_at_2.27.18_PM.png)

If you wish to share the file, you could export from Keychain.app, or you can share the initial **.cer** file with other developers. 

---

## Project Identifier

Any project should be registered under **Identifier** tab in order to deploy or build by using XCode. 

![Screenshot_2019-04-29_at_2.29.08_PM](uploads/cdce60291a7e576818f37e3e6de9ea1b/Screenshot_2019-04-29_at_2.29.08_PM.png)

---

## Devices

Any physical devices, you wish to install the app manually, should be registered first on the Apple devices list first. 

Any other testing device can use the app from TestFlight App, which can be downloaded from AppStore, but the app should be deployed to iTunes connect first for the testers to download the app by usingTestFlight App.

![Screenshot_2019-04-29_at_2.29.46_PM](uploads/5a34a97dcd4071073e7d1963b5011eec/Screenshot_2019-04-29_at_2.29.46_PM.png)

---

## Provisioning Profiles

The provisioning profile is being used for the build. Provisioning profile includes the following; 

1. certificate either for production or development. 
2. devices list that allowed for manual installation
3. project bundle id
4. ...

![Screenshot_2019-04-29_at_2.32.35_PM](uploads/f59fe4a9608d446c30d056821674a13b/Screenshot_2019-04-29_at_2.32.35_PM.png)

---