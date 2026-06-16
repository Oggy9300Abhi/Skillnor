# Skillnor - Location-Based Skill Sharing App

## ✅ Features Implemented
- ✅ Login/Signup with Phone & Email (Firebase Auth)
- ✅ Location-based posts with custom radius
- ✅ Two user types: Helper & Seeker
- ✅ Post skills or needs
- ✅ Real-time chat system
- ✅ User ratings after completion
- ✅ Nearby posts discovery

## 🚀 Quick Start

### Prerequisites
- Android Studio latest
- Min SDK 24, Target SDK 34
- Firebase project

### Setup Firebase
1. Go to https://console.firebase.google.com
2. Create project "Skillnor"
3. Add Android app
4. Download google-services.json
5. Place in `app/` folder

### Build APK
```bash
./gradlew assembleDebug
# APK will be in: app/build/outputs/apk/debug/app-debug.apk
```

### Tech Stack
- Kotlin + Firebase
- Firestore (Database)
- Google Maps API
- Material Design 3
- MVVM Architecture
