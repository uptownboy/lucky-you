# Lucky You

[中文简介](README_cn.md)

LuckyYou is a simple app build on [tauri](https://github.com/tauri-apps/tauri) framework to provide a crossplatform application to do a lucky draw or make a roll call on your class or similar use cases.

## Install

Firstly you need to download from release page according to your platform, I will always release 3 files per version:

- .dmg for MacOS
- .msi for Windows
- .deb for Linux

> Note: If you are using windows and faced the problem of **Missing dll vcruntime**, please download it from [here](https://cn.dll-files.com/vcruntime140_1.dll.html) and put it to your `C:\Windows\System32` and try again.

## Use

Follow the below steps to use the app:

1. You need to prepare your image files with a meaningful name, like student's full name, and put them into one directory.

2. You start the LuckyYou app, click the "Select image fodler" button to select the directory in step 1

3. When the app reading image files done, You can click the "Start" button, and it will display every image and its filename on the screen.

4. You can click "Stop" button at any time and once you click it, the app will stop rolling and display the choosen image and its filename, i.e. the lucky one!

## License

CC0-1.0, Non-comercial