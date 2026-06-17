# How to Upload Images to Your Website

## Quick Start Guide

Your website is now set up to display images! Follow these steps to add your images:

### Step 1: Prepare Your Images
- Create or find images you want to use
- Recommended image formats: **PNG** or **JPG**
- Recommended sizes:
  - Header logo: 300x300px
  - Service cards: 400x300px
  - General images: 1200x600px

### Step 2: Upload Images to GitHub
1. Go to your repository: `https://github.com/sofifurkaan99-creator/furkaansofi.github.io`
2. Navigate to the **Image** folder
3. Click **Add file** → **Upload files**
4. Select your images and upload them
5. Add a commit message like "Upload service images"
6. Click **Commit changes**

### Step 3: Image Files Needed
The website is configured to use these image files in the `Image/` folder:

| Image Name | Usage | Size |
|-----------|-------|------|
| `logo.png` | Header/Logo | 300x300px |
| `business-website.png` | Business Websites card | 400x300px |
| `ecommerce-store.png` | E-Commerce Stores card | 400x300px |
| `portfolio-website.png` | Portfolio Websites card | 400x300px |
| `landing-page.png` | Landing Pages card | 400x300px |
| `website-redesign.png` | Website Redesign card | 400x300px |
| `seo-optimization.png` | SEO Optimization card | 400x300px |

### Step 4: Customize Image Paths
If you want to use different image names or folders:
1. Edit `index.html`
2. Find lines with `src="Image/..."` 
3. Change the filename to match your uploaded image
4. Save and commit

### Example
If you upload a file named `my-logo.png`, change this line:
```html
<img src="Image/logo.png" alt="BrandOrbitX Logo" class="header-img">
```

To this:
```html
<img src="Image/my-logo.png" alt="BrandOrbitX Logo" class="header-img">
```

## Tips
- Keep image file names lowercase (e.g., `logo.png` not `Logo.PNG`)
- Use descriptive names for easy management
- Optimize images for web (compress them to reduce load time)
- Use consistent image dimensions for better visual alignment

## Need Help?
If an image doesn't appear:
1. Check that the filename matches exactly (including capitalization)
2. Make sure the image is in the `Image/` folder
3. Clear your browser cache and refresh
4. Check browser console for error messages (F12)

Happy uploading! 🚀
