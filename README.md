# setup-godot-export
<p align=justify>Step by step instructions for setting up godot window, android export for the game.</p>

## Summarized Instruction

<p align="center">
  <a href="https://www.youtube.com/watch?v=NRlZYmFzY1Q">
    <img src="https://img.youtube.com/vi/NRlZYmFzY1Q/hqdefault.jpg" alt="Export Android Game Demo" width="600">
  </a>
</p>

<p align=justify>Below are the same step told on the youtube video but i make it shorter as much as possible, altough i highly recommend to watch the full youtube video as it explain every detail of the download processes and export setup preocesses concisely.</p>

##

<br>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="40" height="40" align=center /> Getting Started

## 1. Download OpenJDK 17
<p align=justify>go to the download site and find windows operating system and make sure its on x64 , then click the download icon that contains the .msi file, then patiently wait to finish download of the .msi installer.</p>

[Download Here.](https://adoptium.net/en-GB/temurin/releases/?variant=openjdk17&version=17&os=any&arch=any)

##


## 2. Install OpenJDK Zip File

<p align=justify>click the .msi and it will pop up a window setup installer, once open click the following:</p>

next -> next -> install

<p align=justify>after clicking install button it will start to prepare the openJDK file and patiently wait to finish the downloading process, after the finsih of downloading progress click finish button and you already done installing OpenJDK 🎉✨.</p>

##


## 3. Downloading Android Studio
<p align=justify>Go to the Download site of the android studio by clicking the "Download Android Studio Narwhal 3 Feature Drop" on the link below:</p>

[Download Here.](https://developer.android.com/studio/)

##


## 4. Installing Android Studio
<p align=justify>As you downloaded the exe file or the installer, click on it then it will appear a window pop up or the android studio installer, click the following:</p>

next -> next -> next -> install

<p align=justify>as you click the install button it will start to install the android studio then wait for it to complete, as on completion of download click next then make sure to have the "Start Adnroid Studio" get checked then click finish.</p>

##


## 5. Setup Android Studio
<p align=justify>As you redirect from the Android Studio app beginning setup , click next then select "Standard" then click next, we can see our sdk path folder and we will use it later, dont download any yet</p>

##


## 6. Open a Godot Project
<p align=justify>Open youre godot then select a project you want to export, then on the top left click on:</p>

Editor -> Manage Export Templates

<p align=justify>Then click Download and Install Templates and wait for the download progress to finish, after the download is finish go again to the </p>

Editor -> Editor Settings -> (Scrolldown) Export -> Android 

##


## 7. Get Android SDK Path
<p align=justify>Open File Explorer then type on the searchbar: </p>

```
%localappdata%
```

<p align=justify>Click the Following Folders:</p>

Android -> sdk

<p align=justify>then on the search bar copy the folder path and paste it on the "Android SDK Path" in open godot, </p>

##


## 8. Get Debug Keystore

<p align=justify>Open command prompt then type:</p>

```
where javac
```

<p align=justify>then copy paste the path but it will only copy without the javac.exe, after that goto godot then paste it on the "Debug Keystore" after pasting it, click on the folder icon then you will see a file named "debug.keystore", select it by double clicking it.</p>

##

## 9. Get Java SDK Path
<p align=justify>then after that on the earlier where we typed where javac, copy again the link but now without the "/bin/javac.exe", then open godot again then paste it on the Java SDK Path</p>

##


## 10. Export the Project
<p align=justify>Now you're ready to export the project 🥳🎉✨, goto the following:</p>

Project -> Export .. -> Add -> Android -> (Optional if have some error) Fix Import -> Export Project ...

<p align=justify>After clicking the Export project its up to you where you gonna place teh apk file and ready to test the deployed application</p>

##

<p align=justify>[ 🐞 ] If any issues or concerns you can just put it on the issues, feedbacks are always welcome and we will keep it sharp as possible ✨</p>