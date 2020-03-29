```shell script
$ ionic start ionic-cordova-tabs-template tabs --cordova --type=ionic-angular

-- add native storage

$ ionic cordova plugin add cordova-sqlite-storage

$ npm install --save @ionic/storage

$ ionic cordova plugin add phonegap-plugin-barcodescanner

$ keytool -genkey -alias ionic.keystore -keyalg RSA -validity 20000 -keystore ionic.keystore

> ionicionic

```

```

> ionic serve

```

```shell script

$ ionic cordova platform add android

$ ionic cordova build android --prod --release

$ jarsigner -verbose -sigalg SHA256withRSA -digestalg SHA1 -keystore ./ionic.keystore -storepass ionicionic -signedjar ./release/android/app-release-signed.apk ./platforms/android/app/build/outputs/apk/release/app-release-unsigned.apk ionic.keystore
```
