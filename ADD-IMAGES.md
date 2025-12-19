# How to Add Project Screenshots

Your portfolio is now set up to display background images for your top 4 featured projects!

## Required Screenshots

You need to add 4 screenshot images to this folder:

1. **michelle-portfolio.jpg** - Screenshot of michelletrendsetter.com
2. **travel-site.jpg** - Screenshot of your travel recommendation website
3. **mvp-painting.jpg** - Screenshot of MVP Painting website
4. **oakland-macomb.jpg** - Screenshot of Oakland Macomb landing page

## How to Take Screenshots

### Option 1: Using Windows Snipping Tool
1. Open the website in your browser
2. Press `Windows + Shift + S` to open Snipping Tool
3. Select "Window snip" or drag to capture the full page
4. Save as JPG with the exact filename above

### Option 2: Using Browser DevTools (Full Page)
1. Open the website in Chrome/Edge
2. Press `F12` to open DevTools
3. Press `Ctrl + Shift + P` to open command menu
4. Type "screenshot" and select "Capture full size screenshot"
5. Rename the file to match the names above

### Option 3: Use Online Screenshot Tool
- Go to: https://www.screenshotmachine.com/
- Enter your website URL
- Download and rename to the correct filename

## Image Specifications

- **Format**: JPG or PNG (JPG preferred for smaller file size)
- **Recommended size**: 1200px wide (will scale automatically)
- **Quality**: Medium to high quality
- **File names must match exactly** (case-sensitive)

## Where to Place Images

Save all 4 images in the **images** folder:
```
gitportfolio/
  ├── images/
  │   ├── michelle-portfolio.jpg  ← Add here
  │   ├── travel-site.jpg         ← Add here
  │   ├── mvp-painting.jpg        ← Add here
  │   └── oakland-macomb.jpg      ← Add here
  ├── index.html
  ├── script.js
  └── styles.css
```

## After Adding Images

1. Save the images in your gitportfolio folder
2. Run these commands:
   ```bash
   git add .
   git commit -m "Add project screenshots"
   git push origin main
   ```
3. Wait 1-2 minutes for GitHub Pages to rebuild
4. Visit your portfolio to see the images!

## Tips

- Use bright, clear screenshots that show your website's homepage or best features
- Avoid screenshots with personal information or private data
- Make sure the images are high quality but not too large (under 500KB each)
- If an image doesn't show, check that the filename matches exactly
