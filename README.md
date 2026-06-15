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



## ✨ New Features Part 3

### 🎨 Personalization Hub
A dedicated UI entry point accessed via the lower settings cog icon next to user details. Clicking it launches a sleek *Personalization Hub* modal with a cohesive playful aesthetic, providing direct access to three core customization features:

*A. AI Bot Personality 🤖*  
Customize your AI companion's (MelonBuddy's) interaction style:
- *Rename Your Companion:* A simple text input pre-filled with a placeholder name.
- *Personality Traits:* Three horizontal sliders to balance opposite traits — Friendly vs. Professional, Humorous vs. Direct, and Verbose vs. Concise.
- *AI Voice Profile:* Two selectable profile cards — 'MelonMan' (Deep) and 'Melonia' (Sweet) — each with a simple waveform graphic.

*B. Theme Deep Customization 🍉*  
Goes beyond standard light/dark modes by embracing the core "melon" aesthetic:
- *Segmented Variant Selector:* Choose from Classic Green, Golden Melon, Ice Melon, Sunset Melon, and Seedless — with small swatches and icons previewing each.
- *Golden Melon Theme:* When selected, primary green accents shift to a warm yellow-gold with a subtle playful background pattern.
- *Accent Color Picker:* A dedicated visual color wheel for fine-tuning highlight colors.
- *Pattern Density Slider:* Controls how many subtle watermelons are scattered across the background.

*C. Sound Profile 🎵*  
Manages all auditory feedback, from transaction alerts to background ambiance:
- *Transaction Sound Selector:* Four stylized buttons — Splash, Bite, Seed Drop, and Seeded Thud — with icons to visualize each sound effect.
- *Background Music Segmented Control:* Select from Off, Ambient Farm, Lo-fi Beats, and Nature (e.g., rustling leaves).
- *Volume Mixer:* Three separate vertical volume sliders with distinct icons — Clicks (Hand Icon), AI Speech (Robot Icon), and Music (Note Icon).

---

### ⏳ Days till Broke (DTB) — Predictive Burn Indicator
> The "Survival Clock" of Personal Finance

A high-impact predictive metric that moves away from static "Total Spent" numbers. It calculates the user's average daily burn rate against their remaining liquidity to estimate exactly when funds will hit zero — serving as a psychological "reality check" to encourage immediate spending adjustments.

*UI Details:*
- *Dynamic Dashboard Card:* A primary widget on the Home screen featuring a large, central countdown (e.g., "14 Days Remaining").
- *The "Shrivelling Melon" Visual:* A custom vector graphic reflecting the user's financial health. When DTB is high (20+ days), the melon is plump and bright teal (@color/teal_dark). As the number drops, the melon visually "shrivels," turning a warning coral (@color/coral_red) when under 5 days.
- *Contextual Subtext:* MelonBuddy provides a behavioural nudge beneath the countdown, e.g., "At your current rate of R450/day, you'll need to skip 3 takeout meals to make it to payday."

*UX Objective:* To convert abstract budget data into a concrete, time-based survival timeline that triggers immediate behavioural changes.

---

### 🔥 Time-of-Day Spending Heatmap — Behavioral Flux Visualizer

A sophisticated data visualization tool that maps spending intensity across a 24-hour cycle and 7-day week. It identifies *"Danger Zones"* — specific hours where the user is most prone to impulse spending (e.g., late-night online shopping or expensive morning coffee runs).

*UI Details:*
- *7x24 Intensity Grid:* A sleek, interactive grid located in the "Insights" tab. Each cell represents one hour of the week.
- *Chrono-Color Palette:* Uses M3LON's semantic "Heatmap Glow" colors — low-activity hours appear as a deep "Heatmap Night" blue, while high-spending peaks glow with an intense "Heatmap Glow Coral" or "Heatmap Glow Purple" effect.
- *Interactive "Peak" Overlay:* Tapping a high-heat cell reveals the dominant spending category for that time slot (e.g., tapping 8:00 AM shows "Coffee/Breakfast", while 11:00 PM might reveal "Digital Entertainment").
- *Visual Flair:* A subtle glassmorphism effect (frosted cards) over the app's @drawable/gradient_background maintains a premium feel.

*UX Objective:* To reveal hidden spending habits by showing when the user is most financially vulnerable, enabling targeted self-reflection and AI-assisted intervention during those specific "hot" hours.

## VIDEO DEMO PART 3
Video Demonstration -> https://youtu.be/cS79noi3sgA?si=VlT4zNpx3_W6diln

