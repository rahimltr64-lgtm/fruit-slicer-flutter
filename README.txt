Flutter project wrapping the game in a WebView.
Android needs the CAMERA permission in android/app/src/main/AndroidManifest.xml:
<uses-permission android:name="android.permission.CAMERA"/>
<uses-feature android:name="android.hardware.camera" android:required="false"/>
If the project has no android/ folder, run: flutter create . --platforms=android
