# 80 Days Challenge — Android-friendly installable web app

This is a Progressive Web App (PWA). It can be installed on Android from Chrome and opened like an app. It stores checklists and notes in local browser storage on the device.

## Install on Android
1. Publish these files to an HTTPS host (for example, a static hosting service). Service-worker installation generally requires HTTPS, except localhost.
2. Open the hosted URL in Chrome on your Android phone.
3. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.
4. Launch **80 Days Challenge** from your home screen.

## Features
- 80-day calendar and per-day checklist
- Study 10 hours, Gym 2 hours, Food 3,200 kcal, Water 4 liters, Sleep 8 hours (11 PM–7 AM), Meditation 15 minutes
- Daily notes, completion percentage, perfect-day count, current streak
- Export and import JSON backups
- Offline caching after first successful load

## Data and privacy
Progress is stored locally in this browser on this device. It is not synced to a cloud account. Clearing browser/site data can erase progress, so export backups regularly. Importing a backup replaces the current local tracker data.

## Important note
This package is a PWA, not a signed APK. To install it like an app, host it over HTTPS and use Chrome's install option. A native APK would require a separate Android build/signing process.
