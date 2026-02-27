# Canvas Monitor

![Version](https://img.shields.io/badge/version-1.0.0-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Made with](https://img.shields.io/badge/made%20with-HTML%2C%20CSS%2C%20JavaScript-blue)
![License](https://img.shields.io/badge/license-educational-lightgrey)

Canvas Monitor is a client-side simulation of browser focus-detection mechanisms commonly used in online assessment platforms.

It reproduces the same JavaScript signals typically used to detect when a user switches tabs, minimizes the browser, or changes window focus during an online exam.

---

## Features

- Real-time focus detection
- Timestamped event logging
- Local session persistence via `localStorage`
- Optional sound alerts
- Responsive Canvas-inspired UI

---

## Technical Details

This project relies exclusively on standard browser APIs:

- `document.visibilityState`
- `visibilitychange`
- `window.blur`
- `window.focus`
- `AudioContext` (optional alert system)

All logic runs entirely in the browser.  
No server-side components are used.

---

## Live Demo

https://fedesexxx.github.io/canbebeaten/

---

This project is intended for educational and experimental use.
