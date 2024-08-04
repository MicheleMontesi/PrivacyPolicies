## Analysis Theorems: Privacy Policy

Welcome to the Analysis Theorems app for Android and iOS!

This is an open-source Android app developed by Michele Montesi.

As an avid Android user myself, I take privacy very seriously. I know how frustrating it is when apps collect your data without your knowledge.

### Data Collected by the App

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences like theme and alarms) created by you (the user) is stored locally on your device only and can be simply erased by clearing the app's data or uninstalling it. No analytics software is present in the app either.

### Explanation of Permissions Requested in the App

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

https://github.com/MicheleMontesi/PrivacyPolicies/blob/ea5bef68e83adad7483a0e9cbf196a36656c315e/AnalysisDemonstration/AndroidManifest.xml#L50-L52

| Permission | Why it is required |
| :---: | --- |
| `android.permission.INTERNET` | Required for the app to access the internet, necessary for functionalities like fetching data from online sources. Automatically granted by the system; cannot be revoked by the user. |
| `android.permission.ACCESS_NETWORK_STATE` | Needed to check the network state of the device, ensuring that the app can handle network changes and maintain functionality. Automatically granted by the system; cannot be revoked by the user. |
| `android.permission.WAKE_LOCK` | Allows the app to keep the device awake when necessary, such as during an ongoing operation that requires the screen to stay on. Automatically granted by the system; cannot be revoked by the user. |

<hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any questions regarding how the app protects your privacy, please send me an email and I will surely try to fix it/help you.

Yours sincerely,  
Michele Montesi  
michelemontesi36@gmail.com
