# Ayoub ER RKHIS · Data Engineering Portfolio

Modern, single-page portfolio tailored for showcasing data engineering, streaming pipelines, and applied AI experience. Designed for easy deployment on GitHub Pages.

## ✨ Highlights
- Hero banner with quick contact links and CTA buttons.
- Experience timeline emphasizing data platform impact with links to live projects.
- Highlighted open-source project (`vertex-batch`) and skills grouped by platform, development, storage, and automation tooling.
- Responsive, dark-mode friendly design using glassmorphism cards and gradient accents.

## 🗂️ Structure
- `index.html` — semantic HTML layout for the entire site.
- `styles.css` — custom styles, responsive tweaks, and animation fallbacks.
- `ayoub-errkhis-resume.md` — original resume source used to craft the site copy.

## 🚀 Local Preview
Open `index.html` directly in your browser or use any static server:

```bash
bash -lc "python -m http.server"
```

Then visit `http://localhost:8000`.

## 🌐 Deploying to GitHub Pages
1. Push `index.html`, `styles.css`, and this `README.md` to your GitHub repository.
2. In GitHub, navigate to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch (e.g., `main`) and the `/ (root)` folder, then save.
5. Wait for the build to complete and verify the published site URL.

## 🧩 Customization Tips
- Update contact links in the hero section (`index.html`) to add calendly, resume PDF, etc.
- Extend the skills grid by adding more `<span class="pill">Skill</span>` entries.
- Replace the highlighted project with new case studies by duplicating the `.project` block.
- Adjust theming via CSS variables defined at the top of `styles.css`.

## 📄 Licensing
You are free to reuse and adapt this portfolio for personal purposes. Consider crediting if you share derivatives publicly.
