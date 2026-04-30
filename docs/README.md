# GeoFlagster Landing Page

This is the official landing page for GeoFlagster, hosted on GitHub Pages.

## 📁 Structure

```
docs/
├── index.html              # Main landing page
├── privacy-policy.html     # Privacy policy
├── _config.yml             # GitHub Pages configuration
├── css/
│   └── styles.css          # Landing page styles
└── assets/
    └── (screenshots and images go here)
```

## 🚀 Setup

### Enable GitHub Pages

1. Go to your GitHub repository settings
2. Navigate to **Settings** > **Pages**
3. Under "Build and deployment":
   - Set **Source** to `Deploy from a branch`
   - Set **Branch** to `main` (or your default branch)
   - Set **Folder** to `/docs`
4. Click **Save**

Your site will be published at: `https://yourusername.github.io/geoflagster`

## ✏️ Updating Content

### Update the Landing Page
Edit `docs/index.html` to modify:
- Headlines and descriptions
- Feature cards
- Call-to-action buttons
- Links to App Store/Google Play

### Add Screenshots
1. Place your screenshot images in `docs/assets/`
2. Update the image paths in `index.html`:
```html
<img src="assets/screenshot-1.png" alt="Description">
```

### Update App Store Links
Find and update these URLs in `index.html`:
- **App Store**: `https://apps.apple.com/app/geoflagster`
- **Google Play**: `https://play.google.com/store/apps/details?id=com.saduoch.geoflagster`

### Customize Styles
Edit `css/styles.css` to adjust:
- Colors (check `:root` variables)
- Fonts
- Spacing
- Responsive breakpoints

## 📱 Responsive Design

The landing page is fully responsive and works on:
- Mobile phones (375px+)
- Tablets (768px+)
- Desktop displays (1200px+)

## 🔗 URLs

Once deployed, your landing page will have these URLs:

- **Main Landing Page**: `https://yourusername.github.io/geoflagster/`
- **Privacy Policy**: `https://yourusername.github.io/geoflagster/privacy-policy.html`
- **Support Email**: `sdufoo@gmail.com`

## 📋 To-Do for Production

- [ ] Replace placeholder screenshots with actual app screenshots
- [ ] Update App Store and Google Play links with real URLs
- [ ] Update GitHub repository link in footer
- [ ] Test on multiple devices and browsers
- [ ] Verify privacy policy displays correctly
- [ ] Check all links work properly

## 🎨 Color Scheme

- **Primary Color**: `#2563eb` (Blue)
- **Secondary Color**: `#10b981` (Green)
- **Text**: `#1f2937` (Dark Gray)
- **Background**: `#ffffff` (White)

Adjust these in `css/styles.css` if needed.

## 📧 Contact

For support or questions, users can contact: `sdufoo@gmail.com`

---

**Last Updated**: April 29, 2026
