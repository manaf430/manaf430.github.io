# Abdul Manaf — Developer & AI Engineer Portfolio

A modern, minimal, dark-themed personal portfolio website built with semantic HTML5, modern CSS3, and vanilla JavaScript. Designed specifically for **GitHub Pages**, styled with modern developer accents, glassmorphism surfaces, and an emphasis on Software Engineering and AI/ML Engineering.

**Live Website:** [https://manaf430.github.io/](https://manaf430.github.io/)

---

## ⚡ Features & Highlights

- **Modern Developer & AI Aesthetic:** Deep dark obsidian background, cyan/indigo accent gradients, monospace telemetry accents, and responsive card layouts.
- **Visual Centerpiece — Projects Section:**
  - Interactive category filter tabs (`All`, `AI & Agents`, `Cloud & Backend`, `Machine Learning`).
  - Featured flagship layout for **Enterprise Agentic RAG Assistant** and **TAVI (Final Year Project)**.
  - Responsive grid cards matching the clean density of modern software engineering portfolios with tech-stack tags and links.
- **8 Ordered Sections:**
  1. **Hero / Landing** — Status badge, title, terminal telemetry widget, metrics counter, social pills & CTA buttons.
  2. **About** — Bio and 4 core architectural focus pillars.
  3. **Skills** — Grouped into 5 tag/badge categories (AI/ML Engineering, Machine Learning, Software Engineering, Backend & Cloud, Frontend).
  4. **Experience** — Vertical timeline highlighting work at WorkfloX and IEEE leadership roles.
  5. **Projects** — 8 comprehensive project cards with tech tags, descriptions, and GitHub links.
  6. **Education** — BS in Computer Science (UCP, CGPA: 3.49) & FSc Pre-Engineering.
  7. **Certifications** — AWS Cloud Foundations, Advanced Python (NAVTTC), and Exploratory Data Analysis (IBM).
  8. **Contact & Footer** — 1-click email copy button with toast notification, phone, LinkedIn, location, and quick contact launcher.
- **Fast & Zero Dependencies:** Plain HTML/CSS/JS with zero build steps, instant load times, and lightweight self-contained SVG assets.
- **Responsive & Accessible:** Mobile-first layout, semantic HTML5, accessible ARIA attributes, and smooth scrolling navigation with scroll spy.
- **Theme Toggle:** Dark mode by default, with smooth light mode toggle and `localStorage` persistence.

---

## 📂 Project Structure

```text
manaf430.github.io/
├── index.html              # Main semantic HTML5 markup
├── css/
│   └── styles.css          # Design tokens, glassmorphism, responsive styles
├── js/
│   └── main.js             # Scroll spy, project filter, theme toggle, toast
├── assets/
│   ├── avatar.svg          # Stylized AI engineer monogram avatar
│   └── favicon.svg         # Modern gradient SVG favicon
└── README.md               # Documentation & deployment guide
```

---

## 🚀 Running Locally

Because this is a static site, you can view it directly without any build step:

### Option 1: Python Built-in Server (Recommended)
Open a terminal in the project root and run:
```bash
python -m http.server 8000
```
Then visit: `http://localhost:8000` in your web browser.

### Option 2: VS Code Live Server
1. Install the **Live Server** extension in VS Code.
2. Right-click `index.html` and select **"Open with Live Server"**.

### Option 3: Node.js `npx serve`
```bash
npx serve .
```

---

## 🌐 Deploying to GitHub Pages

Since this repository is named `manaf430.github.io`, it is a **GitHub User Site**.

1. Commit and push any changes to the `main` branch:
   ```bash
   git add .
   git commit -m "Update portfolio website"
   git push origin main
   ```
2. In your GitHub repository settings:
   - Navigate to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, verify it is set to **Deploy from a branch**.
   - Ensure Branch is set to `main` and folder is `/(root)`.
3. GitHub Actions will automatically deploy the site to:
   **[https://manaf430.github.io/](https://manaf430.github.io/)**

---

## ✏️ Customization

- **Updating Projects:** Edit or add `<article class="glass-surface project-card">` in the `#projects` section of `index.html`.
- **Updating Resume / Links:** Update the GitHub, LinkedIn, or PDF resume download links in `index.html`.
- **Changing Colors:** Modify CSS custom properties (e.g. `--primary`, `--accent-cyan`) in `:root` inside `css/styles.css`.
