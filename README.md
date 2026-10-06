# ಭಗವದ್ಗೀತಾ ಪಯಣ · Bhagavad Gita Journey

A simple, divine-feeling website for learning the Bhagavad Gita one verse at a time — chant in Kannada, simple meaning in Kannada and English, and a life lesson from each shloka.

## What's inside
- `index.html` — landing page + the 18-chapter journey path
- `shloka.html` — the verse template (reads from `data.js` based on `?v=` in the URL)
- `data.js` — all verse content in one place
- `style.css` — the whole design system

Right now the site carries **18 verses — one essence-verse per chapter**, so you can experience the full arc of the Gita without wading through all 700 shlokas at once. It's built to grow: to add a verse, copy one object in `data.js`, fill in the same fields, and add it to the array in the order you want it to appear. The site will pick it up automatically — no other code changes needed.

## How to host this on GitHub Pages
1. Create a new GitHub repository (e.g. `bhagavad-gita-journey`).
2. Upload all the files in this folder to the repo (`index.html`, `shloka.html`, `style.css`, `data.js`, `README.md`) — keep them at the root, not in a subfolder.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. GitHub will give you a URL like `https://yourusername.github.io/bhagavad-gita-journey/` within a minute or two.

No build step, no dependencies to install — it's plain HTML/CSS/JS.

## A note on the content
The Sanskrit shlokas and their Kannada-script chant are drawn from the well-known, standard verses of the Gita. The meanings, explanations and life-lesson notes are written simply and conversationally, in the spirit of helping a beginner connect with the verse — they are not a substitute for a scholarly commentary. If you plan to share this widely or use it in a classroom/temple setting, it's worth having a Kannada-fluent reader proofread the chant transliteration and meanings against a trusted printed edition before publishing.
