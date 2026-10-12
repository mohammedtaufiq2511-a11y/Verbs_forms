# Useful Verbs Builder - Android App

## Option 1: Sabse aasan (bina Android Studio)
1. www folder ko kisi free hosting par daalo (Netlify Drop / GitHub Pages).
2. Phone ke Chrome mein link kholo, menu > "Add to Home screen" / "Install app".
3. Ye offline bhi chalega (service worker ke saath).
4. APK chahiye to https://www.pwabuilder.com par apna link daal ke "Android" package download karo.

## Option 2: Android Studio se APK
1. Node.js (v18+) aur Android Studio install karo.
2. Is folder mein terminal kholo:
   npm install
   npx cap add android
   npx cap sync android
   npx cap open android
3. Android Studio mein: Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK yahan milegi: android/app/build/outputs/apk/debug/app-debug.apk

## Update karna ho
www/index.html badlo, phir: npx cap sync android, aur dobara APK banao.
App ID: com.taufiq.usefulverbs
