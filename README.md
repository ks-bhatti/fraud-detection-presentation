# Fraudulent Transaction Detection System - Web Presentation

A professional web-based presentation of the Parallel & Distributed Computing project on fraudulent transaction detection using Apache Spark.

**Live Presentation:** https://ks-bhatti.github.io/fraud-detection-presentation

## What's Included

- **index.html** - Complete presentation with all 13 slides using Reveal.js
- **Dark Modern Professional Theme** - Cyan/teal accent colors on dark background
- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Keyboard Navigation** - Arrow keys to navigate, Space to advance, ESC for overview

## Features

- 13 professionally designed slides
- Smooth fade transitions between slides
- Stat boxes and rule justification cards
- Technology stack showcase
- Results and evaluation metrics
- Cross-group portability section
- Conclusion and thank you slide

## How to Use Locally

### Option 1: Open in Browser (Simplest)
1. Download `index.html` to your computer
2. Double-click the file to open in your default browser
3. Use arrow keys to navigate slides

### Option 2: Serve Locally (Python)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open `http://localhost:8000` in your browser.

### Option 3: Serve Locally (Node.js)
```bash
npx http-server
```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **→ / ↓** | Next slide |
| **← / ↑** | Previous slide |
| **Space** | Advance |
| **ESC** | Slide overview |
| **F** | Toggle fullscreen |
| **S** | Speaker notes |
| **B** | Blackout screen |

## Deployment to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `fraud-detection-presentation`
3. Description: `Parallel & Distributed Computing Project Presentation`
4. Select **Public** (required for GitHub Pages)
5. Click **Create repository**

### Step 2: Clone & Add Files

```bash
# Clone your new repository
git clone https://github.com/ks-bhatti/fraud-detection-presentation.git
cd fraud-detection-presentation

# Copy the presentation file
cp index.html .

# Create .gitignore
echo "# OS files
.DS_Store
Thumbs.db
*.swp
*.swo
*~

# IDE files
.vscode/
.idea/
*.sublime-project
*.sublime-workspace

# Node modules (if using build tools)
node_modules/
dist/

# Build artifacts
*.map
" > .gitignore

# Stage and commit
git add index.html .gitignore
git commit -m "Add fraud detection presentation"

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository: https://github.com/ks-bhatti/fraud-detection-presentation
2. Click **Settings** (gear icon)
3. Scroll down to **Pages** section
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/(root)** folder
6. Click **Save**

### Step 4: Verify Deployment

Your presentation will be live at:
```
https://ks-bhatti.github.io/fraud-detection-presentation/
```

It may take 1-2 minutes for GitHub Pages to build and deploy. Refresh the page if you don't see it immediately.

## Updating the Presentation

If you need to make changes:

```bash
# Edit index.html locally
# Then push to GitHub:
git add index.html
git commit -m "Update presentation slides"
git push

# Changes will be live within 1-2 minutes
```

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Responsive

## Presentation Content

### Slides Included

1. **Title Slide** - Project name, university, advisor, team members
2. **Problem Statement** - Why fraud detection matters
3. **Dataset & Imbalance** - 284,807 transactions, 492 frauds (0.173% rate)
4. **Fraud Detection Rules** - 4 detection rules explained
5. **Rule Justification** - Why each rule works
6. **Technology Stack** - Spark, PySpark, SQL, Java, Pandas, Matplotlib, Seaborn
7. **Processing Pipeline** - 6-step data pipeline
8. **System Screens (1)** - Dashboard visualization
9. **System Screens (2)** - Interactive exploration
10. **Visualization Charts** - Performance analysis
11. **Results & Evaluation** - Metrics and performance
12. **Cross-Group Portability** - Testing with external data
13. **Conclusion** - Thank you & discussion

## Customization

### Change Colors
Edit the CSS in `index.html` to change the accent color:
```css
/* Current: Cyan (#00d4ff) */
color: #00d4ff;

/* Alternatives:
   Green: #00ff88
   Purple: #bb86fc
   Orange: #ffb347
   Red: #ff6b6b
*/
```

### Change Theme
Replace the theme line in the `<head>`:
```html
<!-- Current theme -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.5.0/theme/black.min.css">

<!-- Other options:
     white.min.css
     league.min.css
     sky.min.css
     serif.min.css
     blood.min.css
     moon.min.css
-->
```

### Add Speaker Notes
Add notes to any slide:
```html
<section>
    <h2>Slide Title</h2>
    <p>Slide content</p>
    <aside class="notes">
        Speaker notes go here - press 'S' during presentation
    </aside>
</section>
```

## Technical Details

- **Framework:** Reveal.js 4.5.0 (via CDN)
- **No Build Tools Required** - Pure HTML/CSS/JavaScript
- **No Dependencies** - Everything loaded from CDN
- **Open Source** - MIT License (Reveal.js)

## File Structure

```
fraud-detection-presentation/
├── index.html          # Main presentation file
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── (optional) assets/  # Folder for images/videos if added later
```

## Troubleshooting

**Presentation doesn't appear on GitHub Pages?**
- Wait 1-2 minutes for deployment
- Check Settings > Pages to ensure it's enabled
- Verify you pushed to the `main` branch
- Try hard-refreshing (Ctrl+Shift+R or Cmd+Shift+R)

**Slides look broken?**
- Check that you're using a modern browser
- Ensure you have internet connection (CDN resources)
- Try opening in incognito/private mode

**Want to share just the link?**
- Share this link with your team: https://ks-bhatti.github.io/fraud-detection-presentation/
- No installation needed - works in any browser

## Support

For issues with Reveal.js: https://revealjs.com/
For GitHub Pages help: https://docs.github.com/en/pages

---

**Ready to present!** Good luck with your project presentation! 🚀
