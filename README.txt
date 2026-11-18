Calculator PWA
==============
Files: index.html, manifest.json, sw.js, icon-*.png

1. Upload this whole folder to a free HTTPS host:
   - Netlify Drop: https://app.netlify.com/drop (drag the folder in)
   - or GitHub Pages / Cloudflare Pages
2. Open the site's URL on your phone.
3. Android (Chrome): menu > Install app.
   iPhone (Safari): Share > Add to Home Screen.

Test on a computer first: run "python3 -m http.server" in this folder
and open http://localhost:8000 (localhost counts as secure).
If you change files, bump CACHE in sw.js (calc-v1 -> calc-v2).
