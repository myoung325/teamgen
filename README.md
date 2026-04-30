# 🍎 Offline Team Generator & Scorer

A lightweight, privacy-focused Progressive Web App (PWA) designed for teachers and event organizers. Quickly split a list of names into teams, select random groups, and track scores—all without an internet connection.

## ✨ Features

- **Dual Grouping Modes**:
  - **Sequential**: Splits your list into consecutive chunks (keeps your pre-planned order).
  - **Random**: Shuffles the list before assigning teams.
- **Smart Scoring System**: 
  - Enable/Disable scoring toggles.
  - Automatic ranking (1st, 2nd, 3rd, etc.) with support for ties.
  - Persistent points even when toggling scoring visibility.
- **Interactive UI**:
  - **Click-to-Rename**: Click any team name to give it a custom name.
  - **Team Selection**: Highlight random or sequential teams for "who goes next" scenarios.
- **PWA Optimized**: 
  - Installable on iOS, Android, and Desktop.
  - Works 100% offline via Service Workers.
  - Minimized header real-estate for maximum screen usage.

## 🚀 Quick Start

1. **Paste** your student list into the text area (one name per line).
2. **Set** the number of teams you need.
3. **Generate**: Use 'Sequential' to keep your list order or 'Random' for a shuffle.
4. **Scoring**: Tap 'Enable Team Scoring' to start a classroom competition.

## 🛠️ Installation (as a PWA)

- **Desktop (Chrome/Edge)**: Click the "Install" icon in the address bar.
- **iOS (Safari)**: Tap the 'Share' icon and select 'Add to Home Screen'.
- **Android (Chrome)**: Tap the three dots and select 'Install App'.

## 📂 Project Structure

- `index.html` — The entire app (HTML5, CSS3, Vanilla JS).
- `manifest.json` — PWA configuration and icons.
- `sw.js` — Service Worker for offline functionality.
- `icon-512.png` — App icon for home screen installation.

## 📝 Technical Notes

- **No Backend**: No data is ever sent to a server. Your student lists stay on your device.
- **Vanilla JS**: No frameworks used (no React/Vue), ensuring it stays fast even on older school hardware.
- **License**: MIT

---
*Created for teachers who need a fast, reliable way to manage classroom groups.*
