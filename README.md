# Suraj Kure Portfolio

This is a complete static portfolio website for Suraj Kure, inspired by the reference portfolio structure. It includes Home, About, Skills, Projects, Experience, and Contact sections. The certification section has been skipped.

## Files

- `index.html` - page structure and content
- `styles.css` - responsive design, dark/light theme, layout, and animations
- `script.js` - theme toggle, mobile menu, reveal animation, and contact form mail link
- `assets/suraj-developer-visual.svg` - local hero visual

## How to Run in VS Code

1. Open VS Code.
2. Click `File > Open Folder`.
3. Select this folder:

```text
C:\Users\DELL\Documents\Codex\2026-05-10\https-www-rakeshgupta-co-in
```

4. Open `index.html`.
5. Run it using one of these options:

Option A: Use Live Server

1. Install the VS Code extension named `Live Server`.
2. Right-click `index.html`.
3. Click `Open with Live Server`.
4. Your browser will open the portfolio.

Option B: Use Python local server

1. Open the VS Code terminal with `Terminal > New Terminal`.
2. Run:

```powershell
python -m http.server 8000
```

3. Open this URL in your browser:

```text
http://localhost:8000
```

Option C: Open directly

Double-click `index.html`. This works because the site has no build step.

## What to Edit Before Publishing

In `index.html`, update these placeholder links:

- `surajkure@example.com`
- `GitHub`
- `LinkedIn`
- project `View` links

In `script.js`, update this line with your real email:

```js
const contactEmail = "surajkure@example.com";
```

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Go to `Settings > Pages`.
4. Select your main branch and root folder.
5. Save, then open the GitHub Pages link.
"# portfolio" 
