# Image Setup Instructions

## How to Add Your Images to the Presentation

The HTML dashboard is now configured to display your images. Follow these simple steps:

### Step 1: Save All Three Images

Save these images with these **exact filenames**:

1. **Your professional headshot** → Save as: `greg-photo.jpg` 
2. **RunMate Pro screenshot** → Save as: `runmate-pro-screenshot.png`
3. **SunUp screenshot** → Save as: `sunup-screenshot.png`

### Step 2: Place Files in the Same Folder

Put **all three image files** in the **same folder** as your `presentation-dashboard-v1.html` file:

```
📁 3. Mentor Session/
  ├── presentation-dashboard-v1.html
  ├── greg-photo.jpg               ← Save here (your headshot)
  ├── runmate-pro-screenshot.png   ← Save here (RunMate app)
  └── sunup-screenshot.png         ← Save here (SunUp app)
```

### Step 3: Open the Presentation

Double-click `presentation-dashboard-v1.html` to open it in your browser. Your screenshots will now appear in:

- **Intro Section** - Hero display with both apps
- **SunUp Section** - Two SunUp screenshots
- **RunMate Pro Section** - Two RunMate Pro screenshots

---

## Alternative: Use a Subfolder (Optional)

If you prefer to keep images organized in a subfolder:

1. Create a folder called `images` next to the HTML file
2. Place all three images inside the `images` folder
3. Update the HTML image sources to include `images/`:
   - Change: `src="greg-photo.jpg"`
   - To: `src="images/greg-photo.jpg"`
   - Do this for all three images

---

## Images Configured

The presentation currently expects these images:

✅ `greg-photo.jpg` - Your professional headshot in circular frame (Intro section)  
✅ `runmate-pro-screenshot.png` - Used in 3 locations (Intro + RunMate section)  
✅ `sunup-screenshot.png` - Used in 3 locations (Intro + SunUp section)

Once you save the images with these exact names in the same folder as the HTML file, they will display automatically!

---

**Need help?** Just let me know and I can adjust the image paths or filenames.

