googleglass-phonegap-example
============================

Example Phonegap project that can be imported to Eclipse and exported as a .apk file for Google Glass

##Prerequisites
1. Make sure [Glass Debugging](https://developers.google.com/glass/gdk) is turned on
2. Connect your Glass via **USB** to your computer
3. In your Glass mobile app, turn on **screencast**

##Directions
1. [Follow these instructions to install Phonegap] (https://dl.dropboxusercontent.com/u/348446/trainings/android.html)
2. Clone this ````<googleglass-phonegap-example>```` repository
3. In Eclipse, **import** the ````<googleglass-phonegap-example>/example/```` directory
4. Download and install [Android Debug Bridge](http://developer.android.com/tools/help/adb.html) (adb)
5. In Terminal, navigate (````cd````) to ````<adt-bundle...>/sdk/platform-tools````
   * run ````./android update adb````
   * run ````./adb kill-server````
   * run ````./adb start-server````
   * run ````./adb devices````
   * check to see if Glass Serial Number is detected
6. In Eclipse, right-click on the example project and hit 'run example'

##References
* [Phonegap Docs](http://docs.phonegap.com/en/2.6.0/guide_getting-started_index.md.html)



