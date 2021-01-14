# AI RADIO

<p align=left>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
<img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintained Yes" />
<img src="https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg" alt="Ask me Anything" />
</p>

This is an beautiful UI and AI based Radio Application made using flutter.

![](https://github.com/aamit2267/music-guru-radio-app/assets/music-guru-1.png)
![](https://github.com/aamit2267/music-guru-radio-app/assets/music-guru-2.png)

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Installation
You need to install [Flutter](https://flutter.dev/docs/get-started/install) and [Android SDK](https://developer.android.com/studio) in your system, then:
```
git clone music-guru-radio-app
cd music-guru-radio-app
```

You need to make an account on [Alan](https://alan.app/) to get the voice assistance, after that you will find an sdk key:
- Grab the key.
- go to `lib/main/home_page.dart`
- On line number 51 you will get
```
setupAlan() {
    AlanVoice.addButton("ALAN_SDK_KEY", // paste your sdk key here
        buttonAlign: AlanVoice.BUTTON_ALIGN_RIGHT);
    AlanVoice.callbacks.add((command) => _handleCommand(command.data));
}
```
After all these setups, you are ready to go! start debugging your application by pressing `F5` on your keyboard.

## Credit Of This App

- [@impawan](https://github.com/impawan) - Pawan Kumar (GDE-Flutter)


Made By [Amit Agarwal](https://github.com/aamit2267) @2021
