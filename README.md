# Bibliografía

Bilingual bibliography website for authors Vanina Vergara and Pablo Mera. Dark, cinematic design with 3D interactive buttons, full retailer linking, and mobile optimization.

## 📋 Contents

**9 Pages — Spanish & English:**
- **Page #1** — Welcome/Hub with book grid (2×4 layout)
- **Page #2** — *Cuando la Familia se Rompe en Silencio* (Spanish)
- **Page #3** — *Manual del Inadaptado Lúcido* (Spanish)
- **Page #4** — *El Jardín de los que Volvieron* (Spanish)
- **Page #5** — *El Jardín de Luma* (Spanish)
- **Page #6** — *Caracol Menú de Autor* (Spanish)
- **Page #7** — *Caracol Author's Menu* (English)
- **Page #8** — *When Families Fracture in Silence* (English)
- **Page #9** — *The Lucid Misfit's Handbook* (English)

## 🎨 Design Features

- **Dark theme** with neon cyan/green accents
- **3D tilt effects** on mouse move (desktop) and touch (mobile)
- **Sparkling animations** on hero button
- **Floating animations** and smooth transitions
- **Alternating text** (AHORA/COMPRALOS) on hero button
- **Scrolling flag animations** (Paraguay, Spain, Argentina, Uruguay, USA, UK, Australia)
- **Full mobile responsiveness** (2-column grid on mobile, 4-column on desktop)
- **Background images** per page with overlay for text readability
- **Looping background audio** (kelvin.aac) — user interaction required to start
- **Retailer grids** with logo buttons linking to Amazon, MercadoLibre, ThriftBooks, IBS, La Feltrinelli, Books a Million, Bookshop.org, and 10+ more

## 🔗 Links Included

### Internal Navigation
- All 9 pages interconnected via "NEXT" and "PREVIOUS" footer buttons
- Grid buttons on Page #1 link to each book page
- Language selector buttons (ESPAÑOL/ENGLISH)

### External Links
- **11 links per book page** (Kindle, paperback, hardcover, reviews, Spotify, Instagram, Google Calendar, Goodreads, author page, blog)
- **10 retailer buttons per book** (where applicable)
- **WhatsApp hero button** → `http://wa.link/21ft32`
- All URLs verified for functionality

## 📁 Files Required

```
your-repo/
├── index.htm                 (Main HTML file — THIS file)
├── README.md                (This documentation)
├── kelvin.aac               (Background audio — must be in same directory)
└── Images/ (in same directory as index.htm):
    ├── vesp.jpg            (Cuando la Familia Spanish cover)
    ├── pesp.jpg            (Manual del Inadaptado Spanish cover)
    ├── lamp.jpg            (El Jardín de los que Volvieron cover)
    ├── EJDL.jpg            (El Jardín de Luma cover)
    ├── crc.jpg             (Caracol Spanish cover)
    ├── CRCENG.png          (Caracol English cover)
    ├── veng.jpg            (When Families Fracture cover)
    ├── peng.jpg            (The Lucid Misfit's Handbook cover)
    ├── amazon.png          (Retailer logo)
    ├── mercadolibre.png    (Retailer logo)
    ├── th.png              (ThriftBooks logo)
    ├── ibs.png             (IBS Italy logo)
    ├── feltri.png          (La Feltrinelli logo)
    ├── bam.png             (Books a Million logo)
    ├── adlibris.png        (Adlibris logo)
    ├── enbook.jpeg         (Enbook logo)
    ├── better.png          (Better Read logo)
    ├── iber.png            (Iberlibro logo)
    ├── Foyles.png          (Foyles logo)
    ├── big.png             (Big Shopper logo)
    ├── bookshoporg.png     (Bookshop.org logo)
    ├── bookstw.png         (Books.com.tw logo)
    ├── saxo.jpg            (Saxo logo)
    ├── bol.jpg             (Bol.com logo)
    └── libristo.jpg        (Libristo logo)
```

## 🚀 GitHub Pages Deployment

### Option 1: Upload via GitHub Web Interface
1. Create a new GitHub repository named `bibliografica` (or any name)
2. Click "Add file" → "Upload files"
3. Upload `index.htm`, `README.md`, `kelvin.aac`, and all images
4. Commit changes
5. Go to **Settings** → **Pages** → **Build and deployment**
6. Select **Source**: `Deploy from a branch`
7. Select **Branch**: `main` → `/root`
8. Save and wait ~1-2 minutes for deployment
9. Your site will be live at: `https://username.github.io/bibliografica`

### Option 2: Upload via Git Command Line
```bash
# Clone your GitHub repo
git clone https://github.com/username/bibliografica.git
cd bibliografica

# Add all files
git add .

# Commit with message
git commit -m "Add Bibliografía website with 9 pages and retailer links"

# Push to GitHub
git push origin main
```

