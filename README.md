# Boxchat-Native
A Secure Private Chat Platform.

This project uses React Native as the underlying framework, so Boxchat-Native can achieve "one build, run everywhere".

## Compared to Boxchat-Hybrid
Boxchat-Native is different from Boxchat-Hybrid.

Boxchat-Native eventually generates a Native APP instead of a nested Webkit. 

So in theory, Boxchat-Native will have a significant increase in performance and security compared to the previous Hybrid version.

## How to Run
### Starts the Webserver
```
react-native start
```

### Run on Android
> If you want to run this project on your Android device, you need to change the file path in ```/android/gradle.properties``` to your Android SDK folder location, or delete the file directly (if your ANDROID_HOME path Configuration is correct.)
```
react-native run-android
```

### Run on iOS
```
react-native run-ios
```
