# Bibliografía - Vanina Vergara & Pablo Mera

A stunning, bilingual bibliography website showcasing the works of acclaimed authors **Vanina Vergara** and **Pablo Mera**. This cinematic, dark-themed single-page application features 9 comprehensive pages with interactive 3D buttons, embedded background music, flag animations, and links to international book retailers.

## 🌟 Features

### Design & Aesthetics
- **Dark Cinematic Aesthetic**: Deep navy backgrounds with vibrant cyan and purple neon accents
- **True 3D Tilt Effects**: Mouse-responsive perspective transforms on all buttons
- **Sparkling Animations**: Pulsing button effects with smooth hover states
- **Responsive Design**: Optimized for desktop, tablet, and mobile (iOS & Android)
- **High Contrast**: White text on dark backgrounds for maximum readability

### Interactive Elements
- **3D Buttons**: Custom-styled clickable buttons with depth, shadow, and glow effects
- **Flag Animations**: Scrolling country flags (Spain 🇪🇸, Paraguay 🇵🇾, Argentina 🇦🇷, Uruguay 🇺🇾, USA 🇺🇸, UK 🇬🇧, Australia 🇦🇺)
- **Music Player**: Auto-playing background music (abidoza.aac) with toggle control
- **Grid Navigation**: 2×4 book cover grid on landing page linking to author bibliographies
- **Retailer Grid Links**: 8-16 international book retailers per title

### Content
- **9 Complete Pages**:
  1. Bibliografía (Welcome/Navigation)
  2. Cuando la Familia se Rompe en Silencio (Vanina Vergara - Spanish)
  3. Manual del Inadaptado Lúcido (Pablo Mera - Spanish)
  4. El Jardín de los que Volvieron (Vanina Vergara - Spanish)
  5. El Jardín de Luma (Vanina Vergara - Spanish)
  6. Caracol - Menú de Autor (Pablo Mera - Spanish)
  7. Caracol Author's Menu (Pablo Mera - English)
  8. When Families Fracture in Silence (Vanina Vergara - English)
  9. The Lucid Misfit's Handbook (Pablo Mera - English)

- **Complete Metadata**: Book titles, subtitles, author names, descriptions
- **Comprehensive Links**: Spotify, YouTube, Goodreads, Instagram, blogs, Google Calendar scheduling
- **International Retailers**: Amazon, Mercado Libre, ThriftBooks, IBS, Walmart, Saxo, Adlibris, and 15+ more

### Technical Features
- **Single HTML File**: Entire site in one `index.html` for easy deployment
- **No Dependencies**: Pure HTML5, CSS3, and JavaScript
- **Embedded Audio**: Background music autoplay with volume control
- **Keyboard Navigation**: Arrow keys to navigate between pages
- **Mobile-First**: Responsive grid layouts and touch-friendly buttons
- **Performance**: Optimized for fast loading and smooth animations

## 📦 Files Included

```
.
├── index.html          # Complete website (9 pages, all content, styling & JavaScript)
├── README.md           # This file
├── abidoza.aac         # Background music (place in same directory as index.html)
├── py.jpg              # Paraguay flag image
├── vesp.jpg            # Spanish edition book cover
├── pesp.jpg            # Spanish edition book cover
├── lamp.jpg            # Book cover image
├── EJDL.jpg            # Book cover image
├── crc.jpg             # Caracol Spanish cover
├── CRCENG.png          # Caracol English cover
├── veng.jpg            # English edition book cover
├── peng.jpg            # English edition book cover
├── amazon.png          # Retailer logo
├── mercadolibre.png    # Retailer logo
├── v1.png              # Author image
├── ibs.png             # Retailer logo
├── th.png              # ThriftBooks logo
├── falter.png          # Retailer logo
├── feltri.png          # La Feltrinelli logo
├── orell.png           # Orell Füssli logo
├── enbook.jpeg         # Retailer logo
├── najla.jpg           # Retailer logo
├── iber.png            # Iberlibro logo
├── walmart.png         # Walmart logo
├── adlibris.png        # Adlibris logo
├── bam.png             # Books-A-Million logo
├── Foyles.png          # Foyles logo
├── better.png          # Better Read logo
├── big.png             # Big Shopper logo
├── eslitelogo.png      # Eslite Taiwan logo
├── amazonjp.jpeg       # Amazon Japan logo
├── libristo.jpg        # Libristo logo
├── bol.jpg             # Bol.com logo
├── saxo.jpg            # Saxo logo
├── bookshoporg.png     # Bookshop.org logo
├── bookstw.png         # Books.com.tw logo
└── amazones.png        # Amazon Spain logo
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `your-username.github.io` (for user site) or any name for project site
3. Initialize with a README

### Step 2: Prepare Your Files
1. Create a folder locally (e.g., `bibliografia-site`)
2. Copy all files listed above into this folder
3. Ensure `index.html` is in the root directory

### Step 3: Upload to GitHub
**Option A: Using Git Command Line**
```bash
cd /path/to/bibliografia-site
git init
git add .
git commit -m "Initial commit: Bilingual bibliography website"
git remote add origin https://github.com/your-username/repository-name.git
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Desktop**
1. Open GitHub Desktop
2. Click "Create a New Repository"
3. Choose the local path where your files are
4. Publish to GitHub

