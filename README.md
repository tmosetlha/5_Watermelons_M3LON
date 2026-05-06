# M3LON — Smart Banking, Sliced Simple 🍉

## Description
​📝 Project Description   
​M3LON (Smart Banking, Sliced Simple) is a high-performance personal finance management application developed as a prototype for the OPSC6311 module. The application is designed to solve the common friction points in manual expense tracking by leveraging Artificial Intelligence and Cloud Infrastructure.
​Developed by The 5 Watermelons, M3LON moves beyond basic data entry. By integrating Google ML Kit’s Optical Character Recognition (OCR), users can instantly digitize physical receipts, transforming paper waste into actionable financial data. The application follows a modern MVVM (Model-View-ViewModel) architectural pattern to ensure a fluid user experience and scalable code logic, optimized specifically for high-end Android hardware.

​🚀 The M3LON Mission   
​Financial literacy is often hindered by the "effort" of tracking. M3LON aims to "slice" through that complexity with:   
​Automation: Reducing manual input through AI-driven receipt scanning.   
​Visual Intelligence: Converting raw transaction logs into intuitive Line and Bar charts via MPAndroidChart.   
​Gamification: Encouraging consistent financial habits through a custom XP and Badge system integrated into the user profile.   

​Hybrid Storage: Utilizing a dual-database approach with RoomDB for offline-first local persistence and Firebase Firestore for real-time cloud synchronization.

​👥 The 5 Watermelons (Development Team)
​This project represents a collaborative effort by a dedicated team of developers at Rosebank College:

​Tshiamo Mosetlha (ST10451437)  
​Zandile Selao (ST10436981)  
​Matlhogonolo Keebine (ST10452412)   
​Muhluri Nkuna (ST10437226)   
​Ndabezinhle Mthunyane (ST10457068)   

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

## GITHUB LINK
https://github.com/tmosetlha/5_Watermelons_M3LON.git

## FROM PART 1 - VISUAL  STORYBOARD LINK
https://tmosetlha.github.io/ST10451437_5_WATERMELONS_VISUAL_STORYBOARD_FOR_M3LON/

## VIDEO DEMO
Video Demonstration: MALE DEMO - >  https://youtu.be/OKgmmu0sRnk?si=m_1XiVDV9F49dgg-

Video Demonstration: FEMALE MALE DEMO - > https://youtu.be/6Tz25YlzVGE?si=jMxIfoVpovsYLuh9

## APK
[Download the latest APK from the releases section.](https://github.com/tmosetlha/5_Watermelons_M3LON/releases/download/M3LON_v1.0/app-debug.apk)

## REFERENCES
- Firebase Documentation: https://firebase.google.com/docs
- Android Developer Docs: https://developer.android.com/docs
- ML Kit Text Recognition: https://developers.google.com/ml-kit/vision/text-recognition
- MPAndroidChart: https://github.com/PhilJay/MPAndroidChart
- Room Database: https://developer.android.com/training/data-storage/room
- Kotlin Documentation: https://kotlinlang.org/docs/home.html
