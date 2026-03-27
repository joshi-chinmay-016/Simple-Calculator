# 🧮 Calculator

A sleek, minimalist calculator built with **vanilla HTML, CSS, and JavaScript** — featuring a glassmorphism design, animated background, and smooth micro-interactions.

🔗 **Live Demo:** [spectacular-marzipan-c16ca8.netlify.app](https://spectacular-marzipan-c16ca8.netlify.app/)

---

## ✨ Features

- ➕ Basic arithmetic: addition, subtraction, multiplication, division
- ✂️ Percentage (`%`) support
- ⌫ DEL key to delete last character
- 🔄 AC to clear all
- 💧 Glassmorphism card with animated background orbs
- 🎨 Hover lift & press animations on every button
- 📱 Responsive centered layout
- ♿ Accessible — `aria` labels and `readonly` input

---

## 📁 Project Structure

```
calculator/
├── index.html   # Application markup
├── style.css    # Glassmorphism styles & animations
└── script.js    # Button event handlers & eval logic
```

---

## 🚀 How to Deploy

This is a **pure static site** — no build step, no dependencies, no server required.

### Option 1 — Open Locally (Quickest)

Just double-click `index.html` in File Explorer. It opens directly in your browser.

### Option 2 — GitHub Pages (Free Hosting)

1. Create a new repository on [GitHub](https://github.com/new).
2. Push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/calculator.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo.
4. Under **Source**, select `main` branch and click **Save**.
5. Your calculator will be live at:
   ```
   https://<your-username>.github.io/calculator/
   ```

### Option 3 — Netlify Drop (Instant, No Account Needed)

1. Go to [netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop your `calculator/` folder onto the page.
3. Netlify instantly generates a public URL — done!

### Option 4 — Vercel CLI

```bash
npm i -g vercel
vercel --yes
```
Follow the prompts — your site will be deployed in seconds.

### Option 5 — VS Code Live Server (Local Dev)

1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
2. Right-click `index.html` → **Open with Live Server**.
3. The calculator opens at `http://127.0.0.1:5500/`.

---

## 🛠️ Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Markup     | HTML5               |
| Styles     | Vanilla CSS3        |
| Logic      | Vanilla JavaScript  |
| Fonts      | Google Fonts — Inter|

---

## 📸 Preview

🌐 **Live:** [https://spectacular-marzipan-c16ca8.netlify.app/](https://spectacular-marzipan-c16ca8.netlify.app/)

Or open `index.html` locally in any modern browser to see the glassmorphism design with animated background orbs and smooth button animations.

---

## 📄 License

MIT — free to use, modify, and distribute.
