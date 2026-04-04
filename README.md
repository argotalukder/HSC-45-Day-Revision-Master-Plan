# 📚 RevZone — HSC 45-Day Revision Master Plan

> A smart, interactive revision tracker for HSC 2026 Science students — built with pure HTML, CSS & JavaScript. No frameworks, no dependencies, just fast and focused.

🔗 **Live Site:** [https://revzone.vercel.app](https://revzone.vercel.app)

---

## ✨ Features

- **45-Day Structured Plan** — Full chapter-wise daily schedule for all Science subjects (Bengali, English, ICT, Physics, Chemistry, Math, Biology)
- **Progress Tracking** — Visual progress bar with done/left counters; your progress is auto-saved in the browser
- **Persistent Personal Link** — Each user gets a unique URL via `?uid=` query param so progress survives page refreshes and can be bookmarked
- **Study Timer (Pomodoro)** — Built-in countdown timer with 25m / 5m presets, custom duration input, and a 2-minute alarm that auto-stops
- **Subject & Week Filters** — Filter the plan by any subject or week with one click
- **Color-coded Subject Badges** — Each subject has a distinct color for fast visual scanning
- **QNA Suggestion 2.0 Aligned** — Topics are curated based on the QNA HSC Suggestion book

---

## 📸 Preview

| Dashboard | Week View | Timer |
|-----------|-----------|-------|
| Progress bar + stats | Week-wise day cards | Pomodoro countdown |

---

## 🗂️ Project Structure

```
revzone/
│
├── index.html        # The entire app — single file (HTML + CSS + JS)
└── README.md
```

This is a **single-file web app** — everything lives inside `index.html` for simplicity and zero build steps.

---

## 🚀 Getting Started

### Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/revzone.git
   cd revzone
   ```

2. Open `index.html` in your browser:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Or just drag the file into any browser
   ```

No server, no `npm install`, no build process needed.

---

## 🌐 Deploy on Vercel

This site is deployed on [Vercel](https://vercel.com) as a static site.

To deploy your own copy:

1. Fork this repo
2. Go to [vercel.com](https://vercel.com) → **New Project** → Import your fork
3. Select **Framework Preset: Other** (it's just a static HTML file)
4. Click **Deploy** — done!

---

## 📖 Subjects Covered

| Subject | Days |
|---|---|
| বাংলা ১ম ও ২য় পত্র | Day 1–7 |
| English 1st & 2nd Paper | Day 8–14 |
| ICT + পদার্থ ১ম পত্র | Day 15–21 |
| পদার্থ ২য় + রসায়ন ১ম পত্র | Day 22–28 |
| রসায়ন ২য় + গণিত ১ম পত্র | Day 29–35 |
| গণিত ২য় + জীব ১ম পত্র | Day 36–42 |
| জীব ২য় পত্র + Grand Revision | Day 43–45 |

---

## 🛠️ Built With

- **HTML5** — Structure and content
- **CSS3** — Dark theme, responsive layout, animations
- **Vanilla JavaScript** — All logic: routing, localStorage, timer, filtering
- **No external libraries** — Zero dependencies, loads instantly

---

## 📦 Browser Support

Works in all modern browsers: Chrome, Firefox, Edge, Safari.  
Progress is stored in `localStorage` — so it works fully offline after the first load.

---

## 🤝 Contributing

Pull requests are welcome! If you want to:
- Add more subjects or fix topic listings
- Improve the UI or add new features
- Report a bug

Feel free to open an issue or submit a PR.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<p align="center">Made with ❤️ for HSC 2026 students · Powered by <strong>BrainArena</strong></p>
