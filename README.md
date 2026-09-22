# Dot Launcher

A monochrome, dot-matrix home screen launcher for Android, built for the Galaxy Z Fold.

## Features
- Dot-matrix clock (red colon), weekday, date and next alarm, plus a battery ring widget
- Round monochrome icons: uses Android's themed-icon layer when an app provides one, otherwise a greyscale version of the icon
- Dot-grid black background
- Swipe up for the app drawer (with search), swipe down for notifications
- Separate layouts for the cover screen and the inner screen, which switch automatically when you fold or unfold
- Long-press an app to add it to or remove it from home, move it, hide it, open app info or uninstall it
- Long-press an empty spot on the home screen to open settings (monochrome/colour icons, dot grid, 24-hour clock, labels, battery widget, hidden apps, default home app)

## Build the APK (free, no Android Studio needed)
1. Create a free account at github.com and make a **new repository** (private is fine).
2. Click **"uploading an existing file"**, then drag in **everything inside this folder**, including the hidden `.github` folder. Tip: on a computer, press Cmd+Shift+. (Mac) or turn on hidden items (Windows) so you can see `.github`. Then click **Commit changes**.
3. Open the **Actions** tab. The "Build APK" job starts on its own and takes about 5 minutes.
4. When it shows a green tick, open the run and download **DotLauncher-apk** under *Artifacts*. It's a zip file that contains the APK.

## Install on the Fold
1. Copy the APK to your phone and tap it. When asked, allow "Install unknown apps" for your file manager or browser.
2. Press the Home button. When Android asks, pick **Dot Launcher → Always**. You can also go to Settings → Apps → Choose default apps → Home app.
3. To switch back later, choose **One UI Home** in the same menu.

## Alternative: Android Studio
Open this folder in Android Studio, wait for it to sync, then choose **Build → Build APK(s)**.