**Option C: Drag & Drop**
1. In your GitHub repository, click "Add file" → "Upload files"
2. Drag and drop all files
3. Commit changes

### Step 4: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "GitHub Pages" section
3. Select `main` branch as source
4. Save

Your site will be live at:
- `https://your-username.github.io` (if named `your-username.github.io`)
- `https://your-username.github.io/repository-name` (for project repositories)

## 🎨 Design Specifications

### Color Palette
- **Background**: `#0a0e27` (deep navy)
- **Primary Accent**: `#00d4ff` (cyan/neon blue)
- **Secondary Accent**: `#9d4edd` (purple)
- **Highlight Accent**: `#ff006e` (neon pink)
- **Text**: `#ffffff` (white)
- **Neon Black**: `#1a1a2e` (dark container)

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Display Text**: 2.5rem, bold, letter-spaced
- **Body Text**: 0.95rem, line-height 1.6
- **Link Color**: Cyan with hover glow effects

### Responsive Breakpoints
- **Desktop**: Full grid layout with 2-4 columns
- **Tablet**: 768px breakpoint - adjusted padding and font sizes
- **Mobile**: Single column, 2-column grids, touch-optimized spacing

## 🎵 Music & Audio

- **Background Music**: `abidoza.aac` auto-plays on load
- **Volume**: Preset to 30% for comfortable listening
- **Controls**: Music toggle button (♪) in bottom-right corner
- **Loop**: Music loops continuously throughout session

## 🔗 Link Categories

### Retailer Links (Updated)
- Amazon (multiple editions: Kindle, Paperback, Hardcover)
- Amazon Spain (amazones.com)
- Amazon Japan (amazon.co.jp)
- Mercado Libre (mercadolibre.com.ar)
- ThriftBooks (thriftbooks.com)
- Walmart (walmart.com)
- Books-A-Million (booksamillion.com)
- Bookshop.org (bookshop.org)
- IBS (ibs.it)
- La Feltrinelli (lafeltrinelli.it)
- Iberlibro (iberlibro.com)
- Orell Füssli (orellfuessli.ch)
- Adlibris (adlibris.com)
- Saxo (saxo.com)
- Bol.com (bol.com)
- Enbook (enbook.cz)
- Libristo (libristo.hu, libristo.si)
- Better Read (betterread.com.au)
- Big Shopper (bigshopper.nl)
- Eslite Taiwan (eslite.com)

### Social & Author Links
- **Spotify**: Spoken reviews, author playlists
- **YouTube**: Video reviews
- **Instagram**: Author accounts (@caracol.menudeautor, @el.jardin.de.luma)
- **Goodreads**: Book reviews and ratings
- **Blogs**: Author blogs (pablomera.blogspot.com)
- **Google Calendar**: Scheduling links for author conversations
- **WhatsApp**: Direct contact (http://wa.link/21ft32)

## 🎮 User Interactions

### Navigation
- **Click** grid buttons to navigate between pages
- **Arrow Keys** (← →) to move between pages
- **Language Buttons** on landing page to jump to Spanish/English sections
- **Footer Navigation** on each content page (NEXT/SIGUIENTE, PREVIOUS/ANTERIOR)

### Button Hover Effects
- 3D perspective transform
- Shadow and glow intensification
- Scale transform on grid items
- Color transitions on text links

### Music Control
- Click **♪** button to toggle music on/off
- Visual pulse animation shows playing state
- Volume persists at 30% for all plays

## 📱 Mobile Optimization

- **Viewport Meta Tag**: Responsive scaling
- **Touch-Friendly**: Large touch targets (50px+ buttons)
- **Flexible Grids**: 2-column layouts on mobile, expand on desktop
- **Readable Fonts**: Minimum 16px on mobile
- **Optimized Images**: Scaled to screen size
- **Scrollable Tables**: Horizontal scroll for link tables on small screens

## 🔧 Customization

### Change Music
Replace `abidoza.aac` with your own audio file:
```html
<audio id="bgMusic" autoplay loop>
    <source src="your-music.aac" type="audio/aac">
</audio>
```

### Update Colors
Edit CSS variables in `<style>` section:
```css
:root {
    --bg-dark: #0a0e27;
    --accent-cyan: #00d4ff;
    --accent-purple: #9d4edd;
    --accent-pink: #ff006e;
}
```

### Modify Retailer Links
Edit the grid buttons in each page section to add/remove retailers or change URLs.

## 📊 Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- iOS Safari: Full support (with audio autoplay limitation)
- Android Chrome: Full support

## ⚠️ Important Notes

### Audio Autoplay
Some browsers require user interaction for audio autoplay. The music will start automatically when first clicked.

### Image Files
All book cover images must be present in the same directory as `index.html` for proper display.

### Mobile Music
iOS Safari may not autoplay audio due to browser restrictions. User must click the music button to start.

## 📞 Support & Contact

For inquiries about the authors:
- **Vanina Vergara**: Schedule via Google Calendar links in content
- **Pablo Mera**: Blog: https://pablomera.blogspot.com/
- **WhatsApp**: http://wa.link/21ft32

## 📄 License

This website is created for and owned by Vanina Vergara and Pablo Mera. All book covers and content are their intellectual property.

---

**Created**: July 2026  
**Version**: 1.0  
**Status**: Ready for GitHub Pages deployment

Enjoy your bilingual bibliography website! 🚀✨
