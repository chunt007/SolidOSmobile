# SolidOSmobile
SolidOS for android and iOS that is in progress

This is a tutorial on how to run SolidOS natively for iOS or Android. No plans for Pine as of now.

JDK 21 seems like the safest build

For now, I am using Powershell in Windows 11 to run Android Studio and capacitor library.

Here are the current versions of software that are being used right now 

android-studio-2025.1.2.13-windows.exe
node-v22.19.0-x64
Git-2.51.0-64-bit
Cygwin 2.934
Git-2.51.0-64-bit
Capacitor 7.4.3
Npm 11.5.1


JDK 24 issues below
assembleDebug being the worst of them. Literally none of the tutorials worked on this, so I just moved my building habits directly from VSCode to Android Studio.
--enable-native-access=ALL-UNNAMED
File capacitor.settings.gradle will prevent you from proceeding further until you remove "capacitor" from the file itself, then just runs into more bugs.
-libandroid emu metrics dll issues.

main bug is have to set the java environment variable each time. 

npx cap run android should start the program. I suggest enabling the virtual emulator in Android Studio *Depending on your virtual phone of choice* first before starting the program. 

export JAVA_HOME="C:\Program Files\Java\jdk-21" or where ever your location is.

Initially used Git for Windows which has bash functionality and scripts that emulate Linux commands. *Personal choice of my own. The less libraries and extensions, then simplier the execution of the project and that is my goal here.  






