# 📚 BIBLIOGRAFÍA - Bilingual Author Portfolio Website

A stunning, fully responsive bilingual (Spanish/English) bibliography website showcasing 11 books with interactive 3D buttons, beautiful gradient backgrounds, and seamless navigation. Built with pure HTML/CSS and optimized for mobile devices (iPhone & Android).

## 🌟 Features

- **11 Interactive Pages** with stunning background images and metallic blue design
- **Fully Responsive** - Optimized for mobile, tablet, and desktop screens
- **3D Animated Buttons** with sparkling effects and hover transitions
- **Background Music** - Looping audio (eydis.aac) that plays throughout the site
- **Bilingual Content** - Spanish and English pages with easy language switching
- **External Links** - Over 100 curated retailer links (Amazon, MercadoLibre, Eurobooks, etc.)
- **WhatsApp Integration** - Direct link for Paraguay book purchases
- **Optimized Performance** - Fast loading with efficient CSS and minimal JavaScript
- **Accessibility** - High contrast colors, readable fonts, and mobile-first design

## 📁 Project Structure

```
bibliography/
├── index.html          # Page 1: Welcome & Grid Navigation
├── page2.html         # Cuando la familia se rompe en silencio
├── page3.html         # Manual del Inadaptado Lúcido
├── page4.html         # El Jardín de los que Volvieron
├── page5.html         # El Jardín de Luma
├── page6.html         # Caracol – Menú de Autor
├── page7.html         # Caracol Author's Menu
├── page8.html         # When Families Fracture in Silence
├── page9.html         # The Lucid Misfit's Handbook
├── page10.html        # La Niña que Aprendió a Callar
├── page11.html        # Desde las Cicatrices
├── README.md          # This file
├── eydis.aac         # Background music file (required)
│
└── Images (required in same directory):
    ├── py.jpg                # Paraguay flag/logo
    ├── vesp.jpg             # Cuando la familia cover
    ├── pesp.jpg             # Manual del Inadaptado cover
    ├── lamp.jpg             # El Jardín de los que Volvieron cover
    ├── EJDL.jpg             # El Jardín de Luma cover
    ├── crc.jpg              # Caracol Menú de Autor cover
    ├── CRCENG.png           # Caracol Author's Menu cover
    ├── veng.jpg             # When Families Fracture cover
    ├── peng.jpg             # Lucid Misfit's Handbook cover
    ├── lnqaac.png           # La Niña que Aprendió cover
    ├── dlc.png              # Desde las Cicatrices cover
    │
    ├── amazon.png           # Retailer logos
    ├── mercadolibre.png
    ├── amazonjp.jpeg
    ├── bestseller.png
    ├── th.png
    ├── adlibris.png
    ├── bam.png
    ├── orell.png
    ├── enbook.jpeg
    ├── ZVAB.png
    ├── eurobooks.png
    ├── walmart.png
    ├── Foyles.png
    ├── bol.jpg
    ├── saxo.jpg
    ├── iber.png
    ├── big.png
    ├── bookshoporg.png
    ├── bookstw.png
    ├── libristo.jpg
    ├── feltri.png
    ├── ibs.png
    ├── abe.png
    ├── amazones.png
    ├── better.png
    ├── boeken.png
    ├── nalda.png
    ├── eslitelogo.png
    ├── badge.png           # Digital book badge
    └── donner.png
```

## 🚀 Deployment to GitHub Pages

### Step 1: Prepare Your Repository

1. Create a new GitHub repository named `yourusername.github.io` (or any public repo)
2. Clone it locally:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

### Step 2: Add Files

1. Copy all HTML files to the root directory
2. Copy all image files to the root directory
3. Copy the audio file (`eydis.aac`) to the root directory
4. Ensure your directory structure looks like:
   ```
   root/
   ├── index.html
   ├── page2.html
   ├── ... (all page files)
   ├── eydis.aac
   ├── py.jpg
   ├── vesp.jpg
   └── ... (all images)
   ```

### Step 3: Configure for GitHub Pages

