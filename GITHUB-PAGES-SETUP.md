# GitHub Pages Setup for GeoFlagster

Your landing page is ready! Now you need to enable GitHub Pages on your GitHub repository.

## ✅ What's Been Created

- **Landing Page**: `docs/index.html` - Professional, mobile-responsive landing page
- **Privacy Policy**: `docs/privacy-policy.html` - Your privacy policy in the docs folder
- **Styles**: `docs/css/styles.css` - Beautiful, modern CSS styling
- **Configuration**: `docs/_config.yml` - GitHub Pages configuration
- **Assets Folder**: `docs/assets/` - For screenshots and images
- **README**: `docs/README.md` - Instructions for updating content

## 🚀 Enable GitHub Pages (5 Minutes)

### Step 1: Push to GitHub
First, make sure your code is in a GitHub repository:
```bash
cd /Users/sdufoo/claude/geoflagster
git add .
git commit -m "Add GitHub Pages landing page and privacy policy"
git push origin main
```

### Step 2: Configure GitHub Pages
1. Go to your GitHub repository: `https://github.com/yourusername/geoflagster`
2. Click **Settings** (top right)
3. In the left sidebar, click **Pages** (under "Code and automation")
4. Under "Build and deployment":
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main` (or your default branch)
   - **Folder**: Select `/docs`
5. Click **Save**

### Step 3: Wait for Deployment
GitHub will automatically deploy your site. You'll see a green checkmark when it's ready.

Your site will be available at:
```
https://yourusername.github.io/geoflagster/
```

(Replace `yourusername` with your actual GitHub username)

## 📝 Important URLs for App Store Submission

Once deployed, use these URLs:

### Marketing URL
```
https://yourusername.github.io/geoflagster/
```

### Support URL
```
https://yourusername.github.io/geoflagster/
```
(Or use email: `sdufoo@gmail.com`)

### Privacy Policy URL
```
https://yourusername.github.io/geoflagster/privacy-policy.html
```

## 🎨 Next Steps

### 1. Replace Screenshots
Your landing page has placeholder screenshots. Replace them:
1. Save your app screenshots to `docs/assets/`
2. Update the image paths in `docs/index.html`

Example:
```html
<img src="assets/screenshot-1.png" alt="Game in Action">
```

### 2. Update App Store Links
Edit `docs/index.html` and find:
- `https://apps.apple.com/app/geoflagster` → Your App Store link
- `https://play.google.com/store/apps/details?id=com.saduoch.geoflagster` → Your Google Play link

### 3. Customize GitHub Link
In the footer, update:
```html
<a href="https://github.com/yourusername/geoflagster" target="_blank">GitHub</a>
```

### 4. Test Everything
- Visit your landing page
- Click all buttons
- Verify privacy policy loads
- Test on mobile and desktop

## 🔍 Troubleshooting

### Site not appearing?
1. Check that GitHub Pages is enabled in Settings > Pages
2. Ensure the branch is set to `main` and folder is `/docs`
3. Wait 1-2 minutes for GitHub to deploy
4. Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)

### Links returning 404?
- Verify file names and paths match exactly
- Check that privacy-policy.html is in the `docs/` folder

### Styles not loading?
- Clear your browser cache
- Ensure `css/styles.css` exists in the `docs/css/` folder

## 📱 Responsive Design
The landing page automatically adapts to:
- Mobile phones (320px+)
- Tablets (768px+)
- Desktop displays (1200px+)

## 📧 Support Contact
Users can contact you at: `sdufoo@gmail.com`

---

**Created**: April 29, 2026  
**Status**: Ready for GitHub Pages deployment
