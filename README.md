# markpedigo.github.io

This repository contains the source files for **markpedigo.github.io**, a static personal website hosted with GitHub Pages.

## 📁 Repository structure

- `index.html` — main landing page (loads `home.html` inside an iframe).
- `home.html` — primary homepage content.
- `publications.html` — publications page.
- `about.html`, `contact.html` — additional pages that exist in the repo but are not currently linked in the navigation menu.
- `blog/` — blog index (`blog.html`) and individual post folders (YYYY-MM-DD).
- `img/` — image assets used across the site.
- `style.css` — main site stylesheet.

## 🛠️ Editing the site

1. Update the relevant HTML file (e.g., `home.html`, `publications.html`, or a blog post in `blog/YYYY-MM-DD/`).
2. If you change navigation links (e.g., add an “About” or “Contact” link), edit `index.html`.

   Example (uncomment / add a `<li>` item in the nav list):

   ```html
   <!-- <li class="nav-item">
     <a class="nav-link" href="about.html" target="content_iframe">About</a>
   </li> -->
   ```

3. Preview locally by opening `index.html` in a browser.
4. Commit and push changes to this repository.

## 🚀 Deployment

This site is served via **GitHub Pages** from the `main` (or `master`) branch.

---

If you need help with updating styles or restructuring pages, just ask!