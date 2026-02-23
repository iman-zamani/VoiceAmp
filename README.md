# VoiceAmp

VoiceAmp turns your Android phone into a portable microphone and speaker system.

It captures your voice using the device microphone and streams it in real time to a connected Bluetooth speaker or other audio output device.

This is useful for:

* Small presentations
* Teaching in classrooms
* Outdoor speaking
* Quick announcements
* Situations where a traditional microphone setup is not available

---

## Features

* Real-time voice streaming
* Audio output to Bluetooth or wired speakers
* Simple press-and-hold recording control
* Lightweight and easy to use

---

# Installation

## Option 1: Install via APK (Recommended)

1. Go to the **Releases** section of this repository.
2. Download the latest APK file.
3. Open the APK file and install it.
4. Allow installation from unknown sources if prompted.

After installation, launch the app and grant microphone permission.

---

## Option 2: Build from Source (For Developers)

### Requirements

* Android Studio Arctic Fox (2020.3.1) or newer
* Android SDK with compile SDK version 34
* Android device running Android 7.0 (API level 24) or higher
* Bluetooth speaker or external audio output device

### Steps

1. Clone the repository:

```bash
git clone https://github.com/iman-zamani/VoiceAmp.git
```

2. Open Android Studio.
3. Select **Open an Existing Project**.
4. Choose the cloned project folder.
5. Allow Gradle to sync.
6. Connect a physical Android device (recommended for audio testing).
7. Click **Run** to build and install the app.

---

# Usage

1. Connect your phone to a Bluetooth speaker.
2. Launch VoiceAmp.
3. Grant microphone permission when requested.
4. Press and hold the "Record" button to start streaming.
5. Release the button to stop streaming.

Your voice will be played through the connected speaker in real time.

---

# Important Notice

This project is currently under development and is not ready for production use.

* It may contain bugs or stability issues.
* Performance may vary between devices.
* Security measures are not fully implemented.

Use this project for testing and experimental purposes only.

---

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
