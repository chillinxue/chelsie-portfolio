# Chelsie Lin — Portfolio

## What's inside
```
index.html                → homepage (hero, about, featured + selected work, background, contact)
style.css                 → all styling and the color system (forest green + citrus)
script.js                 → nav scroll behavior + mobile menu
resume.pdf                → your resume (already included — swap the file to update it)
projects/
  line-bank.html           → LINE Bank AI Chatbot
  shopbop.html              → Amazon Shopbop — Bop & Browse
  ascenzi.html               → Ascenzi & Associates
  library.html                → Madison Public Library
  mental-health.html           → AI Mental Health Research
  hanabi.html                   → HANABI Travel Planner
  stylish.html                   → STYLiSH E-commerce
```

## Deploy on GitHub Pages (free)
1. Create a new GitHub repo named `<your-username>.github.io` — this gives you the cleanest URL: `https://<your-username>.github.io`. (Any other repo name also works; the site just lives at `https://<username>.github.io/<repo-name>` instead.)
2. Upload every file and folder in this package to the repo root, keeping the `projects/` folder structure intact.
3. In the repo, go to **Settings → Pages**, set Source to the `main` branch and `/ (root)`, then save.
4. Your site is live within a minute or two at the URL from step 1.
5. Any time you edit a file and push again, the live site updates automatically within about a minute — no rebuild step.

## Photos
Your headshot (`assets/chelsie-photo.jpg`) is already wired into the homepage hero banner and the About section circle photo — that part is done.

The project case study pages still use placeholder boxes (a light icon on a tinted background) wherever a real screenshot should go, because I can't fetch or generate your actual product screenshots. To swap one in:
- Find the `<div class="case-img">...</div>` in a project's HTML file (or `<div class="case-hero__media">...</div>` near the top).
- Replace the whole `<div class="case-img">...</div>` with `<img class="case-img" src="assets/your-screenshot.jpg" alt="...">` — the same class handles sizing on an `<img>` tag too.
- Add your screenshots into the `assets/` folder (create subfolders if it gets crowded, e.g. `assets/line-bank/`); compress large images first so the site loads fast.

## Still to do
- Swap in real project screenshots (see above).
- Double check `resume.pdf` is your latest version before you deploy.
- Update the LinkedIn URL in the nav/contact section if it changes.

## Editing content later
Everything is plain HTML — open any file in a text editor (or ask Claude to edit it for you) and change the text directly. Layout, spacing and colors all come from `style.css`, so you never need to touch it just to update words.
