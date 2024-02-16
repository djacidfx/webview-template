<h1 align="center">
     WebView Template
</h1>
<p align="center">
     <a style="text-decoration:none" href="https://github.com/djacidfx/webview-template/commits/master">
          <img src="https://img.shields.io/github/last-commit/djacidfx/webview-template?color=informational&label=last%20update" alt="License" />
     </a>
     <a style="text-decoration:none" href="LICENSE">
          <img src="https://img.shields.io/github/license/djacidfx/webview-template" alt="License" />
     </a>
     <a style="text-decoration:none" href="CODE_OF_CONDUCT.md">
          <img src="https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg" alt="Code of Conduct" />
     </a>     
</p>
     <h2>Find Us On The Google Play Store:</h2>
<p align="center">
<a href="https://play.google.com/store/apps/dev?id=8599109884308816488" target="_blank"><img src="/screenshots/google.png" alt="Google Play Store Link"></a>
</p>

If you want to create an Android app from any responcive website without writing a lot of code? This project is the perfect solution for you. It is a ready-made WebView template that saves you time and hassle.

### Features
* Support Android 5.0+ to 14
* Latest Android libraries
* Splash Screen
* Progress bar to indicate a webpage is being loaded.
* Swipe down to refresh current webpage.
* Show custom error page in times of connectivity issues.
* Protect WebView's state from configuration changes. (e.g. screen orientation and keyboard availability changes)
* Plenty of comments in source code

## Build
1. Click the **Code** button, which brings up a dialog.
2. In the dialog, click the **Download ZIP** button to save the project to your computer. Wait for the download to complete.
3. Locate the file on your computer (likely in the **Downloads** folder).
4. Double-click the ZIP file to unpack it. This creates a new folder that contains the project files.
5. Start Android Studio.
6. In the **Welcome to Android Studio** window, click **Open an existing Android Studio project**.
7. In the **Import Project** dialog, navigate to where the unzipped project folder is located.
8. Double-click on that project folder.
9. Wait for Android Studio to open the project.
10. Click the **Make Project** button to build the app.

## Customize
1. In `MainActivity.kt`, put your own website URL as the value of `WEBSITE` constant.
2. Replace default app icons with your own.

*Optional*: Change the value of `javaScriptEnabled` to `false` in `MainActivity.kt` if your website doesn't contain any JavaScript elements.

## ScreenShots
<img src="/screenshots/421814416_933224221576747_2243912789096801651_n.jpg" alt="screenshot" /> <img src="/screenshots/422058124_1050114512730649_8978524172455846166_n.jpg" alt="screenshot" />
