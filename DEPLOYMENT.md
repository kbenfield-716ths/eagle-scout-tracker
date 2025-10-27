# Quick Start Guide - GitHub Deployment

## Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name it `eagle-scout-tracker` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. Do NOT initialize with README (we already have one)
6. Click "Create repository"

## Step 2: Upload Your Files

### Option A: Using GitHub Web Interface (Easiest)

1. On your new repository page, click "uploading an existing file"
2. Drag and drop all these files:
   - `index.html`
   - `liam.html`
   - `annalise.html`
   - `README.md`
   - `.gitignore`
3. Click "Commit changes"

### Option B: Using Git Command Line

```bash
cd /path/to/your/files
git init
git add .
git commit -m "Initial commit - Eagle Scout Tracker"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/eagle-scout-tracker.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Click "Pages" in the left sidebar
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click "Save"
6. Wait 1-2 minutes for deployment

## Step 4: Access Your Site

Your tracker will be live at:
```
https://YOUR-USERNAME.github.io/eagle-scout-tracker/
```

## Adding Photos

Once deployed:
1. Open your tracker
2. Click the profile photo circle
3. Select a photo from your device
4. The photo will be saved in your browser

## Updating Content

To make changes:
1. Edit the files on your computer
2. Upload them to GitHub (replace existing files)
3. Changes will be live in 1-2 minutes

## Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for deployment status
- Make sure repository is Public

**Photos not saving?**
- Photos are stored in browser localStorage
- Clear cache if having issues
- Photos are per-device (not synced between devices)

**Progress not saving?**
- Make sure you click "Save Progress"
- Check browser console for errors (F12)
- Try a different browser

## Support

For issues or questions, create an issue on your GitHub repository.

---

**Enjoy tracking your Eagle Scout journey! 🦅**
