# EL Field PWA — Demo Deployment

Quick deployment to GitHub Pages for phone demo.
Total time: ~5 minutes.

## Steps

### 1. Create a GitHub repository

Go to https://github.com/new

- Repository name: `el-field-pwa`
- Visibility: Private (or Public if fine)
- Do NOT initialize with README
- Click "Create repository"

### 2. Upload the files

On the empty repository page, click "uploading an existing file"

Drag and drop all four files:
  - index.html
  - manifest.json
  - sw.js
  - icon-192.png
  - icon-512.png

Commit message: "Initial PWA demo"
Click "Commit changes"

### 3. Enable GitHub Pages

Go to Settings → Pages (left sidebar)

- Source: "Deploy from a branch"
- Branch: main / (root)
- Click Save

Wait about 60 seconds.

### 4. Your URL

Your PWA will be live at:
  https://{your-github-username}.github.io/el-field-pwa/

### 5. Install on your phone

**iPhone (Safari):**
1. Open the URL in Safari
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap "Add"

The app icon will appear on your home screen and open
fullscreen without the Safari browser chrome.

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home Screen" or "Install app"

## Notes

- The URL must be HTTPS for PWA installation to work
  (GitHub Pages provides this automatically)
- After installing, the app works offline
  (service worker caches all files on first load)
- The demo uses hardcoded sample data —
  no backend connection required
