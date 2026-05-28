# Raimundo Couras — Portfolio Website

Personal portfolio website showcasing AI Engineering, RAG Pipelines, and Data Engineering expertise.

## 🚀 Live Demo

After deploying to GitHub Pages: `https://courasneto.github.io/`

## 📁 Structure

```
├── index.html      # Main portfolio page (single-file, all CSS included)
└── README.md       # This file
```

## 🛠️ How to Deploy on GitHub Pages

### Option 1: Replace current `couras` repo

1. Clone your existing repo:
   ```bash
   git clone https://github.com/courasneto/couras.git
   cd couras
   ```

2. Copy the `index.html` to the repo root

3. Push changes:
   ```bash
   git add .
   git commit -m "Add portfolio website"
   git push
   ```

4. Enable GitHub Pages:
   - Go to repo **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
   - Save

5. Access at: `https://courasneto.github.io/couras/`

### Option 2: Create `courasneto.github.io` repo (recommended)

1. Create new repo named exactly `courasneto.github.io`

2. Push the index.html:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/courasneto/courasneto.github.io.git
   git push -u origin main
   ```

3. Access at: `https://courasneto.github.io/`

## ✨ Features

- **Responsive Design** — Works on desktop, tablet, and mobile
- **Animated Sections** — AOS (Animate On Scroll) library
- **Single File** — All CSS included, no external dependencies (except fonts/icons)
- **Dark Sidebar** — Fixed navigation menu
- **Portfolio Filter** — Filter projects by category
- **Career Stats** — Animated number counters

## 🎨 Customization

### Change Colors

Edit the `:root` variables at the top of the `<style>` section:

```css
:root {
  --color-primary: #149ddd;      /* Main accent color */
  --color-secondary: #f4845f;    /* Secondary accent */
  --color-bg-dark: #040b14;      /* Dark background */
}
```

### Add Profile Photo

Replace the initials div with an image:

```html
<!-- Replace this: -->
<div class="initials">RC</div>

<!-- With this: -->
<img src="your-photo.jpg" alt="Profile">
```

### Add More Projects

Copy a `portfolio-item` block and modify the content.

## 📝 License

Free for personal use. Template inspired by [BootstrapMade](https://bootstrapmade.com/).

---

Built with ❤️ by Raimundo Couras
