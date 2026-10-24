# APK Player - GitHub Pages version

Open this site in a browser on any PC, even a low-spec PC. Nothing is installed on your PC. The PC only shows the screen.

## What this site does

- Drop an APK file: it is analyzed in your browser only (package, version, permissions, SHA-256, icon, file list, asset preview). No file is sent to this site's server, because GitHub Pages is static hosting.
- Web-app APKs (with an index.html under assets/): they actually play in the player on this page.
- Native APKs: a browser cannot run native Android code directly, and an iPhone cannot install an APK at all. For real native play, use the Cloud Android section on the page:
  - Appetize: create a free account, paste your API token into the page (stored only in your browser's localStorage), upload the APK, and stream the cloud Android screen. Free plan limits apply (check Appetize pricing).
  - ApkOnline: no signup, open it in a new tab and upload the APK there.

## How to publish on GitHub Pages

1. This repository is public with `index.html` at the root.
2. GitHub > Settings > Pages > Build and deployment > Source: Deploy from a branch, Branch: main, Folder: / (root).
3. After a minute, the site is at `https://<username>.github.io/apk-player/`.

## Privacy note

Local analysis never leaves your browser. Cloud play is different: when you use Appetize, the APK is sent to Appetize's servers. Do not upload private or paid apps you do not own.
