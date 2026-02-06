# How to Generate Your OG Card Image

## Option 1: Automated (Recommended)

Install Puppeteer and run the script:

```bash
npm install puppeteer
node generate-og-image.js
```

This will create `og-image.png` at exactly 1200x630px with 2x resolution for crisp display.

## Option 2: Manual Screenshot

1. **Open `og-card.html` in your browser** (already opened)

2. **Take a screenshot at exactly 1200×630px**:

   **Chrome DevTools Method:**
   - Open DevTools (F12 or Cmd+Option+I)
   - Toggle device toolbar (Cmd+Shift+M or Ctrl+Shift+M)
   - Set dimensions to: **1200 × 630**
   - Click the three dots menu → "Capture screenshot"
   - Save as `og-image.png`

   **Firefox DevTools Method:**
   - Open DevTools (F12)
   - Click the responsive design mode icon
   - Set to 1200 × 630
   - Take screenshot (Cmd+Shift+S on Mac)

   **macOS Screenshot Tool:**
   - Press Cmd+Shift+4
   - Press Spacebar to capture specific window
   - Click on the browser window with og-card.html

3. **Crop/resize** the screenshot to exactly 1200×630px if needed using:
   - Preview (built-in Mac app)
   - Any image editor

4. **Save as** `og-image.png` or `og-image.jpg` in the Portfolio directory

## After Creating the Image

The HTML is already updated to reference `/og-image.jpg`. Once you have the image:

1. Rename your file to `og-image.jpg` (or update the HTML to use `.png`)
2. Place it in the Portfolio root directory
3. Commit and push:
   ```bash
   git add og-image.jpg og-card.html
   git commit -m "Add OG card image"
   git push
   ```

## Preview Your Card

After deployment, test the preview:
- **Twitter**: https://cards-dev.twitter.com/validator
- **LinkedIn**: https://www.linkedin.com/post-inspector/
- **Facebook**: https://developers.facebook.com/tools/debug/

Just paste: `https://hsinghplay.usa.dev/`
