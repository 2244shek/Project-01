# Art InGene 🎨

> **Your one-stop hub for curated online tools** — for learning, development, creativity, resume building, projects, and more.

![Dark Mode UI](images/web_logo.png)

## ✨ About

Art InGene is a static website that aggregates the best free tools across multiple categories so you never have to hunt for them again. Built as a first solo web development project by **Abhishek Panigrahi** (B.Tech CSE — AI/ML, VIT Chennai).

---

## 📂 Project Structure

```
Project -01/
├── index.html          # Home — hero + category card grid
├── about.html          # About page — project timeline
├── projects.html       # College project helpers
├── resume.html         # Resume building tools
├── learn.html          # AI/ML, Data Science, Hacking, Coding
├── development.html    # Web Dev, AR/VR, No-Code tools
├── creator.html        # Creator tools (music, video, audio)
├── editor_tools.html   # Editing tools (PDF, image, video)
├── fellow_devs.html    # Developer profile page
├── css/
│   └── style.css       # Unified dark-mode design system
└── images/             # Logos and category icons
```

---

## 🎨 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (semantic) |
| Styling | Vanilla CSS (custom design system) |
| Fonts | [Inter + Space Grotesk](https://fonts.google.com/) via Google Fonts |
| Icons | Inline SVG |
| Build | None — zero build step required |

---

## 🚀 Running Locally

This is a plain static site. You need a local HTTP server to preview it (browsers block CSS loading over `file://`).

**Option 1 — VS Code Live Server** *(recommended)*
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
2. Right-click `index.html` → **Open with Live Server**

**Option 2 — npx http-server**
```bash
npx http-server . -p 5500 -o
```
Then open [http://localhost:5500](http://localhost:5500)

---

## 🗂 Tool Categories

| Category | Description |
|----------|-------------|
| 📁 Project Tools | College & personal project helpers |
| 📄 Resume Tools | Resume builders & vocabulary tools |
| 📚 Learning Tools | AI/ML, Data Science, Ethical Hacking, Coding |
| 💻 Developer's Tools | Web Dev, AR/VR, No-Code builders |
| 🎨 Creator's Tools | Music, video, audio, image tools |
| ✂️ Editing Tools | PDF, image, video editors |
| 🧑‍💻 Coder's Section | *(Coming Soon)* |

---

## 📸 Design

- **Theme**: Dark mode (`#080b12` background, `#00e5ff` cyan accent)
- **Responsive**: CSS Grid collapses gracefully on mobile, hamburger menu
- **Typography**: Space Grotesk (headings) + Inter (body)
- **Effects**: Glassmorphism navbar, card hover lift + glow, smooth transitions

---

## 🤝 Contributing

Found a great tool that should be listed? Feel free to open a PR or raise an issue!

1. Fork the repo
2. Add your tool to the relevant `.html` page using the `.tool-card` or `.tool-list-item` pattern in the existing code
3. Submit a pull request

---

## 📄 License

© 2022–2024 Art InGene. All rights reserved.
