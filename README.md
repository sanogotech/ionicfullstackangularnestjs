# ionicfullstackangularnestjs
Ionic Full Stack  Angular  Nestjs


## Code Source Fork
- https://github.com/sanogotech/demo-ionic-nest-tutorial



## Docs

- https://ionicframework.com/docs/intro/cli
- https://ionicframework.com/blog/full-stack-typescript-with-ionic-angular-and-nestjs-part-1/
- https://ionicframework.com/blog/full-stack-typescript-with-ionic-angular-and-nestjs-part-2/

## Install

```
npm install -g cordova ionic
or
npm install -g @ionic/cli
```


* Create an Ionic app using one of the pre-made app templates, or a blank one to start fresh. 
* The three most common starters are the *blank starter, *tabs starter, and *sidemenu starter.

```
ionic start myapp sidemenu
cd myapp
ionic lab
or
ionic  serve
```

```
htpp://localhost:8100
```

## Build Android APK

* After you've successfully installed the JDK/Maven/Gradle,
* you need to also install Android Studio, the Android IDE (integrated development environment).

```
The "android" command is deprecated.
For manual SDK, AVD, and project management, please use Android Studio.
For command-line tools, use tools\bin\sdkmanager.bat
and tools\bin\avdmanager.bat
```


```
sdkmanager --list
 
For simple list of ADB packages type in terminal:

android list sdk 

for install all packages:

android update sdk --no-ui
```

```
ionic integrations enable capacitor
ionic capacitor add android
ionic capacitor sync
cd android && ./gradlew assembleDebug && cd ..

```


* OK
* If the build completes successfully, you'll find your app's apk at android/app/build/outputs/apk/debug/app-debug.apk
