# Sebastian Kremis — Personal Blog-style Page

This repository contains a small, blog-style personal website for Sebastian Kremis. The page is built with static HTML and CSS and presents an AI-generated assessment of Sebastian’s strengths, skills, education, and career highlights based on his CV.

Features
- Blog-style landing article that summarizes professional strengths and interests (AI-generated assessment)
- Sidebar with skills, experience highlights, education, and certifications (links to certificate verification pages)
- Social links: GitHub and LinkedIn in the header (no email address shown on the public page)
- Clean, responsive layout (styles in `style.css`)

Files
- `index.html` — Main page containing content and structure
- `style.css` — Stylesheet used by the page
- `CV Sebastian Kremis EN.pdf` — CV (used as source for content)

Preview locally
You can preview the site in a browser by opening `index.html` directly, or using a simple HTTP server.

Using Python (PowerShell / Terminal):

```powershell
# From the project directory:
python -m http.server 8000
# Open http://localhost:8000 in your browser
```

Using VS Code: open the project folder and use the Live Server extension for a live preview.

Edit or customize
- Edit `index.html` to update content or add new articles.
- Modify `style.css` to change layout, colors, or fonts.

Acknowledgements
- The content and site were created and improved with assistance from GitHub Copilot (credit added to the footer).

License
- Add a LICENSE file if this site should have a specific license.
