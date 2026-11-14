Buddy Android ICON FIX — upload pack (2026-11-14)
What changed: launcher icons only (real Buddy art, same as the approved iOS icon) + version bump to versionCode 3 / versionName 1.2. Nothing else touched.
Upload to repo mdarybeth28/inventory-buddy-android, replacing the same paths:
- android/app/build.gradle
- android/app/src/main/res/mipmap-mdpi/ic_launcher.png, ic_launcher_round.png, ic_launcher_foreground.png
- same 3 files in mipmap-hdpi, mipmap-xhdpi, mipmap-xxhdpi, mipmap-xxxhdpi
Then run the Android build workflow; upload the new AAB to the Closed testing (Alpha) track as a new release. Tester opt-ins and 14-day clocks are NOT affected by a new release on the same track.
