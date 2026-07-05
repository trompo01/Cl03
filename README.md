# Bibliografía - Multi-Language Book Bibliography Website

A stunning, dark-themed, responsive bilingual website showcasing the works of **Pablo Mera** and **Vanina Vergara**. This nine-page digital catalog features interactive 3D buttons, immersive background images, and direct links to international bookstores.

## 🌟 Features

- **9 Interactive Pages**: Complete bilingual navigation (Spanish & English)
- **Dark Minimalist Design**: High contrast white text on dark background with neon accents
- **3D Effects**: Interactive tilt animations on mouse movement
- **Mobile Responsive**: Optimized for all devices (smartphones, tablets, desktops)
- **Auto-Playing Music**: Ambient background audio (abidoza.aac)
- **Sparkling Buttons**: Eye-catching animations on interactive elements
- **International Bookstore Links**: Direct connections to Amazon, Mercado Libre, and 20+ global retailers
- **Bilingual Content**: Full Spanish and English book descriptions and links

## 📖 Pages Overview

| Page | Title | Language | Content |
|------|-------|----------|---------|
| 1 | Bibliografía (Welcome) | Bilingual | Navigation hub with 8 book covers |
| 2 | Cuando la Familia se Rompe en Silencio | Spanish | Vanina Vergara's memoir |
| 3 | Manual del Inadaptado Lúcido | Spanish | Pablo Mera's philosophical handbook |
| 4 | El Jardín de los que Volvieron | Spanish | Vanina Vergara's literary work |
| 5 | El Jardín de Luma | Spanish | Prequel to El Jardín de los que Volvieron |
| 6 | Caracol – Menú de Autor | Spanish | Pablo Mera's nightclub memoirs |
| 7 | Caracol Author's Menu | English | English version of page 6 |
| 8 | When Families Fracture in Silence | English | English version of page 2 |
| 9 | The Lucid Misfit's Handbook | English | English version of page 3 |

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com/new)
2. Create a new repository named: `yourusername.github.io`
3. Make sure it's set to **Public**

### Step 2: Upload Files
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

2. Copy your files:
   - `index.htm` (main website file)
   - `README.md` (this file)
   - All image files (see below)
   - `abidoza.aac` (background music file)

3. Commit and push:
   ```bash
   git add .
   git commit -m "Initial website commit"
   git push -u origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to your repository **Settings**
2. Scroll to **GitHub Pages** section
3. Select **main** branch as source
4. Your site will be live at: `https://yourusername.github.io`

## 📁 Required Files

### Images (Book Covers & Logos)
Place these files in the same directory as `index.htm`:

**Book Covers:**
- `vesp.jpg` - Cuando la Familia se Rompe (Spanish cover)
- `pesp.jpg` - Manual del Inadaptado Lúcido (Spanish cover)
- `lamp.jpg` - El Jardín de los que Volvieron (background image)
- `EJDL.jpg` - El Jardín de Luma (background image)
- `crc.jpg` - Caracol Menú de Autor (Spanish background)
- `CRCENG.png` - Caracol Author's Menu (English background)
- `veng.jpg` - When Families Fracture in Silence (English background)
- `peng.jpg` - The Lucid Misfit's Handbook (English background)
- `py.jpg` - Paraguay WhatsApp button image

**Retailer Logos:**
- `amazon.png` - Amazon logo
- `amazon.co.jp` - Amazon Japan logo
- `amazones.png` - Amazon Spain logo
- `amazonjp.jpeg` - Amazon JP (alternate)
- `mercadolibre.png` - Mercado Libre logo
- `th.png` - ThriftBooks logo
- `ibs.png` - IBS.it logo
- `feltri.png` - La Feltrinelli logo
- `walmart.png` - Walmart logo
- `orell.png` - Orell Füssli logo
- `enbook.jpeg` - Enbook logo
- `najla.jpg` - Najla shortlink logo
- `falter.png` - Falter.at logo
- `better.png` - Better Read logo
- `adlibris.png` - Adlibris logo
- `big.png` - Big Shopper logo
- `iber.png` - Iberlibro logo
- `libristo.jpg` - Libristo logo
- `bam.png` - Books a Million logo
- `Foyles.png` - Foyles logo
- `bookshoporg.png` - Bookshop.org logo
- `bookstw.png` - Books.com.tw logo
- `bol.jpg` - Bol.com logo
- `saxo.jpg` - Saxo logo
- `eslitelogo.png` - Eslite (Taiwan) logo

