
Fork from [https://bitbucket.org/nightstomp/cordova-plugin-googlemaps-sdk.git](https://bitbucket.org/nightstomp/cordova-plugin-googlemaps-sdk.git)

Use [Git Large File Storage](https://git-lfs.github.com/) to storage GooleMaps file.

GoogleMaps for iOS SDK (Cordova)
===============================
This plugin just installs Google Maps SDK for iOS to your project.

Google Maps SDK for iOS
https://developers.google.com/maps/documentation/ios/

The official way (provided by Google Inc.) would be to use CocoaPods, but currently, Cordova will break building and running on simulator, when using pods. As interims-solution, we need to use this repo. It includes the current iOS SDK 1.13.0
https://cocoapods.org/?q=GoogleMaps

As soon as cordova supports CocoaPods, this repo will be deleted and Cocoapods will be included. As seen on JIRA, XCWorkspace (which is required for pods) should be available on cordova-ios-4 (currently, 09/14/2015) - it's on version 3.9.2

I could not find any document which prohibited uploading the original files to github/bitbucket, if so, please write me! I will response asap.