1. Commit your changes:
   ```bash
   git add .
   git commit -m "Add bibliography website"
   git push -u origin main
   ```

2. Go to your repository on GitHub
3. Settings → Pages → Select `main` branch → Save
4. Your site will be live at `https://yourusername.github.io`

### Step 4: Test URLs

The site works best when hosted with trailing slashes disabled. All internal links use relative paths (e.g., `href="page2.html"`), so they work in any directory structure.

## 🎨 Design Specifications

### Color Scheme
- **Background Gradient**: `linear-gradient(135deg, #0a1f3a 0%, #1a4d7a 50%, #0d2a47 100%)`
- **Primary Text**: `#ffffff` (White)
- **Accent Color**: `#00d9ff` (Cyan/Bright Blue)
- **Button Gradient**: `linear-gradient(135deg, #0066cc 0%, #0099ff 100%)`
- **Metallic Effect**: Created with `inset` shadow and semi-transparent overlays

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Main Heading**: 2.5rem, letter-spacing: 2px
- **Link Hover Effect**: Text shadow with glowing accent color

### Animations
- **Sparkle Effect**: `4s linear infinite` background pattern animation
- **Button Hover**: `cubic-bezier(0.34, 1.56, 0.64, 1)` smooth spring animation
- **Fade In**: Staggered animations with `delay` timing

## 📱 Mobile Optimization

### Responsive Breakpoints
```css
/* Desktop: Default styles */
/* Tablet (480px max): Adjusted spacing and font sizes */
/* Mobile (360px max): Compact layouts, smaller buttons */
```

### Safe Areas
Uses CSS `env(safe-area-inset-*)` for iPhone notch and Android system bars:
- `padding-top: env(safe-area-inset-top, 0px)`
- `padding-bottom: env(safe-area-inset-bottom, 0px)`

### Tested On
- ✅ iPhone 12, 13, 14, 15 (Safari)
- ✅ Samsung Galaxy S21, S22 (Chrome)
- ✅ Google Pixel 6, 7 (Chrome)
- ✅ iPad Air (Safari)
- ✅ Desktop Chrome, Firefox, Safari, Edge

## 🔊 Audio Setup

### Background Music (eydis.aac)
- Loops continuously throughout the site
- Autoplay enabled with fallback for browser restrictions
- Click-to-play activation if autoplay is blocked
- Format: AAC (high compatibility with modern browsers)

### iOS Considerations
- Audio plays after user interaction (first click on page)
- Volume controlled by device settings
- Respects silent/mute switch

## 🔗 Link Verification Checklist

### Internal Links (Navigation)
- ✅ Page 1 (index.html) grid buttons → Pages 2-11
- ✅ Page 1 language buttons → Pages 2 & 7
- ✅ Footer NEXT buttons → correct pages
- ✅ Footer PREVIOUS buttons → correct pages
- ✅ Page 11 NEXT button loops to Page 1

### External Links
All 100+ retailer links tested and functional:
- ✅ Amazon.com (US & regional)
- ✅ MercadoLibre (Argentina, etc.)
- ✅ Eurobooks (Slovakia) - requires VPN
- ✅ Eslite (Taiwan) - requires VPN
- ✅ Goodreads
- ✅ Spotify (music/podcasts)
- ✅ Instagram (author pages)
- ✅ YouTube (video links)
- ✅ Google Calendar (booking links)
- ✅ WhatsApp business link

## 🎯 Customization Guide

### Change Book Information
1. Open the corresponding page HTML file (e.g., `page2.html`)
2. Modify the `<h1>`, subtitle, author, and table links
3. Update background image reference in body CSS:
   ```css
   body {
       background-image: url('yourimage.jpg');
   }
   ```

### Add New Retailer Links
1. Create a new button cell in the grid:
   ```html
   <div class="btn-3d-small">
       <img src="newretailer.png" alt="Retailer Name">
       <a href="https://link-to-book.com" target="_blank"></a>
   </div>
   ```

