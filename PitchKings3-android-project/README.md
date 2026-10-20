# Pitch Kings - Android build

Upload ALL of these files to a GitHub repository (keep the folder layout):
  .github/workflows/build-apk.yml
  package.json
  capacitor.config.json
  www/index.html, www/sw.js, www/manifest.webmanifest, www/icon-192.png, www/icon-512.png

Then: Actions tab > Build Android APK > Run workflow. When it turns green, open the run, scroll to Artifacts,
download PitchKings-apk, unzip it and install app-debug.apk on your Android phone.
The recipe finds the project folder by itself, so it still works if the files end up inside a subfolder.
