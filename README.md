# dart_define_test

Checking Dart define parameters to build android apps

## Files of interest
android\app\build.gradle  
android\app\src\main\AndroidManifest.xml  

## Getting Started
Run
```
flutter build apk --release --dart-define=appId=com.demo.define --dart-define="appName=define  app"
```

Flutter version used 2.0.4  
Flutter version matters, refer  

[Link 1](https://itnext.io/flutter-1-17-no-more-flavors-no-more-ios-schemas-command-argument-that-solves-everything-8b145ed4285d)  
[Link 2](https://medium.com/flutter-community/how-to-setup-dart-define-for-keys-and-secrets-on-android-and-ios-in-flutter-apps-4f28a10c4b6c)  