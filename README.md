# 🐾 Tamaholly Project

Interactive Virtual Pet & Smartwatch Simulation for the **Waveshare ESP32-S3 1.75" AMOLED Round Touch Display Development Board (466×466 Circular AMOLED, CO5300 QSPI, CST9217 Touch)**.

## ✨ Features
- **3 Swipeable Views (CST9217 Touch Simulation)**:
  - **View 0 (Right Swipe)**: Smartwatch Watchface with digital Clock, Date & configurable Alarm (`RTC DS3231`).
  - **View 1 (Center / Home)**: Realistic Video Holly (Puppy) with AMOLED Ring-Buttons, center petting touch trigger, automatic sleep/wake loops, tap, wink & bark actions.
  - **View 2 (Left Swipe)**: Classic 1996 Retro Tamagotchi LCD Dot-Matrix mode with animated 16×16 pixel puppy, heart status meters, and retro action toolbar (Feed, Play, Light/Sleep, Clean).
- **Physical ESP32-S3 Board Mockup**: Round CNC casing, digital dual microphones (ES7210), BOOT & PWR buttons, USB-C port, and status badges.

## 🚀 Getting Started
Open `index.html` directly in a browser or serve via any static file server:
```bash
python -m http.server 8787
```
Then navigate to `http://127.0.0.1:8787/index.html`.
