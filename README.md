# 🎬 Motion Reel '26 — Pure HTML/CSS/JS Motion Design

A cinematic motion-design reel built with **one single HTML file**.
No React. No build step. No `npm install`. Just open it in your browser.

**Scenes:** orbit intro · kinetic typography · reactive dot field · fluid metaball blob · 3D particle sphere · animated UI dashboard · type & brand · logo outro.

> Built with Claude by [@tech.by.itzwania](https://instagram.com/tech.by.itzwania). Pure Canvas + CSS + vanilla JavaScript.

---

## ⚡ Quick Start (30 seconds)

### Option 1 — Download ZIP (easiest, no Git needed)
1. Click the green **`Code`** button at the top of this page.
2. Click **`Download ZIP`**.
3. Right-click the ZIP → **Extract All**.
4. Open the extracted folder and **double-click `index.html`**.

It opens in your browser and the reel starts playing. That's it. ✅

### Option 2 — Clone with Git
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```
Then open `index.html` in your browser:

| OS      | Command            |
|---------|--------------------|
| Windows | `start index.html` |
| macOS   | `open index.html`  |
| Linux   | `xdg-open index.html` |

### Option 3 — Run on a local server (optional)
```bash
# Python
python -m http.server 8000
# or Node
npx serve .
```
Open **http://localhost:8000** in your browser.

---

## 🎮 Controls

| Input | Action |
|-------|--------|
| **Click** | Jump to the next scene |
| **Space** | Pause / resume |
| **← / →** | Previous / next scene |
| **S** | Slow motion |

---

## 🖥️ Tips for the best result
- Use **Chrome, Edge or Brave** on desktop (best Canvas performance).
- Press **F11** for fullscreen.
- Keep internet **on** the first time: the page loads the *Archivo Black* and *JetBrains Mono* fonts from Google Fonts. Offline it still works, using fallback fonts.
- Want to screen-record it for Reels/TikTok? Press **F12 → Ctrl+Shift+M** (device toolbar) to get a vertical frame, or use any screen recorder.

---

## 🛠️ Customize
Everything is in `index.html`:
- **Colors / fonts** → CSS at the top of the file.
- **Text** (e.g. "I MAKE THINGS MOVE", "CLAUDE") → search the file for the string and change it.
- **Scene order & timing** → find the scene list in the `<script>` section.

Edit with any editor (VS Code, Notepad++), save, and refresh the browser.

---

## 📁 Project structure
```
.
├── index.html   # the whole reel (HTML + CSS + JS)
└── README.md
```

## ❓ Troubleshooting
| Problem | Fix |
|---------|-----|
| Blank / black page | Use a modern browser; avoid very old browsers or in-app WhatsApp/Instagram viewers. |
| Fonts look different | You're offline, so fallback fonts are used. Connect to the internet once. |
| Laggy animation | Close other tabs, enable hardware acceleration in browser settings. |

## 🌐 Run it online without downloading (optional)
Enable **GitHub Pages**: *Settings → Pages → Deploy from branch → `main` / root → Save*.
Your reel will be live at `https://<your-username>.github.io/<your-repo>/`.

## 📄 License
MIT — free to use, modify and share. A credit/mention is appreciated 🙌

---

⭐ **Star this repo if you liked it, and follow [@tech.by.itzwania](https://instagram.com/tech.by.itzwania) on Instagram for more web-dev motion builds!**
