# react-native-google-admob

## React Native
Run instructions for iOS:
• npx react-native run-ios
- or -
• Open GoogleAdMob/ios/GoogleAdMob.xcworkspace in Xcode or run "xed -b ios"
• Hit the Run button


Run instructions for Android:
• Have an Android emulator running (quickest way to get started), or a device connected.
• npx react-native run-android

Run instructions for Windows and macOS:
• See https://aka.ms/ReactNative for the latest up-to-date instructions.

## Install modules
1. yarn add https://github.com/nghidang/react-native-admob-native-ads#paperbit
2. yarn add react-native-gesture-handler react-native-star-rating react-native-vector-icons
3. npx pod-install

## Google AdMob SDK
### iOS
1. Open your project's Podfile and add this line to your app's target:
    pod 'Google-Mobile-Ads-SDK'
2. npx pod-install
3. Update your Info.plist
    <key>GADApplicationIdentifier</key>
    <string>ca-app-pub-xxxxxxxxxxxxxxxx~yyyyyyyyyy</string>

### Android
1. Update your AndroidManifest.xml
    <meta-data
        android:name="com.google.android.gms.ads.APPLICATION_ID"
        android:value="ca-app-pub-xxxxxxxxxxxxxxxx~yyyyyyyyyy"/>
