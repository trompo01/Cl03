# Bibliografía - Bilingual Bibliography Template

A sophisticated, minimalistic bilingual book bibliography website with dark theme, 3D interactive effects, mobile responsiveness, and immersive audio.

## Features

### 🎨 Visual Design
- **Dark Minimalistic Theme**: Deep black background (#0a0a0a) with elegant cyan/neon blue accents (#64c8ff)
- **High Contrast**: White text on dark background for optimal readability
- **3D Effects**: 
  - Hover-activated 3D tilt on all interactive elements
  - Mouse-movement-responsive perspective transforms
  - Gentle floating animations
  - Sparkling link effects with gradient overlays
  
### 🌍 Bilingual Navigation
- **Dual Language Support**: Spanish (Español) & English
- **Language Gates**: Direct page access via language selector buttons
- **Seamless Navigation**: Between 9 interconnected pages

### 📱 Mobile Optimization
- **Responsive Design**: Optimized for all phone models (Android & iPhone)
- **Touch Navigation**: Swipe left/right to navigate pages
- **Flexible Grid**: Images adapt to screen size
- **Mobile-First Buttons**: Touch-friendly button sizing

### 🎵 Audio Integration
- **Background Music**: kelvin.aac plays automatically while navigating
- **Looping**: Continuous audio loop with play/pause control
- **Audio Toggle**: Floating music control button (bottom-right corner)
- **Auto-Play**: Music starts immediately when available

### 📚 Content Structure

#### Page 1: Welcome/Inicio
- Title: "BIBLIOGRAFÍA"
- 2×4 Grid (8 image buttons) linking to different books
- Language selector buttons with animated flags
- Gateway to Spanish and English sections

#### Page 2: CUANDO LA FAMILIA SE ROMPE EN SILENCIO
- Author: Vanina Vergara
- 10 clickable links to various platforms
- Purchase buttons (Amazon, Mercado Libre)
- Navigation to Page 3

#### Page 3: Manual del Inadaptado Lúcido
- Author: Pablo Mera
- 11 information links
- 8 retailer buttons (grid format)
- Navigation to Page 4

#### Page 4: El Jardín de los que Volvieron
- Author: Vanina Vergara
- 10 information links
- 6 retailer buttons (2×3 grid)
- Navigation to Page 5

#### Page 5: El Jardín de Luma
- Author: Vanina Vergara
- Prequel to El Jardín de los que Volvieron
- 10 information links
- 6 retailer buttons
- Navigation to Page 6

#### Page 6: CARACOL – Menú de Autor
- Author: Pablo Mera
- 8 information links
- 6 retailer buttons
- Spanish language version
- Navigation to Page 7

#### Page 7: CARACOL Author's Menu
- Author: Pablo Mera
- English language version
- 10 information links
- 2 purchase buttons
- Navigation to Page 8

#### Page 8: WHEN FAMILIES FRACTURE IN SILENCE
- Author: Vanina Vergara
- English language edition
- 9 information links
- Purchase buttons
- Navigation to Page 9

#### Page 9: THE LUCID MISFIT'S HANDBOOK
- Author: Pablo Mera
- English language edition
- 10 information links
- 10 international retailer buttons
- Loops back to Page 1

### 🎮 Interactive Features

#### 3D Tilt System
- Elements rotate in 3D space as you move your mouse
- Perspective-based transforms
- Distance-aware activation (200px radius)
- Smooth transitions and resets

#### Navigation Options
1. **Click**: Direct button clicks for page navigation
2. **Keyboard**: Arrow keys (← Left, → Right)
3. **Touch**: Swipe gestures on mobile devices
4. **Footer Buttons**: Previous/Next navigation on every page

#### Button Effects
- **Sparkling Animation**: Shimmer effect on hover
- **Glow Effects**: Neon glow on titles and links
- **Float Animation**: Subtle up-down floating motion
- **Scale & Elevation**: Buttons rise on hover

### 📂 File Structure

```
/
├── index.htm              # Main HTML file (all 9 pages in one document)
├── README.md              # This documentation
├── kelvin.aac             # Background music file
│
├── Images/
│   ├── vesp.jpg          # Page 2 book cover & background
│   ├── pesp.jpg          # Page 3 book cover & background
│   ├── lamp.jpg          # Page 4 book cover & background
│   ├── EJDL.jpg          # Page 5 book cover & background
│   ├── crc.jpg           # Page 6 book cover & background
│   ├── CRCENG.png        # Page 7 book cover & background
│   ├── veng.jpg          # Page 8 book cover & background
│   ├── peng.jpg          # Page 9 book cover & background
│   │
│   ├── amazon.png        # Amazon retailer button
│   ├── mercadolibre.png  # Mercado Libre button
│   ├── v1.png            # Version indicator
│   ├── ibs.png           # IBS.it retailer
│   ├── th.png            # ThriftBooks retailer
│   ├── falter.png        # Falter.at retailer
│   ├── feltri.png        # Feltrinelli retailer
│   ├── bam.png           # Books-A-Million retailer
│   ├── enbook.jpeg       # Enbook retailer
│   ├── adlibris.png      # Adlibris retailer
│   ├── iber.png          # IberLibro retailer
│   ├── better.png        # BetterRead retailer
│   ├── Foyles.png        # Foyles retailer
│   ├── libristo.jpg      # Libristo retailer
│   ├── bookshoporg.png   # Bookshop.org retailer
│   ├── bookstw.png       # Books.com.tw retailer
│   ├── saxo.jpg          # Saxo retailer
│   └── bol.jpg           # BOL.com retailer
```

### 🎯 Color Palette

| Color | Hex | Use |
|-------|-----|-----|
| Background | #0a0a0a | Main page background |
| Primary Accent | #64c8ff | Buttons, titles, borders |
| Text Primary | #ffffff | Main text content |
| Text Secondary | #b0b0b0 | Subtitle/author text |
| Button Background | #1a1a2e | Button base color |
| Overlay | rgba(10, 10, 10, 0.7) | Background image overlay |

### 🔗 Supported Retailer Links

**Spanish Language Books:**
- Amazon (Kindle, Paperback, Hardcover)
- Mercado Libre
- ThriftBooks
- IBS.it
- Feltrinelli
- Books-A-Million
- Enbook
- Adlibris
- IberLibro
- Foyles
- Goodreads
- Spotify Playlists
- Instagram Accounts

**English Language Books:**
- Amazon (All formats)
- Books-A-Million
- Bookshop.org
- Books.com.tw
- ThriftBooks
- Saxo
- IBS.it
- Feltrinelli
- BOL.com
- Enbook
- Goodreads

### 🚀 Deployment Instructions

#### For GitHub Pages

1. **Create Repository**
   - Go to github.com and create a new repository named `bibliography` (or your preferred name)
   - Clone to your local machine

2. **Add Files**
   ```bash
   cp index.htm your-repo/
   cp README.md your-repo/
   cp kelvin.aac your-repo/
   cp -r images/ your-repo/
   ```

3. **Configure GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Save

4. **Access Your Site**
   - Your site will be available at: `https://yourusername.github.io/bibliography`

#### For Local Testing

Simply open `index.htm` in a modern web browser:
```bash
open index.htm  # macOS
start index.htm # Windows
firefox index.htm # Linux
```

### 💻 Browser Compatibility

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

### 🎧 Audio Setup

Place the `kelvin.aac` file in the same directory as `index.htm`. The audio will:
- Auto-play on page load (when permitted by browser)
- Loop continuously
- Pause/resume with the floating control button
- Persist across page navigation

### 🔧 Customization Guide

#### Change Colors
Edit the CSS variables in the `<style>` section:
```css
color: #64c8ff;        /* Primary accent */
background: #0a0a0a;   /* Background */
color: #ffffff;        /* Text */
```

#### Add More Pages
1. Copy an existing `<div class="page">` block
2. Update the `id="page#"` attribute
3. Modify content as needed
4. Update navigation links in surrounding pages

#### Adjust 3D Effect Intensity
In the JavaScript section, modify the tilt values:
```javascript
const rotateX = (distY / maxDistance) * 15;  // Change 15 to higher/lower
const rotateY = (distX / maxDistance) * -15; // Change 15 to higher/lower
```

#### Change Audio File
Replace `kelvin.aac` with your audio file and update the HTML:
```html
<source src="your-audio-file.aac" type="audio/aac">
```

### 📊 Performance Optimization

- **Lazy Loading**: Background images use CSS background-image (cached efficiently)
- **CSS-Based Animations**: Hardware-accelerated transforms
- **Minimal JavaScript**: Efficient event handlers with debouncing
- **Responsive Images**: Adapt to screen size dynamically
- **No External Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript

### ✨ Accessibility Features

- **Semantic HTML**: Proper heading hierarchy (H1, H2, H3)
- **Link Targets**: External links open in new tabs (`target="_blank"`)
- **Keyboard Navigation**: Full support for arrow keys
- **ARIA Labels**: Descriptive titles on interactive elements
- **High Contrast**: Accessible color combinations (WCAG AA standard)

### 🐛 Troubleshooting

**Audio Not Playing?**
- Check browser autoplay policy (may require user interaction first)
- Ensure `kelvin.aac` is in the same directory as `index.htm`
- Use the audio control button to manually play/pause

**3D Effects Not Working?**
- Browser may not support CSS 3D transforms
- Update to a modern browser version
- Check browser developer console for errors

**Links Not Working?**
- Verify all href URLs are correct and accessible
- Test links individually in a new tab
- Check internet connection

**Mobile Layout Issues?**
- Use Chrome DevTools device emulation
- Test on actual mobile devices
- Check viewport meta tag is present

### 📝 Credits

- **Design**: Bilingual Bibliography Template
- **Author Information**: Vanina Vergara, Pablo Mera
- **Books Featured**: 8 published works with international distribution
- **Music**: kelvin.aac (background score)

### 📄 License

This template is provided as-is for personal and commercial use. Customize freely for your needs.

### 🌐 Version

**Version 1.0** - June 2026

---

## Quick Start Checklist

- [ ] Add `kelvin.aac` to project directory
- [ ] Add all book cover images (vesp.jpg, pesp.jpg, lamp.jpg, etc.)
- [ ] Add all retailer logo images (amazon.png, th.png, etc.)
- [ ] Test all links are functional
- [ ] Test audio playback
- [ ] Test 3D effects on desktop
- [ ] Test mobile responsiveness
- [ ] Test keyboard navigation (arrow keys)
- [ ] Test touch navigation (swipe)
- [ ] Upload to GitHub Pages or hosting service

---

## Need Help?

For detailed instructions on each feature or customization options, refer to the inline code comments in `index.htm`.

Enjoy your bilingual bibliography website! 🎉
