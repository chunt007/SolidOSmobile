# SolidOSmobile
SolidOS for android and iOS that is in progress

This is a tutorial on how to run SolidOS natively for iOS or Android. No plans for Pine as of now.

JDK 21 issues at the moment is not allowing qemu emulator to function properly. libandroid emu metrics dll issues. But JDK21 seems the most compatible. 

JDK 24 issues below
assembleDebug being the worst of them. Literally none of the tutorials worked on this, so I just moved my building habits directly from VSCode to Android Studio.
--enable-native-access=ALL-UNNAMED
File capacitor.settings.gradle will prevent you from proceeding further until you remove "capacitor" from the file itself, then just runs into more bugs.

Initially used Git for Windows which has bash functionality and scripts that emulate Linux commands. *Personal choice of my own. The less libraries and extensions, then simplier the execution of the project and that is my goal here.

For now, I am using Powershell in Windows 11 to run Android Studio and we will be using VSCode with capacitor.

For newer android devices, you can simply pair your device with Android studio.

To access the hidden Android 16 Developer Options, go to Settings > About phone and repeatedly tap the Build number seven times until you see a message that you're a developer. You'll then find Developer options within the main Settings menu, usually under System. This hidden menu provides advanced tools for app developers to test, optimize, and debug applications on their devices. 

You will also want to enable wireless debugging, these instructions are already available in Android Studio 

For developer purposes, I will warn you that at any point in time, certain commands and certain versions of IDE/Code Editors/Compilers/Terminals/Etc may not work the way I intended for it to. Things change without notice and tutorials become extremely outdated without a revision in sight. I will do my best to ensure this repository remains consistent and hassle free. 

The specs of my programs at the time that I ran these tutorails These are the current programs I use interchangablly. I will not claim that all of them are necessary, but rather to avoid confusion and to warn you that everything should be an exact copy of what I use as I cannot know for certain how others have their versions set up raher out of the box or custom. Errors are prone to happen but if a tutorial is created, I have a job of warning you about its effectiveness. 

android-studio-2025.1.2.13-windows.exe
node-v22.19.0-x64
Git-2.51.0-64-bit
Cygwin 2.934
Git-2.51.0-64-bit



