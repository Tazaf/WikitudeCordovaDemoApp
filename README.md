# WikitudeCordovaDemoApp

**I didn't develop this application. It's only a more easily installable version of the official [Wikitude Cordova Plugin Demo App](https://github.com/Wikitude/wikitude-cordova-plugin-samples).**

## Install
1. Clone or download this repository
2. Navigate on the newly created folder
2. Install the platform on which you want to insall this app (**Be sure to install at least the version 5.0.0 of the android platform, otherwise the compilation will fail.**) :
  ```
  cordova platform add android@5.0.0
  ```
3. Install the plugins:
  ```
  cordova prepare
  ```
5. You'll need to register on the Wikitude website in order to obtain a Trial Licence Key. More information [here](https://github.com/Tazaf/ionicitude/wiki/Installing-the-Wikitude-plugin#wikitude-licence-key).
4. With your device plugged in your computer, install the app:
  ```
  cordova run android
  ```
