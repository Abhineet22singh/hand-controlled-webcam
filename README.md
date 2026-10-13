# 🖐️ Hand-Controlled Webcam Reel

A **browser-based webcam app** controlled entirely by **hand gestures** — no installs needed! Built with [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) + WebRTC + Canvas API.

## 🎮 Live Demo

> Open `index.html` via a local server (see below) and allow webcam access.

---

## ✋ Gesture Controls

| Gesture | Action |
|---|---|
| ✊ **Fist** | 📸 Capture photo |
| ✋ **Open palm + swipe ←** | ◀ Previous filter |
| ✋ **Open palm + swipe →** | ▶ Next filter |
| ☝️ **Point finger UP** | 🔍 Zoom in |
| 👇 **Point finger DOWN** | 🔍 Zoom out |
| 🤏 **Pinch** | 🔍 Fine-tune zoom |
| ✌️ **Peace sign** | 🔄 Reset zoom to 1× |

---

## 🎨 Filters

Swipe through 8 real-time filters:
`Normal → Greyscale → Sepia → Invert → Warm → Cool → Vignette → Sketch`

---

## 🚀 Run Locally

### Option 1 — PowerShell (no install needed)
```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1
```
Then open **http://localhost:3000** in Chrome.

### Option 2 — Node.js
```bash
npx serve .
```

### Option 3 — Python
```bash
python -m http.server 3000
```

---

## 🛠️ Tech Stack

- **MediaPipe Hands** — real-time hand landmark detection (21 keypoints)
- **WebRTC** — browser webcam access
- **Canvas API** — pixel-level filter rendering + hand skeleton overlay
- **Pure HTML/CSS/JS** — zero frameworks, zero installs

---

## 📸 Screenshots

> Show your hand to the camera and control everything with gestures!

---

## 📄 License

MIT © [Abhineet22singh](https://github.com/Abhineet22singh)