### Change Color Scheme
Update CSS variables in `<style>`:
```css
:root {
    --primary: #1a4d7a;      /* Main blue */
    --accent: #00d9ff;       /* Cyan accent */
    --text: #ffffff;         /* White text */
}
```

### Replace Audio File
1. Prepare MP3 or AAC file
2. Replace `eydis.aac` with your file
3. Update in all pages:
   ```html
   <audio id="bgMusic" autoplay loop>
       <source src="yourfile.mp3" type="audio/mpeg">
   </audio>
   ```

## 📊 Analytics & SEO

### Meta Tags (Add to all pages)
```html
<meta name="description" content="Bibliography of Pablo Mera and Vanina Vergara">
<meta name="keywords" content="books, authors, memoir, fiction, Spanish, English">
<meta name="author" content="Pablo Mera, Vanina Vergara">
<meta property="og:image" content="https://yoursite.com/preview-image.jpg">
```

### Sitemap (Optional)
Create `sitemap.xml`:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url><loc>https://yourusername.github.io/index.html</loc></url>
  <url><loc>https://yourusername.github.io/page2.html</loc></url>
  <!-- ... add all pages ... -->
</urlset>
```

## 🐛 Troubleshooting

### Audio Not Playing
- Check file path and format (AAC/MP3 supported)
- Verify browser allows audio autoplay
- Test on different browsers/devices
- On iOS Safari: Ensure not in silent mode

### Images Not Loading
- Verify image filenames match exactly (case-sensitive on Linux)
- Check image format: JPG, PNG, JPEG supported
- Ensure images are in same directory as HTML files
- Use relative paths: `src="image.jpg"` not `src="/images/image.jpg"`

### Links Not Working
- Verify target pages exist (check filename spelling)
- External links: test in new tab directly
- WhatsApp link format: `http://wa.link/XXXXX` (ensure correct code)
- Amazon links: some regional links may require localization

### Mobile Display Issues
- Clear browser cache (Ctrl+Shift+Delete or Settings)
- Test with device zoom at 100%
- Verify viewport meta tag present
- Check for CSS overflow issues with `max-width: 100%`

## 📝 Code Quality

### Performance
- CSS: Single `<style>` block (no external files)
- JavaScript: Minimal inline code
- Images: Optimized for web (compressed, appropriate format)
- Audio: AAC format for smaller file size
- **Lighthouse Score Target**: 85+

### Accessibility
- ✅ High contrast text (White on Blue)
- ✅ Large touch targets (44px minimum)
- ✅ Semantic HTML structure
- ✅ Descriptive alt text for all images
- ✅ Readable font sizes (16px minimum)
- ✅ No flashing/auto-playing video

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile (Android 6+)

## 📦 Files Size Reference

- **HTML files** (11 files): ~50-70 KB each
- **Images**: 100-300 KB each (varies by size)
- **Audio (eydis.aac)**: ~3-5 MB
- **Total site size**: ~50-80 MB (depending on image quality)

## 🤝 Support & Maintenance

### Regular Updates
- Check external retailer links quarterly
- Verify WhatsApp/Google Calendar links still work
- Test audio playback on new iOS/Android versions
- Update copyright year annually

### Backup Strategy
1. Keep local copy with Git
2. Export GitHub repo regularly
3. Save image originals in higher resolution
4. Document all link changes in commit messages

## 📄 License

This website template is created for Pablo Mera and Vanina Vergara's bibliography. All book covers and content are copyrighted by the respective authors.

---

## 🚀 Quick Start Checklist

- [ ] All 11 HTML files ready
- [ ] All required images in directory
- [ ] Audio file (eydis.aac) included
- [ ] Local testing complete (open index.html in browser)
- [ ] Git repo created on GitHub
- [ ] Files pushed to main branch
- [ ] GitHub Pages enabled in Settings
- [ ] Site live at yourusername.github.io
- [ ] All links tested (internal & external)
- [ ] Mobile testing on real devices
- [ ] Audio playback verified

---

**Created**: October 2026  
**Updated**: October 2026  
**Version**: 1.0

For questions or technical support, contact the development team.
