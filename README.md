googleglass-phonegap-example
============================

Example Phonegap project that can be imported to Eclipse and exported as .apk file for Google Glass. The JavaScript includes touchpad events and accelerometer events via the Phonegap API.

##Prerequisites
1. Make sure [Glass Debugging](https://developers.google.com/glass/gdk) is turned on
2. Connect your Glass via **USB** to your computer
3. On your mobile device, turn on Glass **screencast**
4. On your computer, [Install Phonegap] (https://dl.dropboxusercontent.com/u/348446/trainings/android.html)

##Directions
1. Clone this ````<googleglass-phonegap-example>```` repository
2. In Eclipse, **File > New > Other (Cmd + N)**
3.  **Android > Android Project from Existing Code** 
4. Under **Root Directory**, select ````<googleglass-phonegap-example>/example/```` or whatever you named the cloned repository
5. Select the checkbox next to ````example````
6. Select **Copy projects into workspace**
7. Select **Finish**
8. In the **Package Explorer** on the left-hand side, right-click on ````example````
9. Select **Properties (Cmd + I)**
10. Under **Android** select ````Glass Development Kit Sneak Peek```` as the **Project Build Target > Target Name**
11. Make sure your Glass is connected over USB. You can now hit **Run Example** to see the results.
4. Make changes to JavaScript, HTML, and CSS in the ````<googleglass-phonegap-example>/example/assets/www```` directory

##Debugging
1. Download and install [Android Debug Bridge](http://developer.android.com/tools/help/adb.html) (adb)
2. In Terminal, ````cd```` to ````<adt-bundle...>/sdk/platform-tools````
   * run ````./android update adb````
   * run ````./adb kill-server````
   * run ````./adb start-server````
   * run ````./adb devices````
   * make sure Glass Serial Number is detected

##References
* [Phonegap Docs](http://docs.phonegap.com/en/2.6.0/guide_getting-started_index.md.html)
* [Android Debug Bridge](http://developer.android.com/tools/help/adb.html) aka 'ADB'
* [Glass GDK](https://developers.google.com/glass/gdk)

Screenshot of Glass accelerometer data:
![Google Glass accelerometer data via Phonegap](/screenshot_accel_data.png)