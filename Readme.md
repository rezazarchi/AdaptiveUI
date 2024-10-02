# Adaptive UI with Jetpack Compose
This project showcases an adaptive layout with adaptive navigation items, designed to deliver an optimal user experience across various Android devices and window sizes. By leveraging the latest Jetpack Compose libraries, we've created a flexible and responsive UI that adapts seamlessly to different screen configurations and device types.
```kotlin
implementation("androidx.compose.material3.adaptive:adaptive")
implementation("androidx.compose.material3.adaptive:adaptive-layout")
implementation("androidx.compose.material3.adaptive:adaptive-navigation")
implementation("androidx.compose.material3:material3-adaptive-navigation-suite")
```
I got use of these resources: [Link 1](https://developer.android.com/develop/ui/compose/layouts/adaptive/list-detail), [Link 2](https://developer.android.com/develop/ui/compose/layouts/adaptive/build-adaptive-navigation), [Link 3](https://youtu.be/u8vQgmgf3X4?si=NJkAM56kp_vZKNfh), and [Link 4](https://youtu.be/W3R_ETKMj0E?si=LTpTDtcjNMGNNBxh) to implement this project.

## Screenshot
The video screenshots demonstrate the app's dynamic UI adaptation. The footage was captured on a Windows 11 machine using the Windows Subsystem for Android, allowing us to visualize how the UI changes in real-time as the window size is changes.

![recorded gif](asset/recorded.gif)



## Run the project

1. *Clone the Repository:*
```bash
git clone https://github.com/rezazarchi/AdaptiveUI.git
```
2. Open the project in Android Studio
   Current latest version is Koala Feature Drop 2024.1.2 Patch 1
3. build it to run the app on an emulator or connected device.
