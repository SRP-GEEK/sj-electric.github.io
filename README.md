# SJ Enterprises - Professional Website

## About
This is the official website for SJ Enterprises, an electrical accessories and project material supply company established in 1975 with 50+ years of legacy across four generations.

## Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Professional industrial theme with dark green, navy, and beige colors
- ✅ 7 pages: Home, About Us, Products, Industries, Pricing, Gallery, Contact
- ✅ Contact form with HTML/JavaScript validation
- ✅ WhatsApp integration for quick quotes
- ✅ BOQ-based pricing explanation
- ✅ Project portfolio showcase
- ✅ Mobile-friendly navigation
- ✅ Clean, commented code

## File Structure
```
├── index.html          # Home page
├── about.html          # About Us page
├── products.html       # Products catalog
├── industries.html     # Industries We Serve
├── pricing.html        # How Pricing Works
├── gallery.html        # Project Gallery
├── contact.html        # Contact Us with form
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
├── SJ_Logo_High_Resolution.png  # Company logo
├── CNAME              # Custom domain configuration
└── README.md          # This file
```

## Deployment to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `sj-electric.github.io` (or your preferred name)
3. Make it **Public**
4. Do NOT initialize with README (we already have files)
5. Click "Create repository"

### Step 2: Upload Files
Upload all the files from this folder to your repository:
- index.html
- about.html
- products.html
- industries.html
- pricing.html
- gallery.html
- contact.html
- style.css
- script.js
- SJ_Logo_High_Resolution.png
- CNAME (if using custom domain)
- README.md

### Step 3: Enable GitHub Pages
1. Go to your repository Settings
2. Scroll to "Pages" section (left sidebar)
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" (or "master") and "/ (root)"
5. Click "Save"

### Step 4: Access Your Website
- Your website will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`
- If using custom domain (CNAME file), configure DNS settings accordingly
- It may take a few minutes for the site to go live

## Customization

### Update Contact Information
Replace the phone number and email in all HTML files:
- Current: +91 9823460907
- Current: sjgrppne@gmail.com

### Update WhatsApp Links
Search for `wa.me/919823460907` and replace with your WhatsApp number.

### Change Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-dark: #1a3a2e;
    --primary-navy: #0d2137;
    --accent-gold: #c9a961;
    --neutral-beige: #f4f1e8;
}
```

### Add Real Project Images
Replace the placeholder emoji icons in `gallery.html` with actual project images:
```html
<!-- Current -->
<div class="gallery-placeholder">🏘️</div>

<!-- Replace with -->
<img src="path/to/your/image.jpg" alt="Project description" style="width: 100%; height: 250px; object-fit: cover;">
```

## Technology Stack
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (no frameworks)
- Responsive design principles
- Mobile-first approach

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact
For any questions or support regarding this website:
- Phone: +91 9823460907
- Email: sjgrppne@gmail.com
- WhatsApp: +91 9823460907

## License
© 2025 SJ Enterprises. All rights reserved.

---

**Built with care for SJ Enterprises - Serving since 1975**
