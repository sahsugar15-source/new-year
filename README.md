Happy New Year — Shareable Web Card

Files
- newyear-card-final.html  (the animated card)
- song.mp3                 (place your audio file here, name exactly this)

Local testing (recommended first)
1. Copy your MP3 to this folder and rename it to `song.mp3` (or update the HTML `src` accordingly).
2. Start a simple HTTP server from PowerShell:

```powershell
cd "D:\Programming notes\python practice"
python -m http.server 8000
```

3. Find your PC local IP (PowerShell):

```powershell
ipconfig
```

4. On your phone (same Wi‑Fi) open:

```
http://<your-pc-ip>:8000/newyear-card-final.html
```

Notes: Mobile browsers block autoplay; the page shows a "Tap to Play Music & Start" button — your recipient should tap it to enable music.

Option B — Quick public hosting (Netlify drag-and-drop)
1. Zip this folder or leave files in a local folder.
2. Go to https://app.netlify.com and sign up / log in.
3. From the Netlify dashboard, click "Add new site" → "Deploy manually" → drag & drop the folder (or the two files) into the uploader.
4. Netlify will give you a public HTTPS link you can share. Open that link on mobile — the recipient will tap the play button to start music.

Alternative: Push these files to a GitHub repo and connect the repo to Netlify or Vercel for automated deploys.

If you want, I can:
- Rename the audio file and update the HTML to a different filename you prefer.
- Create a GitHub repo and prepare a commit for you to push, then give exact Netlify connect steps.

Enjoy — tell me which next step you want me to take.