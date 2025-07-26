# 🌈 React Static Color Changer

A minimal React app that runs from a single `index.html` file and changes the background color every 5 seconds. No build tools, frameworks, or npm required — just open it in a browser or run it on a local server.

---

## 🚀 Features

- Written in pure React + JSX
- Uses CDN (React + Babel) — no build step needed
- Fully contained in one file: `index.html`
- Background color changes every 5 seconds
- Works offline after initial load (if cached)

---

## 🖥️ Preview

![Preview Screenshot](screenshot.png) <!-- Optional, if you add a screenshot -->

---

## 📁 File Structure

/react-static-color-changer
├── index.html
└── README.md

---

## 🔧 How to Run

### ✅ Option 1: Open Directly

Just double-click `index.html` or drag it into a browser.

> ⚠️ Make sure you are connected to the internet the first time (CDNs are used).

---

### ✅ Option 2: Run on a Local Server (Port 3000)

#### Using Python (Mac/Linux/Windows):

```bash
# Step 1: Open terminal in this directory
cd path/to/react-static-color-changer

# Step 2: Run the server on port 3000
python3 -m http.server 3000