### Audio
- `abidoza.aac` - Background music file (loops automatically on page load)

## 🎨 Design Specifications

### Color Scheme
- **Background**: Dark (#0a0a0a)
- **Primary Text**: White (#ffffff)
- **Primary Accent**: Cyan (#00ffff)
- **Secondary Accent**: Neon Green (#00ff88)
- **Highlight**: Semi-transparent dark overlays

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Main Title**: 3rem, uppercase, with cyan glow
- **Headings**: 1.8rem and 1.4rem, uppercase
- **Body Text**: 1rem, white, high contrast

### Interactive Elements
- **3D Button Tilt**: Rotates on mouse movement
- **Hover Effects**: Glow intensifies, scale increases
- **Animations**: Sparkling effect, smooth transitions
- **Mobile Optimization**: Touch-friendly buttons, responsive grid layout

## 📱 Mobile Responsiveness

The website automatically adapts to different screen sizes:
- **Desktop** (1024px+): Full 2-column grids, large fonts
- **Tablet** (768px-1023px): Adjusted spacing and button sizes
- **Mobile** (480px-767px): Single column for some elements
- **Small Mobile** (<480px): Optimized touch targets, minimal padding

## 🔗 Navigation Features

- **Main Button**: Alternates between three promotional messages
  - "AHORA" (Now)
  - "COMPRALOS" (Buy Them)
  - "EN PARAGUAY" (In Paraguay)
  - Links to WhatsApp: `http://wa.link/21ft32`

- **Language Buttons**: Quick switch between Spanish and English versions
  - Spanish flag → Navigates to page 2
  - English flag → Navigates to page 7

- **Navigation Footer**: On each page
  - "NEXT / SIGUIENTE" → Forward navigation
  - "PREVIOUS / ANTERIOR" → Back navigation

## 🎵 Audio Setup

The background music (`abidoza.aac`) automatically:
- Starts playing on first user interaction
- Loops continuously while browsing
- Uses non-intrusive initialization to comply with browser autoplay policies

To manually enable autoplay without user interaction, modify the audio tag in `index.htm`:
```html
<audio id="bgMusic" autoplay loop muted>
```
Then unmute with JavaScript after user interaction.

## 🔧 Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:
```css
color: #00ffff;  /* Cyan accent */
color: #00ff88;  /* Neon green */
background: #0a0a0a;  /* Dark background */
```

### Adjusting Animation Speed
Modify transition values:
```css
transition: all 0.3s ease;  /* Change 0.3s to your preferred duration */
```

### Adding More Pages
1. Copy an existing page `<div class="page">` block
2. Update the ID (e.g., `id="page10"`)
3. Modify the background image URL
4. Update the navigation buttons

## 🌐 Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Full support

## 📊 Link Verification

All external links have been included and verified for:
- ✅ Amazon links (multiple countries)
- ✅ Independent bookstore links
- ✅ Social media (Spotify, Goodreads, Instagram)
- ✅ WhatsApp integration
- ✅ Author websites and blogs
- ✅ Video content links

## 📚 Content Structure

Each book page includes:
1. **Title & Author Information** - Centered with accent colors
2. **Main Content Table** - All relevant links organized by type
3. **Retailer Grid** - 8-16 bookstore logos linking to specific titles
4. **Navigation Footer** - Next/Previous page buttons
5. **Background Image** - Book-specific atmospheric backdrop

## 🎯 Accessibility

- High contrast text (white on dark background)
- Clear button labels with descriptive alt text
- Proper semantic HTML structure
- Mobile-friendly touch targets (minimum 48x48px)
- Keyboard-navigable interface

## 📝 License

This website template is custom-built for showcasing literary works. Feel free to modify and adapt as needed.

## 🤝 Support & Contact

For questions or technical support with GitHub Pages deployment, refer to the [GitHub Pages Documentation](https://pages.github.com/).

For content updates, edit the HTML links and text directly in `index.htm`.

---

**Last Updated**: July 2026
**Version**: 1.0
**Built for**: Pablo Mera & Vanina Vergara
