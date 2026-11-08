# 🪔 Diwali 2026 Interactive Greeting & Video Player

A responsive Diwali celebration web experience featuring animated diya lighting, interactive fireworks, personalized greetings, and seamless video playback.

## ✨ Features
- **Diya Lighting**: 5 traditional clay diyas ignite sequentially with warm, flickering flame animations.
- **Interactive Fireworks**: Canvas-based particle fireworks bursting on screen automatically and on every click/tap.
- **Personalized Greetings**: Custom greetings supporting URL parameters (e.g., `?name=Friend`).
- **Signature**: Default sender signature set to **Jaypal**.
- **Auto Video Clip Playback**: Automatically launches [diwali-clip.mp4](diwali-clip.mp4) right after the Diwali wishes complete (~6 seconds), with sound fallback handling.
- **Video Controls**: Includes custom Play/Pause, Seek bar, Mute/Unmute toggle, Fullscreen, Replay, and Return to Wishes buttons.

## 🚀 How to Run Locally

### Option 1: Direct File
Double click `index.html` to open in any web browser.

### Option 2: Local HTTP Server (Recommended)
```bash
python -m http.server 8000
```
Then visit:
- Default: `http://localhost:8000/`
- Personalized: `http://localhost:8000/?name=YourFriend`

## 🌐 Deploy to GitHub Pages
1. Go to repository **Settings** -> **Pages**.
2. Select **Deploy from a branch** -> **Branch: `main`** -> **Folder: `/ (root)`**.
3. Click **Save**.
4. Access your live website at:
   `https://jaycoll1999.github.io/Diwali-_2026/`
