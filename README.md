# AppLock - App Password Locker for Android

## How to get the APK (5 minutes):

### Method 1: GitHub Actions (Recommended - Free)
1. Create a free account at https://github.com
2. Create a new repository (name: AppLock)
3. Upload all files from this ZIP keeping the folder structure
4. Go to Actions tab → "Build APK" → "Run workflow"
5. Wait ~5 minutes → Download the APK from Artifacts

### Method 2: Android Studio
1. Install Android Studio from https://developer.android.com/studio
2. Open this folder as a project
3. Build → Generate Signed APK → Debug

## Features:
- PIN lock (4-8 digits) for any installed app
- Works in background as a foreground service
- Auto-starts after phone reboot
- 5 wrong attempts = 30 second lockout
- Dark theme, lightweight

## First Launch:
1. Install APK (enable "Install from unknown sources")
2. Set your PIN
3. Grant Usage Access permission
4. Grant Draw Over Apps permission
5. Press "Start Guard"
6. Toggle which apps to protect

## Requirements:
- Android 5.0+ (API 21+)
