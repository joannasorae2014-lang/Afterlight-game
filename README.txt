AFTERLIGHT phone app files

Files:
- index.html: your game, with app metadata and service-worker registration added
- manifest.webmanifest: Android/PWA app name, portrait orientation, colours and icons
- service-worker.js: caches the game shell for repeat/offline loading
- icons/: 192px and 512px app icons

Important:
1. Upload the contents of this folder to the ROOT of your website repository.
2. Keep the folders and filenames exactly as they are.
3. The Google Fonts import in the game may need internet; the game has fallback fonts.
4. Offline support starts after the game has first loaded online successfully.
5. This is the web-app preparation stage, not the APK yet.
