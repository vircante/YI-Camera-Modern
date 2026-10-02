# YI Camera Modern

<p align="center">
  <strong>A modernized Android client for YI cameras</strong>
</p>

<p align="center">
  Bringing the discontinued YI Camera experience back to modern Android devices.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-green?style=flat-square" alt="Android">
  <img src="https://img.shields.io/badge/Status-Community%20Maintained-blue?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Project-Open%20Source-orange?style=flat-square" alt="Open Source">
</p>

---

## 📱 About

**YI Camera Modern** is a community-maintained modernization of the discontinued **YI Camera** Android application.

The original application was designed for older Android versions and, over time, compatibility issues appeared on newer smartphones due to changes in Android's APIs, permissions, networking and storage system.

This project aims to keep compatible YI cameras usable on **modern Android devices** while preserving as much of the original experience and functionality as possible.

> This project is **not affiliated with or endorsed by YI Technology**.

---

## ✨ Features

The goal is to maintain and restore the functionality provided by the original application, including:

* 📷 Connect to compatible YI cameras
* 📡 Camera Wi-Fi connection
* 🎥 Live camera preview
* 📸 Remote photo capture
* 🎬 Remote video recording
* 🖼️ Browse camera media
* ⬇️ Download photos and videos
* ⚙️ Camera configuration
* 🔋 Camera status information
* 📱 Compatibility with modern Android versions

Some features may vary depending on the camera model and firmware.

---

## 🚀 Why this project?

The original YI Camera application was created for an older Android ecosystem.

Modern Android versions introduced significant changes to:

* Application permissions
* Storage access
* Wi-Fi APIs
* Background services
* Network security
* Broadcast receivers
* Scoped storage
* Deprecated Android APIs

As a result, an application that worked correctly years ago may no longer install, connect to the camera or provide the same functionality on current smartphones.

**YI Camera Modern** focuses on addressing these compatibility problems.

---

## 📱 Android compatibility

The project targets modern Android devices while attempting to retain compatibility with supported older devices.

| Component         | Target               |
| ----------------- | -------------------- |
| Platform          | Android              |
| Architecture      | ARM / ARM64          |
| Camera connection | Wi-Fi                |
| UI                | Native Android       |
| Status            | Community maintained |

> Actual compatibility depends on the Android version, smartphone, YI camera model and camera firmware.

---

## 🛠️ Building

### Requirements

* Android Studio
* JDK compatible with the project's Gradle version
* Android SDK
* Gradle

### Clone

```bash
git clone https://github.com/YOUR_USERNAME/YI-Camera-Modern.git
cd YI-Camera-Modern
```

### Build

Open the project with Android Studio and let Gradle synchronize.

Alternatively:

```bash
./gradlew assembleDebug
```

The generated APK can be found under:

```text
app/build/outputs/apk/debug/
```

---

## 🔧 Development

The modernization work focuses primarily on replacing or adapting components that no longer work correctly on current Android versions.

### Main areas

```text
Android compatibility
        │
        ├── Permissions
        ├── Storage
        ├── Wi-Fi
        ├── Networking
        ├── Background services
        └── Deprecated APIs

Camera communication
        │
        ├── Connection
        ├── Commands
        ├── Live preview
        └── Media transfer
```

---

## 🐛 Known issues

Because the original application is discontinued, some functionality may require additional reverse engineering or adaptation.

Possible issues include:

* Camera-specific compatibility problems
* Differences between camera firmware versions
* Wi-Fi connection issues on certain smartphones
* Missing functionality from the original application
* Android manufacturer-specific restrictions

If you encounter an issue, please open a GitHub Issue and include:

1. YI camera model
2. Camera firmware version
3. Android version
4. Smartphone model
5. Steps to reproduce the problem
6. Relevant logs or screenshots

---

## 🤝 Contributing

Contributions are welcome.

You can help by:

* Testing the application on different Android devices
* Testing different YI camera models
* Fixing Android compatibility issues
* Improving the camera communication layer
* Fixing UI problems
* Improving documentation
* Reporting bugs
* Submitting pull requests

Before submitting a pull request, please make sure the project still builds successfully.

---

## 📸 Supported cameras

Support depends on the implementation inherited from the original application and the camera protocol.

Compatibility testing with different YI cameras is encouraged.

| Camera           | Status     |
| ---------------- | ---------- |
| YI Action Camera | 🟡 Testing |
| YI 4K            | 🟡 Testing |
| YI 4K+           | 🟡 Testing |
| Other YI cameras | ⚪ Unknown  |

> The compatibility table will be updated as devices are tested.

---

## ⚠️ Disclaimer

**YI Camera Modern is an independent community project.**

It is not affiliated with, sponsored by, or endorsed by **YI Technology**.

**YI** and related product names and trademarks belong to their respective owners.

This repository contains modifications intended to improve compatibility with modern Android devices.

The licensing and copyright of the original application and any third-party components remain subject to their respective licenses.

---

## 📜 License

See the project's `LICENSE` file for licensing information.

If this repository contains code derived from the original YI Camera application or other third-party projects, their respective licenses and copyright notices remain applicable.

---

## ❤️ Project goal

The goal is simple:

> **Keep YI cameras usable for the people who still own them.**

Instead of letting perfectly functional cameras become difficult to use because their companion application was discontinued, this project attempts to modernize the Android software while preserving the original camera experience.

---

<p align="center">
  <sub>YI Camera Modern • Community maintained</sub>
</p>
