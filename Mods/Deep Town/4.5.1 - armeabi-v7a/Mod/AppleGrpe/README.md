# Modding:
## Installing
Go to [apkcombo](https://apkcombo.com/en-dk/apk-downloader/?device=&arch=armeabi-v7a&android=&q=com.rockbite.deeptown) and download the apk file. --if you are already on apkcombo, select architecture to armeabi-v7a and set package name to com.rockbite.deeptown and download the apk. ( because you don't wanna get split apks, use "Split APKs Installer (SAI)" or any other split apks installer. and note that this will mod a single apk file. go to "https://platinmods.com/threads/how-to-mod-split-apks-app-bundles.74051/" for that. And if the apk file doesn't use  that architecture, go to that also.-
Decompile the apk.
( or extract the apk using ZArchiver or rename the .apk extension to .zip and extract it by using your favorite app. )
Modding:
  - Mod whatever you want.
  - for modding and getting whateer you want edit the file(s) located in assets/json/ and use the appropiate json and xml editor.
Compile. ( or compress the folders and files and rename the .zip extension to .apk )
Sign the .apk ( you can also not )
Install ( simple )
What I Did:
ditor signs automatically
yes.
Changelog:
Mod | Modified Dictionary/XML | Modified File ~~In assets/json/~~
--- | ----------------------- | ---------------------------------
Buildings instantly appear when you build them. | `deployTime:0` | `building_blueprints.json`