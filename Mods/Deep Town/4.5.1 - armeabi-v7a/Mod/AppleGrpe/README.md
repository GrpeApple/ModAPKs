# Modding:
### Installing the original
Use [apkcombo](https://apkcombo.com/en-dk/apk-downloader/?device=&arch=armeabi-v7a&android=&q=com.rockbite.deeptown) and download the apk file.
### Getting to the files
Decompile the apk.
### Modding the apk
In assets/json folder you can edit the json and xml files using your favorite editor.
### Wrapping it up
Compile what you did, and sign the apk.
### Install
Install, very simple.
### 
## Notes
#### [Instaling the original](#installing-the-original):
On [apkcombo](#installing-the-original), select architecture to armeabi-v7a and set package name to com.rockbite.deeptown and download the apk.
Because you don't wanna get split apks, use [Split APKs Installer (SAI)](https://play.google.com/store/apps/details?id=com.aefyr.sai&hl=en) or any other split apks installer.
Visit [platinmods](https://platinmods.com/threads/how-to-mod-split-apks-app-bundles.74051/) for more information.
#### [Getting to the files](#getting-to-the-files):
You can also extract the apk by renaming the .apk extension to .zip or extract it directly.
#### [Modding the apk](#modding-the-apk):
You can do whatever you want with it, I don't mind.
#### [Wrapping it up](#wrapping-it-up):
You can also compress ~~or not I haven't tested to not compress it yet.~~ the files and rename the .zip extension to .apk and sign ~~or not~~ it.
### What I Did:
1. Installed the original armeabi-v7a apk.
2. Extracted the apk using ZArchiver
3. Modded it with Acode ~~It supports Ctrl-F which is Find and also RegExp~~
4. Used APK Editor Pro ~~Not on Play store, Download it [here.]()~~ to build, and sign.
5. Installed using package installer. ~~If you don't have it, it's built-in to android. You already could have known to install it if you uninstalled it already.~~
# Changelog:
Mod | Modified Dictionary/XML | Modified File ~~In assets/json/~~
--- | ----------------------- | ---------------------------------
Buildings instantly build. | `"deployTime":0` | `building_blueprints.json`
Building instantly upgrade. | `"upgradeDuration":0` | `building_blueprints.json`