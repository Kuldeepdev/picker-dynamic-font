What is the current behavior?
Ionic Picker component do notrespond to font scaling on iOS which can create inaccessibleapplications particularly for users with low vision for Picker component. Ionic apps onAndroid devices currently support the Android equivalent due tofunctionality in the Chromium webview.
Developers have also requested a way of adjusting the fonts in theirIonic Picker component consistently.


What is the new behavior?
* Thismeans devs can change the font size on html and the text in supportedIonic Picker components will scale up/down appropriately
* Add support for Dynamic Type on iOS (the iOS version of Dynamic FontScaling) for Picker Component.