### Option 3: Using the `trompo01` Account (Existing User)
If you're using your existing GitHub account:
1. Navigate to your repo at `https://github.com/trompo01/bibliografica`
2. Upload files the same way (GitHub web interface or Git CLI)
3. Site will deploy to: `https://trompo01.github.io/bibliografica`

## 🎵 Audio Setup

The website includes looping background audio (`kelvin.aac`):
- **Autoplay policy**: Most browsers require user interaction before audio plays
- **Fallback**: Click anywhere on the page, then audio starts automatically
- **Volume**: Set to 30% to not overwhelm
- **Loop**: Continuous loop throughout navigation

To disable or replace audio:
1. Remove `kelvin.aac` upload
2. Edit `index.htm`, find the JavaScript audio section
3. Comment out or delete the audio initialization code

## 🔍 Link Verification Checklist

All links have been configured and tested:

### ✅ Internal Navigation
- [x] Page 1 → Grid buttons to all 8 book pages
- [x] Page 1 → ESPAÑOL button to Page 2
- [x] Page 1 → ENGLISH button to Page 7
- [x] All pages → NEXT/PREVIOUS footer buttons
- [x] Page 9 → NEXT button returns to Page 1 (circular)

### ✅ External Links (Sample)
- [x] Hero button → WhatsApp: `http://wa.link/21ft32`
- [x] Page 2 → Amazon Paperback: Cuando la Familia...
- [x] Page 2 → MercadoLibre: Cuando la Familia...
- [x] Page 3 → 11 links (Kindle, paperback, Spotify, etc.)
- [x] Page 3 → 8 retailer buttons
- [x] Page 4 → 12 links + 10 retailer buttons
- [x] Page 5 → 12 links + 6 retailer buttons
- [x] Page 6 → 11 links + 10 retailer buttons (Spanish)
- [x] Page 7 → 10 links + 4 retailer buttons (English)
- [x] Page 8 → 9 links + 1 retailer button (Amazon)
- [x] Page 9 → 10 links + 10 retailer buttons

### ✅ Retailer Coverage
- Amazon (all formats: Kindle, paperback, hardcover)
- MercadoLibre (Argentina/Paraguay)
- ThriftBooks
- IBS (Italy)
- La Feltrinelli
- Books a Million
- Bookshop.org
- Adlibris
- Enbook
- Better Read
- Iberlibro
- Foyles
- Big Shopper
- Books.com.tw
- Saxo
- Bol.com
- Libristo

## 📱 Mobile Optimization

- **Responsive grid**: 2 columns on mobile, scales to 4 on desktop
- **Touch-friendly buttons**: Tap zones optimized for Android/iOS
- **3D tilt**: Enabled on desktop, touch equivalent on mobile
- **Fast load**: Single HTML file, no external dependencies
- **Viewport meta tags**: Proper scaling for all device widths

## 🎯 Browser Support

- ✅ Chrome/Chromium (desktop & mobile)
- ✅ Firefox (desktop & mobile)
- ✅ Safari (desktop & mobile)
- ✅ Edge (desktop)
- ⚠️ IE11 (not supported — uses modern CSS/JS)

## ⚙️ Customization

### Change Colors
Edit the CSS variables at the top of `index.htm`:
```css
:root {
    --neon-green: #00ff41;      /* Change this */
    --neon-cyan: #00d9ff;       /* Change this */
    --dark-bg: #0a0e27;         /* Change this */
}
```

### Add/Remove Pages
1. Copy a page `<div class="page">` block
2. Give it a unique `id` (e.g., `id="page10"`)
3. Add navigation buttons calling `goToPage('page10')`
4. Update footer navigation in adjacent pages

### Replace Audio
1. Upload your .aac, .mp3, or .ogg file
2. Edit the `<audio>` src in JavaScript to point to new filename
3. Ensure file is in the same directory as `index.htm`

## 📞 Support & Troubleshooting

### Audio not playing?
- Check browser console for errors (F12 → Console)
- Some browsers require user gesture before autoplay
- Click anywhere on page to trigger audio

### Images not loading?
- Ensure image files are in the same directory as `index.htm`
- Check image filenames match exactly (case-sensitive)
- Verify GitHub Pages deployment completed (check Settings → Pages)

### Links not working?
- Right-click link → "Inspect" to verify `href` attribute
- Test external links in new tab
- Verify WhatsApp link with your account's phone number

### 3D tilt not working?
- Disable in `prefers-reduced-motion` (accessibility setting)
- Mobile touch tilt available with finger movement
- Desktop requires mouse movement over button

## 📄 License

This website and all content are the intellectual property of Vanina Vergara and Pablo Mera.

---

**Version**: 1.0  
**Last Updated**: June 2026  
**Deploy URL**: `https://trompo01.github.io/bibliografica`
