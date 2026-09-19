# Jerusalem

Offline-first worship presentation web app for PrimeOS.

## Current build
- Bible and lyric starter libraries
- Live preview
- Separate projector/output window
- Clear / present controls
- LocalStorage persistence
- VGA workflow: open projector window, move it to the VGA display, fullscreen

## Important
The browser/PrimeOS display manager controls which physical monitor a popup window occupies. Jerusalem intentionally uses a clean output window so it can be moved to the VGA projector without exposing the operator controls.

## Run
Open `index.html` in a browser. For a more reliable local install, serve this folder with any local static web server or package it later as an Android/desktop application.
