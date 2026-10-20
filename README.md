# TallyRoll

A calculator app with a paper tape, built as an installable web app (PWA). Open it on a phone, tap "Add to Home screen", and it works like a normal app, even offline.

## Features

- Addition, subtraction, multiplication and division, plus %, ± and backspace
- Chained calculations (2 + 3 × 4 is worked out one step at a time)
- Paper tape history, saved on the device
- Tap a tape line to bring its answer back to the display
- Share the tape as text
- 3D keys that press down, with vibration feedback
- Printing animation on the tape and a flip animation on the display
- Three themes (Graphite, Ocean, Cream), remembered next time
- Works offline and installs on the home screen

## Built with

- HTML, CSS and JavaScript (no frameworks)
- Web App Manifest and a Service Worker (for installing and working offline)
- localStorage (to save history and theme)

## Try it

Live version: https://YOUR-USERNAME.github.io/tallyroll/

On Android: open the link in Chrome, tap the three dots, then "Add to Home screen" or "Install app".

## Files

```
index.html            the whole app: screen, styles and calculator logic
manifest.webmanifest  app name, colours and icons
sw.js                 service worker for offline use

```

## Author

Your name, your class and your college or school.
