# Mert Savaş — Personal Landing Page

Personal link-in-bio page hosted on GitHub Pages. Dark aerospace aesthetic with animated flow field matching the metal business card.

## Before you go live — two things to update in index.html

1. **LinkedIn URL** — find this line and replace with your real handle:
   ```
   href="https://linkedin.com/in/YOUR-LINKEDIN-HANDLE"
   ```
   Also update the visible text below it:
   ```
   linkedin.com/in/your-handle
   ```

2. **CV link** — upload your CV PDF to Google Drive, set sharing to "Anyone with the link can view", copy the link, and replace:
   ```
   href="YOUR-CV-GOOGLE-DRIVE-LINK"
   ```
   Also update the subtitle line `PDF · Updated June 2026` whenever you update the file.

---

## How to deploy (5 minutes)

### Step 1 — Create the repository
- Go to github.com and create a new repository
- Name it exactly: `yourusername.github.io` (replace yourusername with your actual GitHub username)
- Set it to Public
- Do NOT initialise with a README (you already have one)

### Step 2 — Upload the files
Option A (no command line):
- Open the new repository on GitHub
- Click "Add file" → "Upload files"
- Drag both `index.html` and `README.md` into the window
- Click "Commit changes"

Option B (command line):
```bash
git init
git add .
git commit -m "initial"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
- Go to your repository → Settings → Pages
- Under "Source", select "Deploy from a branch"
- Branch: main, folder: / (root)
- Click Save

Your page will be live at `https://yourusername.github.io` within about 60 seconds.

---

## Updating your CV

When you have a new version of your CV:
1. Go to Google Drive
2. Right-click the old CV file → "Manage versions" → "Upload new version"
3. The share link stays exactly the same — no changes needed anywhere else

---

## Pointing your QR code here

Once the page is live at `yourusername.github.io`:
1. Go to kutt.it (free, no expiry)
2. Create a short link pointing to your GitHub Pages URL
3. Generate a QR code from that short link
4. Give the QR file to your card manufacturer

If you ever move the page or change platforms, just update the Kutt destination — the QR on your card never needs to change.
