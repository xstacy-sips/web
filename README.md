# Xstacy Multi-Page Website

A professional multi-page website for Xstacy beverage brand with separate pages for different sections.

## 📁 File Structure

```
your-repository/
├── index.html          # Home page
├── about.html          # About Us page
├── menu.html           # Menu page
├── gallery.html        # Gallery page
├── contact.html        # Contact page
├── styles.css          # Shared stylesheet
├── script.js           # Shared JavaScript
└── image/
    ├── logo.png
    ├── xstacy-text-logo.png
    ├── doodle1.png (optional)
    ├── doodle2.png (optional)
    ├── doodle3.png (optional)
    ├── doodle4.png (optional)
    ├── doodle5.png (optional)
    └── doodle6.png (optional)
```

## 🌟 Pages Overview

### 1. **index.html** - Home Page
- Hero section with logo and tagline
- Preview of About section
- Featured drinks preview
- Quick navigation to all pages

### 2. **about.html** - About Us
- Full brand story
- Brand values (Creative Flavors, Happy Vibes, Premium Quality)
- "Our Story" section

### 3. **menu.html** - Menu
- Hot Drinks section
- Cold Drinks section
- Full drink descriptions and prices

### 4. **gallery.html** - Gallery
- Visual showcase of happy moments
- Placeholder for photos (6 items)

### 5. **contact.html** - Contact
- Contact form
- Business information
- Social media links

## 🎨 Features

✅ **Fully Responsive** - Works on all devices
✅ **Consistent Navigation** - Easy to move between pages
✅ **Active Page Highlighting** - Shows current page in navigation
✅ **Shared Styling** - One CSS file for all pages
✅ **Scroll Animations** - Elements fade in as you scroll
✅ **Mobile Menu** - Hamburger menu for mobile devices
✅ **Floating Doodles** - Animated doodles on home page (optional)

## 🚀 How to Deploy on GitHub Pages

### Step 1: Upload All Files

Upload these files to your repository root:
- index.html
- about.html
- menu.html
- gallery.html
- contact.html
- styles.css
- script.js

### Step 2: Create Image Folder

1. Create a folder named `image` in your repository
2. Upload your logo files:
   - logo.png (circular logo)
   - xstacy-text-logo.png (text logo)
3. Optionally upload doodle files (doodle1.png through doodle6.png)

### Step 3: Enable GitHub Pages

1. Go to Settings → Pages
2. Select "main" branch
3. Click "Save"
4. Your site will be live at: `https://[username].github.io/[repo-name]`

## 🎯 Customization

### Adding More Menu Items

Edit `menu.html` and add more items to the `.menu-grid`:

```html
<div class="menu-item">
    <div class="menu-item-image">Name</div>
    <div class="menu-item-content">
        <h3>Drink Name</h3>
        <p class="menu-item-description">Description here</p>
        <p class="menu-item-price">₹Price</p>
    </div>
</div>
```

### Changing Colors

Edit `styles.css` at the top:

```css
:root {
    --primary: #3853a4;        /* Main blue */
    --background: #faf8f3;     /* Cream background */
    --accent-green: #cddda3;   /* Light green */
    --accent-brown: #846b59;   /* Brown */
}
```

### Removing Floating Doodles

In `index.html`, delete or comment out these lines:

```html
<!-- Floating Doodles -->
<div class="doodle doodle-1"><img src="image/doodle1.png" alt=""></div>
<!-- ... rest of doodles ... -->
```

## 📱 Contact Information

Update your contact details in `contact.html`:
- Email
- Phone number
- Address
- Social media links

## 🎨 Brand Colors

- **Primary Blue**: #3853a4
- **Background Cream**: #faf8f3
- **Accent Green**: #cddda3
- **Accent Brown**: #846b59

## 📝 Notes

- All pages share the same header and footer for consistency
- Navigation automatically highlights the current page
- Mobile-friendly with responsive design
- SEO-friendly with proper page titles
- Fast loading with optimized CSS and JS

## 🔧 Troubleshooting

**Images not showing?**
- Check that the `image` folder exists
- Verify file names match exactly (case-sensitive)
- Check file paths in HTML files

**Navigation not working?**
- Make sure all HTML files are in the root directory
- Check that script.js is loading properly

**Styling issues?**
- Verify styles.css is in the root directory
- Clear browser cache and refresh

---

**Making The World Smile, One Sip at a Time** ☕✨

Design by Arti Kathe | © 2025 Xstacy
