# 🌾 SIH Farmer

**SIH Farmer** is a FlutterFlow-based mobile application prototype created for fun as part of a Smart India Hackathon (SIH)-inspired idea. It focuses on providing a sleek, intuitive frontend for farmers with user authentication and profile management. This version does not include backend logic or integrations.

---

## 📖 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Firebase Setup](#firebase-setup)
- [Installation](#installation)
- [Usage](#usage)
- [Screens and UI](#screens-and-ui)
- [Configuration](#configuration)
- [Known Issues](#known-issues)
- [Contributors](#contributors)
- [License](#license)

---

## 🧭 Introduction

**SIH Farmer** is a prototype app for farmers to manage their profiles, access basic information, and securely log in. Developed entirely in FlutterFlow, this project showcases a frontend-oriented implementation with Firebase authentication and UI screens designed for a real-world agricultural app concept.

---

## ✨ Features

- 🌐 Firebase integration
- 🔐 Email/password authentication
- 👤 Profile screen with user info
- 📱 Clean, intuitive frontend UI
- 🛠️ No backend logic (UI-only prototype)

---

## 🛠 Tech Stack

- **FlutterFlow** – No-code/low-code app builder
- **Flutter** – Mobile UI framework (exported from FlutterFlow)
- **Firebase** – Authentication & hosting
- **Dart** – Underlying language for Flutter

---

## 🔥 Firebase Setup

1. Create a project on [Firebase Console](https://console.firebase.google.com/).
2. Add an Android/iOS app with your bundle ID.
3. Download and add the `google-services.json` (for Android) or `GoogleService-Info.plist` (for iOS) to your FlutterFlow project.
4. Enable **Authentication**:
   - Go to **Authentication > Sign-in method**
   - Enable **Email/Password** provider
5. (Optional) Set up **Firebase Hosting** if deploying a web version.

---

## 📦 Installation

> **Note:** This assumes you're exporting the project from FlutterFlow to run it locally with Flutter.

```bash
# Clone the exported FlutterFlow project
git clone https://github.com/your-username/sih-farmer.git
cd sih-farmer

# Get packages
flutter pub get

# Run on device or emulator
flutter run
