**Appmobi Secure Mobile Platform**
---------------------
The Appmobi Secure Mobile Platform provides a level of security never seen in a mobile platform, enabling the development of highly secure Cordova-based applications in minutes versus months. This platform provides your development team with configurable, high-performance security options for every app built, including app and device level shared keys for encryption and identity verification as well as integration with most 3rd party authentication systems such as OAUTH, LDAP, and more.

Quickly and easily build the most secure apps on the market today, in minutes.

**Requirements**
--------
In order to utilize the Appmobi platform, you must have a registered Appmobi platform.  
<!---
[Register for FREE](https://cloud.appmobi.com/) for our public cloud to get up and running fast.  We also offer a PrivateStack install where you can isolate the Appmobi backend on your own Amazon Web Service account; [Register for a PrivateStack Demo](https://licensing.appmobi.com/demo/signup/).  Additional AWS charges may apply depending on the configuration of your PrivateStack platform. --->

**Features**
--------
**Security Kit**

Appmobi provides Mobile Application Data Encryption and User Authentication out of the box – securing enterprise mobile applications with 3 levels of security

 - Good: App level shared key encryption
 - Better: App + Device level shared key
 - Best: App + Device Level + Authentication
 
**Secure Push Messages**

pushMobi is a cross platform push messaging service for mobile applications. With a single code base you can send and receive push messages on iOS, Android, Windows8 and Windows8 Phone. Along with the 140 characters of message text, you also have the ability to send a data payload that can be accessed by your app and used to control a behavior or provide additional content.

**Secure Live Update**

liveUpdate allows you to update your app without submitting your changes to the various app stores. liveUpdate does not require that any additional code be added to your app. However, you do have the option to add liveUpdate code to give you more control regarding how and when updates are applied. When you are ready to apply a liveUpdate, you have several options on how your application handles the update.

**Select one of the four behaviours when submitting your liveUpdate**

- Option 1: Automatically Install the Update on Next Restart
- Option 2: Download Update on Restart and Install on following Restart/Resume
- Option 3: Prompt the User and request their permission
- Option 4: Notify the Application

**Secure Data Store**

secureDataStore allows you to save your Application Data securely on device and Sync the same to the appmobiServer and also allows to share data to Application server.

**Secure Analytics**

secure analytics delivers real-time intelligence from a fully scalable, secure private-stack, and is tested for optimal enterprise us, helping developers know what they’re protecting while they’re protecting it.

<!---
**Development Guide**
---------------------

New to mobile development and looking for a place to start? Our Quickstart guide for Development will guide you step-by-step from setting up your development environment, managing services and installing all the necessary components of the Cordova development environment.

**QuickStart Guide for Android Development**
 - [Enabling Google Services](https://docs.appmobi.com/guides/quickstart-android/index.html#enabling-google-services)
 - [Installing the Android SDK & Cordova](https://docs.appmobi.com/guides/quickstart-android/index.html#installing-the-android-sdk-cordova)
 - [Setup your Appmobi App](https://docs.appmobi.com/guides/quickstart-android/index.html#setup-your-privatestack-app)
 - [Creating an App in Android Studio](https://docs.appmobi.com/guides/quickstart-android/index.html#creating-an-app-in-android-studio)

**Quickstart Guide for iOS Development**
-  [Creating a new App in the Mangement Portal](https://docs.appmobi.com/guides/quickstart-ios/index.html#creating-a-new-app-on-private-stack) 
-  [Creating a new iOS App on Cordova using CLI v5.0.0](https://docs.appmobi.com/guides/quickstart-ios/index.html#creating-a-new-ios-app-on-cordova-using-cli-v5-0-0) 
-  [Creating a new iOS App on Apple Developer Site](https://docs.appmobi.com/guides/quickstart-ios/index.html#creating-a-new-ios-app-on-apple-developer-site) 
-  [Generating Push SSL certificate](https://docs.appmobi.com/guides/quickstart-ios/index.html#generating-push-ssl-certificate) 
-  [Generating Provisioning Profiles](https://docs.appmobi.com/guides/quickstart-ios/index.html#generating-provisioning-profiles) 

**Quickstart Guide for OAuth Integration**
 - [Google OAuth Integration](https://docs.appmobi.com/guides/quickstart-oauth/index.html#google-oauth-integration) 
 - [Facebook OAuth Integration](https://docs.appmobi.com/guides/quickstart-oauth/index.html#facebook-oauth-integration)
--->

**Plugin Variables**
----------
Our plugin makes use of Cordova plugin variables to communicate with the Appmobi backend.  When installing the plugin you will need to provide 3 parameters:

- **APP_NAME**: The name of the application created on your Appmobi Management Portal.
- **PROJECT_ID**: The unique application indentifier of your Appmobi application.
- **CONFIG_URL**: The HTTP endpoint of your Appmobi Backend (ie. https://appmobi.com/ for our public cloud, https://127.0.0.1 for an Appmobi PrivateStack )

When the user creates a new app based on the sample in Intel XDK, The Appmobi plugin will be added using the default parameter values. The user needs to change default placeholder values with the above 3 parameters for initialization of Plugin.

Note: The above parameters should be correct as provided from private stack App. Any inaccuracy in parameters may results in Plugin initialization failure.

**References**
----------
 -  [Appmobi Official Website](https://www.appmobi.com/)
<!--- -  [Appmobi Documentation](https://docs.appmobi.com/)  --->
 -  [Apache Cordova](https://cordova.apache.org/) 

**Compatibility**
----------
Platforms : 
- Android
- iOS  
