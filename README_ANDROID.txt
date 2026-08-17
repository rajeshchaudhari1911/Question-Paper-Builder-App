QUESTION PAPER BUILDER — INSTALLABLE ANDROID-STYLE PWA

This package is a Progressive Web App (PWA). It can be installed from Chrome on Android and appears like an app with a home-screen icon.

HOW TO DEPLOY:
1. Upload the contents of this folder to any HTTPS static web host.
2. Open the HTTPS URL in Chrome on Android.
3. Chrome will show an Install prompt, or use Chrome menu → Add to Home screen / Install app.

FILES:
- index.html: app
- manifest.json: Android/PWA app metadata
- sw.js: offline app shell/cache
- icon.svg: app icon

FEATURES:
- Upload searchable PDF question bank
- Search/filter questions
- Select questions manually
- Set marks
- Reorder selected questions
- Enter exam details
- Check total marks
- Print / Save as PDF
- Save selection locally in the browser

NOTE:
The PDF reader library is loaded from a CDN, so the first load requires internet. A scanned/image-only PDF needs OCR; this version does not yet include OCR.
