## Webview

Just a simple webview. for my website :D

## Core

Webview core:

- Flutter (Webview) - Android, IOS

## Build

Makesure you install flutter and Android studio correctly. If you not sure about that, type these command to verify the installation:

```shell
flutter doctor -v
```

The output should show [✓] (except Chrome).

```shell
❯ flutter doctor -v
[✓] Flutter (Channel master, 3.22.0-31.0.pre.13, on Arch Linux 6.8.9-zen1-2-zen, locale en_US.UTF-8)
    • Flutter version 3.22.0-31.0.pre.13 on channel master at /home/btw/Documents/flutter
    • Upstream repository https://github.com/flutter/flutter
    • Framework revision 3e14f18178 (22 hours ago), 2024-05-10 16:08:13 -0700
    • Engine revision ba8e0d3e2f
    • Dart version 3.5.0 (build 3.5.0-141.0.dev)
    • DevTools version 2.36.0-dev.5

[✓] Android toolchain - develop for Android devices (Android SDK version 34.0.0)
    • Android SDK at /home/btw/Android/Sdk
    • Platform android-34, build-tools 34.0.0
    • Java binary at: /opt/android-studio/jbr/bin/java
    • Java version OpenJDK Runtime Environment (build 17.0.10+0-17.0.10b1087.21-11572160)
    • All Android licenses accepted.

[✗] Chrome - develop for the web (Cannot find Chrome executable at google-chrome)
    ! Cannot find Chrome. Try setting CHROME_EXECUTABLE to a Chrome executable.

[✓] Linux toolchain - develop for Linux desktop
    • clang version 17.0.6
    • cmake version 3.29.3
    • ninja version 1.12.0
    • pkg-config version 2.1.1

[✓] Android Studio (version 2023.3)
    • Android Studio at /opt/android-studio
    • Flutter plugin version 79.0.2
    • Dart plugin can be installed from:
      🔨 https://plugins.jetbrains.com/plugin/6351-dart
    • Java version OpenJDK Runtime Environment (build 17.0.10+0-17.0.10b1087.21-11572160)

[✓] Connected device (2 available)
    • sdk gphone64 x86 64 (mobile) • emulator-5554 • android-x64 • Android 13 (API 33) (emulator)
    • Linux (desktop)              • linux         • linux-x64   • Arch Linux 6.8.9-zen1-2-zen

[✓] Network resources
    • All expected network resources are available.

! Doctor found issues in 1 category.
```

### Android build

```shell
git clone https://codeberg.org/UmmIt/Webview.git && cd Webview && flutter build apk
```
