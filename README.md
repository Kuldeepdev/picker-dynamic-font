What is the current behavior?
Ionic Picker component do not respond to font scaling on iOS which can create inaccessible applications particularly for users with low vision for Picker component.  Ionic apps on Android devices currently support the Android equivalent due to functionality in the Chromium webview.
Developers have also requested a way of adjusting the fonts in their Ionic Picker component consistently.


What is the new behavior?
* This means devs can change the font size on html and the text in supported Ionic Picker components will scale up/down appropriately
* Add support for Dynamic Type on iOS (the iOS version of Dynamic Font Scaling) for Picker Component.


