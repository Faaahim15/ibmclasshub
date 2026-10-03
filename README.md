# IBM Class Hub – Android wrapper

WebView app that loads https://ibmclasshub.lovable.app/

## Get the APK (no Android Studio needed)
1. Create a free account at github.com and make a new repository.
2. Upload ALL files/folders from this project (including the hidden .github folder).
3. Go to the repo's "Actions" tab -> "Build APK" -> wait ~3-5 min for the green tick.
4. Open the finished run -> "Artifacts" -> download "IBMClassHub-apk" (zip) -> extract app-debug.apk.
5. Send the APK to anyone. They must allow "Install unknown apps" on their phone.

## Or build with Android Studio
Open this folder in Android Studio -> Build -> Build APK(s).

## Customize
- Site URL: app/src/main/java/com/ibmclasshub/app/MainActivity.java (APP_URL, APP_HOST)
- App name: app/src/main/res/values/strings.xml
- Icon: app/src/main/res/drawable/ic_launcher.xml
