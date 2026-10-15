# 陶芸 · Zen Clay Catcher

> *A calm, minimalist HTML5 canvas web game inspired by traditional Japanese pottery aesthetics (Wabi-Sabi).*

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-7C9082?style=flat-square&logo=github)](https://suzuhisako.github.io/zen-clay-catcher/)
[![License: MIT](https://img.shields.io/badge/License-MIT-C87A5B?style=flat-square)](LICENSE)

---

## 🍵 About the Game

**Zen Clay Catcher** is a mobile-optimized, browser-based web game designed to offer a peaceful, meditative experience. Players slide or tap to steer a stoneware Tenmoku bowl, gathering soft earthen clay drifting down from above to shape traditional ceramics.

Rather than fast-paced pressure, the scoring and audio systems encourage a calm state of flow and rhythmic concentration (*Zanshin/残心*).

---

## ✨ Features

- **Wabi-Sabi Visual Aesthetic:** Clean Japanese palette featuring Terracotta, Celadon, Biscuit, Tenmoku, and Kintsugi Gold glazes with organic hand-kneaded clay shapes.
- **Mobile-First Design:** Optimized touch-friendly controls, protective vertical offsets for mobile system gestures, and edge-to-edge drop zones on narrow displays.
- **Pentatonic Audio Synthesis:** Built with the Web Audio API to play gentle, rising pentatonic tones and golden chimes as you maintain your rhythm.
- **Dynamic Difficulty:** Switch seamlessly between **Zen (寬)**, **Standard (正)**, and **Master (精)** modes on the fly or via the resting screen.
- **Local Score History (Makimono):** Automatically saves your 10 most recent practice sessions and personal best streak using browser `localStorage`.
- **Bilingual Interface:** Fully localized in English and Japanese.

---

## 📖 Scoring & Mindset

| Metric | Description |
| :--- | :--- |
| **Shaped (成形)** | Total clay collected. Standard Clay (+1), Tenmoku (+2), Kintsugi Gold (+5). |
| **Harmony (調和)** | Your unbroken streak of consecutive catches. Missing resets streak to 0. |
| **Peak (極)** | Your all-time highest Harmony streak saved on your local device. |

---

## 🚀 Live Demo

Play the live game directly in your browser:  
👉 **[https://suzuhisako.github.io/zen-clay-catcher/](https://suzuhisako.github.io/zen-clay-catcher/)**

---

## 🛠️ Technology Stack

- **Frontend:** HTML5 Canvas, CSS3 (Flexbox/CSS Variables/Media Queries), Vanilla JavaScript (ES6+).
- **Audio:** Native Web Audio API (Synthesized oscillators — no external audio assets required).
- **Deployment:** GitHub Pages & Google Cloud Run (Containerized via Docker/Nginx).

---

## 📂 Local Development

No complex setup or build steps required. Simply clone the repository and open `index.html` in your web browser:

```bash
# Clone the repository
git clone [https://github.com/suzuhisako/zen-clay-catcher.git](https://github.com/suzuhisako/zen-clay-catcher.git)

# Navigate to the project directory
cd zen-clay-catcher

# Open index.html in your browser or run via VS Code Live Server

## 📝 License
Distributed under the MIT License. See LICENSE for details.

## Embrace the rhythm of the wheel. 一期一会 (One time, one meeting).
