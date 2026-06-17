# GitHub Pages Deployment Guide

## Your Presentation Link Will Be:
```
https://ks-bhatti.github.io/fraud-detection-presentation/
```

---

## STEP-BY-STEP DEPLOYMENT

### Step 1: Create a GitHub Repository (5 minutes)

1. Open https://github.com/new in your browser
2. Fill in the repository details:
   - **Repository name:** `fraud-detection-presentation`
   - **Description:** `Fraudulent Transaction Detection System - Parallel & Distributed Computing Project`
   - **Visibility:** Select **Public** (required for GitHub Pages)
   - **Initialize repository:** Leave unchecked

3. Click **Create repository**

---

### Step 2: Upload Files to GitHub (3 methods - choose one)

#### METHOD A: Using GitHub Web Interface (Easiest - No Git needed)

1. On your new repository page, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `.gitignore`

3. Type commit message: `Add fraud detection presentation`
4. Click **Commit changes**

✅ **Done with file upload!** Skip to Step 3.

---

#### METHOD B: Using Git Command Line (Recommended)

Open Terminal/Command Prompt and run:

```bash
# 1. Clone the repository to your computer
git clone https://github.com/ks-bhatti/fraud-detection-presentation.git
cd fraud-detection-presentation

# 2. Copy your presentation files here
# (Copy index.html, README.md, .gitignore to this folder)

# 3. Stage files for commit
git add index.html README.md .gitignore

# 4. Create a commit
git commit -m "Add fraud detection presentation"

# 5. Push to GitHub
git push -u origin main
```

✅ **Files uploaded!** Skip to Step 3.

---

#### METHOD C: Using GitHub Desktop (Visual Interface)

1. Download GitHub Desktop: https://desktop.github.com/
2. Sign in with your GitHub account
3. Click **Create a New Repository**
   - Name: `fraud-detection-presentation`
   - Check "Initialize with README"
4. Click **Create Repository**
5. In Finder/Explorer, copy `index.html` and `.gitignore` to the repository folder
6. In GitHub Desktop:
   - You'll see the changes
   - Type summary: "Add fraud detection presentation"
   - Click **Commit to main**
   - Click **Push origin**

✅ **Files uploaded!** Skip to Step 3.

---

### Step 3: Enable GitHub Pages (2 minutes)

1. Go to your repository: https://github.com/ks-bhatti/fraud-detection-presentation
2. Click the **Settings** tab (gear icon, top right)
3. On the left sidebar, click **Pages**
4. Under "Source":
   - Select **Deploy from a branch**
   - Branch: **main** (or **master** if that's your default)
   - Folder: **/root** (default)
5. Click **Save**

You'll see a message: "Your site is live at https://ks-bhatti.github.io/fraud-detection-presentation/"

⏳ **Wait 1-2 minutes** for GitHub Pages to build your site.

---

### Step 4: Verify Your Presentation (1 minute)

1. Open https://ks-bhatti.github.io/fraud-detection-presentation/ in your browser
2. You should see:
   - Title: "Fraudulent Transaction Detection System"
   - Dark background with cyan accents
   - 13 slides total

3. Navigate with:
   - **Arrow keys** to move between slides
   - **Space** to advance
   - **ESC** for slide overview
   - **F** for fullscreen

✅ **Success!** Your presentation is live!

---

## Quick Reference: Files You Need

| File | Purpose |
|------|---------|
| `index.html` | **Required** - The complete presentation (all 13 slides) |
| `README.md` | Optional but recommended - Documentation |
| `.gitignore` | Optional but recommended - Tells Git which files to ignore |

---

## Sharing Your Presentation

**Share this link:**
```
https://ks-bhatti.github.io/fraud-detection-presentation/
```

Anyone can view it in:
- Desktop browsers
- Mobile/tablet browsers
- No installation needed
- No login required

---

## Making Changes After Deployment

If you need to update slides:

### Using Git:
```bash
# Edit index.html locally in any text editor

# Then push changes:
git add index.html
git commit -m "Update presentation content"
git push

# Live in 1-2 minutes
```

### Using GitHub Web:
1. Go to your repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make changes
5. Scroll down, click **Commit changes**

---

## Troubleshooting

**Problem: Site not showing up?**
- Solution: Wait 2-3 minutes for GitHub Pages to build
- Solution: Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)
- Solution: Check Settings > Pages - ensure it says "Your site is live at..."

**Problem: Getting a 404 error?**
- Solution: Make sure you made the repository **Public** (not Private)
- Solution: Verify the URL is: `https://ks-bhatti.github.io/fraud-detection-presentation/`

**Problem: Slides look broken or styling is off?**
- Solution: This usually means the CDN link for Reveal.js failed
- Solution: Try a different browser or check internet connection
- Solution: Open in Incognito/Private mode

**Problem: Can't upload files?**
- Solution: Make sure repository is **Public**
- Solution: Use GitHub Desktop or Web interface instead of command line

---

## What Happens Next?

1. **Tomorrow's Presentation:** Open the link on projector/screen and present
2. **After Presentation:** Leave it live - it's a permanent record of your project
3. **Share with Team:** Send the link to team members, advisors, or classmates
4. **Update Anytime:** You can edit slides anytime and changes go live instantly

---

## Need Help?

- **GitHub Help:** https://docs.github.com/en/pages
- **Reveal.js Docs:** https://revealjs.com/
- **Keyboard Controls:** Press **?** during presentation

---

## Summary: Total Time = ~10 Minutes

1. Create repo - 5 minutes
2. Upload files - 3 minutes
3. Enable GitHub Pages - 2 minutes
4. Wait for deployment - 1-2 minutes
5. Verify - 1 minute

**That's it!** Your presentation is ready for tomorrow! 🚀
