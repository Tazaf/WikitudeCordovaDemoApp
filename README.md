# WikitudeCordovaDemoApp

**I didn't develop this application. It's only a more easily installable version of the official [Wikitude Cordova Plugin Demo App](https://github.com/Wikitude/wikitude-cordova-plugin-samples).**

## Install
1. Clone or download this repository
2. Navigate on the newly created folder
3. Install the platform on which you want to install this app
    ```
    cordova platform add android
    ```
    ...or...
    ```
    cordova platform add ios
    ```
    (**For android platform, be sure to have at least the android@5.0.0 platform version**)
4. Install the plugins:
    ```
   cordova prepare
   ```
5. You'll need to register on the Wikitude website in order to obtain a Trial Licence Key. More information [here](https://github.com/Tazaf/ionicitude/wiki/Installing-the-Wikitude-plugin#wikitude-licence-key).
6. When you get your icence key, replace the value of `this._sdkKey` on the line 14 of the `WikitudePlugin.js` file located in the ` WikitudeCordovaDemoApp/platforms/android/platform_www/plugins/com.wikitude.phonegap.WikitudePlugin/www` folder.
7. For the Licence Key to be propertly propagated, you'll need to remove your platform and then reinstall it.
7. With your device plugged in your computer, install the app:
   ```
   cordova run android
   ```
