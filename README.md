# Moobit 🌒

Moobit is a minimalist, beautifully designed Progressive Web App (PWA) built to help you take control of your daily routines and emotional well-being. Combining a habit tracker, mood logger, and comprehensive visual analytics into a clean dashboard, Moobit allows you to seamlessly monitor your progress over weeks, months, and an entire year.

## ✨ Key Features

* **Daily Logging:** Quickly record your overall mood (using expressive emojis ranging from Excellent to Terrible), check off completed habits, and jot down quick daily notes.
* **Custom Habit Management:** Add, track, and remove personalized habits tailored specifically to your lifestyle and goals.
* **Visual Trends & Analytics:** Gain insights at a glance with integrated Chart.js graphs tracking your mood trajectory, habit completion frequencies, and monthly mood breakdowns.
* **Activity Tracker & Highlights:** Review monthly performance with an interactive calendar view and summary highlights showing total days logged and average mood scores.
* **Yearly Heatmap & Scrollable Logs:** Visualize your whole year's emotional pattern through an annual heatmap and easily expand or collapse historical record tables.
* **100% Offline & PWA Ready:** Install Moobit directly onto your desktop or mobile device's home screen for fast, private, and secure local data tracking without needing an external server connection.

## 🚀 Tech Stack

* **HTML5 / CSS3:** Modern responsive layout utilizing CSS Grid, Flexbox, and sticky positioning.
* **JavaScript (Vanilla):** High-performance client-side logic with local storage persistence (`localStorage`).
* **Chart.js:** Dynamic, lightweight data visualization for trends and metrics.
* **PWA Standards:** Fully configured with a Web App Manifest (`manifest.json`) and Service Worker (`sw.js`) for offline caching and installation support.

## 📦 Project Structure

```text
moobit/
├── index.html       # Main application interface and script logic
├── manifest.json    # PWA configuration manifest
├── sw.js            # Service worker for offline asset caching
├── icon-192.png     # 192x192 PWA application icon
└── icon-512.png     # 512x512 PWA application icon
