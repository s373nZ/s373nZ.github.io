# Se7enZ Landing Page

Personal landing page showcasing Bitcoin open source contributions.

## Live Site

🔗 **https://s373nz.github.io** (once deployed)

## Features

- Static HTML/CSS (no build step)
- Dark theme with Bitcoin orange accent
- Mobile responsive
- GPG key verification

## Deploy to GitHub Pages

1. Create a new repo named `s373nz.github.io` on GitHub
2. Push this code:
   ```bash
   cd ~/se7enz-landing
   git init
   git add .
   git commit -m "Initial landing page"
   git remote add origin git@github.com:s373nZ/s373nz.github.io.git
   git push -u origin main
   ```
3. GitHub Pages will auto-deploy from the main branch

## Local Development

```bash
python3 -m http.server 8888
# Open http://localhost:8888
```

## Structure

```
├── index.html   # Main page
├── style.css    # Styles
└── README.md    # This file
```
