# Nishant Sawardekar - Portfolio

Single-file portfolio site. Everything (styles, scripts, background image, music and resume PDF) is embedded in `index.html`, so no other files or folders are needed.

## Publish on GitHub Pages
1. Create a new public repository on GitHub, e.g. `portfolio` (or `ish1010n.github.io` for the root address).
2. Upload `index.html` (and this README if you like) to the top level of the repository.
3. Go to Settings > Pages, choose Source: Deploy from a branch, Branch: `main`, folder `/ (root)`, then Save.
4. After a minute or two the site is live at `https://ish1010n.github.io/portfolio/`.

## Notes
- Music starts after the visitor clicks "Enter portfolio" (browsers block sound before a click). The speaker button at the bottom-right mutes and unmutes it.
- Both "Download resume" buttons save `NishantS_Resume.pdf` from the embedded copy.
- Fonts load from Google Fonts; if blocked, standard fonts are used.
- After uploading a new version, hard-refresh with Ctrl+Shift+R (Cmd+Shift+R on a Mac).
