# M3LON — Smart Banking, Sliced Simple 🍉

## Description
M3LON is a personal budget tracking Android application built for 
OPSC6311 Module — Part 2 Prototype.
Developed by: The_5_Watermelons
Full Names and Student Numbers: 
Tshiamo Mosetlha - ST10451437, 
Zandile Selao - ST10436981,
Matlhogonolo Keebine - ST10452412,
Muhluri Nkuna - ST10437226,
Ndabezinhle Mthunyane - ST10457068

Group: The 5_Watermelons

## Features
- 🔐 User Registration & Login with Firebase Authentication
- 🏠 Home Dashboard with monthly budget overview
- 💸 Expense tracking with date, time, category and description
- 📷 AI Receipt Scanner using ML Kit Text Recognition
- 📊 Graphs & Trends (Line & Bar charts)
- 💰 Budget Goals with minimum and maximum limits
- 🗂️ Category management (Food, Transport, Shopping, etc.)
- 👤 User Profile with badges and XP system
- 💾 Local data storage with RoomDB
- ☁️ Cloud sync with Firebase Firestore

## Tech Stack
- **Language:** Kotlin
- **IDE:** Android Studio Otter 3 Feature Drop (2025.2.3)
- **Database:** RoomDB (local) + Firebase Firestore (cloud)
- **Authentication:** Firebase Authentication
- **AI/ML:** Google ML Kit Text Recognition
- **Charts:** MPAndroidChart
- **Architecture:** MVVM (ViewModel + LiveData + Repository)
- **Min SDK:** API 24 (Android 7.0)
- **Target SDK:** API 36

## How To Run
1. Clone the repository
2. Open in Android Studio Otter 2025.2.3
3. Add your own `google-services.json` from Firebase Console
4. Enable Email/Password Authentication in Firebase Console
5. Enable Firestore in Firebase Console
6. Build and run on Android device (API 24+)

##FROM PART 1 - VISUAL  STORYBOARD LINK
https://tmosetlha.github.io/ST10451437_5_WATERMELONS_VISUAL_STORYBOARD_FOR_M3LON/

## Video Demo
[Click here to watch the demo](YOUR_YOUTUBE_LINK_HERE)

## APK
[Download the latest APK from the releases section.](https://github.com/tmosetlha/5_Watermelons_M3LON/releases/download/M3LON_v1.0/app-debug.apk)

## References
- Firebase Documentation: https://firebase.google.com/docs
- Android Developer Docs: https://developer.android.com/docs
- ML Kit Text Recognition: https://developers.google.com/ml-kit/vision/text-recognition
- MPAndroidChart: https://github.com/PhilJay/MPAndroidChart
- Room Database: https://developer.android.com/training/data-storage/room
- Kotlin Documentation: https://kotlinlang.org/docs/home.html
