# 🌙 Zain's Universe

> A premium cosmic personal finance app, memory keeper, and life companion — built for Zain Akram, guided by the moon.

## Deploy to GitHub Pages

1. Push this entire folder to a GitHub repo
2. Go to **Settings → Pages → Source → `main` branch / root**
3. Your app will be live at `https://yourusername.github.io/zains-universe/`

## Add to Home Screen (PWA)

**iPhone (Safari):** Tap **Share** → **Add to Home Screen**  
**Android (Chrome):** Tap **⋮ menu** → **Add to Home Screen** / **Install App**

## Default PIN

`1410` — change it inside Settings after first login.

## Features

- 🌙 Real moon phase with daily message
- ♏ Scorpio daily horoscope with energy meters
- 💰 Real-time balance (income − expenses)
- 🧾 Receipt scanner with OCR (Tesseract.js)
- 📖 Full transaction history with search
- 🏰 Empire Plans (goals with progress bars)
- 📸 Memories with anniversary notifications
- 🎂 Birthday system (5 Nov 2006)
- 🏆 Achievements engine
- ⭐ Shooting star easter egg / wish maker
- 🎨 5 themes + auto-theme by balance
- 🔒 PIN lock screen with cinematic intro
- 📜 Yearly statements + PDF export
- 👁️ Privacy mode (hides all amounts)
- 📱 PWA — installs like a native app
- 🌐 100% offline after first load

## Project Structure

```
zains-universe/
├── index.html          ← main shell
├── manifest.json       ← PWA manifest
├── service-worker.js   ← offline caching
├── css/
│   └── main.css        ← all styles + themes
├── js/
│   ├── data.js         ← state, storage, finance, moon, scorpio
│   ├── ui.js           ← all render functions + CRUD modals
│   ├── receipt.js      ← OCR receipt scanner
│   └── app.js          ← cinematic intro, lock, FAB, PWA, init
└── assets/
    ├── icon-192.png
    └── icon-512.png
```
