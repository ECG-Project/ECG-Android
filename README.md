# KE.Net ECG

KE.Net ECG is an Android application that implements getting an ECG from a Polar H10 heart monitor. The H10 needs to have firmware version 3.0.35 or later installed, and you need to know the ID of your device (which is printed on its side).  You can see the ECG trace in real time and save PNG and CSV files of the data.

See <https://kenevans.net/opensource/KEDotNetECG/Assets/kedotnetecg.html> for more information.

It uses the Polar SDK located at <https://github.com/polarofficial/polar-ble-sdk>.

**More information**

More information and FAQ are at <https://kennethevans.github.io> as well as more projects from the same author.

Licensed under the MIT license. (See: <https://en.wikipedia.org/wiki/MIT_License>)


# Installation
Download project from Github, using `main` branch. Open this project in Android Studio. Then
in menu **File > Sync Project with Gradle Files** to install dependencies.

It's recommended to use Physical Device which can be plugged in via USB, don't use Virtual device supported in Android Studio. 
Then open Debugging Mode in Android (you can search over the Internet about how to enable this function).

Then compile and run project using Android Studio.