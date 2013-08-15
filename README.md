googleglass-phonegap-example
============================

Example Phonegap project that can be imported to Eclipse and exported as a .apk file for Google Glass

##Prerequisites
1. Make sure [Glass Debugging](https://developers.google.com/glass/gdk) is turned on
2. Connect your Glass via **USB** to your computer
3. In your Glass mobile app, turn on **screencast**
4. [Install Phonegap] (https://dl.dropboxusercontent.com/u/348446/trainings/android.html)

##Directions
1. Clone this ````<googleglass-phonegap-example>```` repository
2. In Eclipse, **import** the ````<googleglass-phonegap-example>/example/```` directory
3. Download and install [Android Debug Bridge](http://developer.android.com/tools/help/adb.html) (adb)
4. In Terminal, ````cd```` to ````<adt-bundle...>/sdk/platform-tools````
   * run ````./android update adb````
   * run ````./adb kill-server````
   * run ````./adb start-server````
   * run ````./adb devices````
   * make sure Glass Serial Number is detected
5. In Eclipse, right-click on the example project and hit 'run example'. You should see an option to upload to your Glass.
6. Make changes to JavaScript, HTML, and CSS in the ````<googleglass-phonegap-example>/example/assets/www```` directory

##References
* [Phonegap Docs](http://docs.phonegap.com/en/2.6.0/guide_getting-started_index.md.html)
* [Android Debug Bridge](http://developer.android.com/tools/help/adb.html) aka 'ADB'
* [Glass GDK](https://developers.google.com/glass/gdk)