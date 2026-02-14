# Olympic Hockey 2026 - Clean Production Version

Interactive 3D flipbook for the **2026 Milano Cortina Winter Olympics Men's Hockey Tournament**. This is the production-ready version optimized for hosting.

## Features

- **3D Page Flipping**: Realistic page-turning animations
- **Fully Responsive**: 
  - Desktop: Two-page magazine spread (>768px)
  - Mobile: Single-page swipe view (<768px)
- **Olympic Content**:
  - Tournament information and schedules
  - Team rosters with player statistics
  - Olympic hockey history (1920-2026)
  - Historical medals table
- **Dynamic Data**: Loads from `data.json` for easy updates

## Files

```
clean/
├── index.html       ← Main flipbook page
├── flipbook.css     ← Flipbook styles + mobile responsive
├── book.js          ← 3D flipbook engine
├── style.css        ← Additional styling
├── script.js        ← Data loading logic
└── data.json        ← Tournament data (auto-updates)
```

## Usage

### Local Viewing
Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge).

### Hosting
Upload all files in the `clean/` folder to your web host. The page will:
- Load tournament data from `data.json`
- Display with responsive 3D flipbook interface
- Work on desktop and mobile devices

## Navigation

**Desktop:**
- Click left/right page edges to flip
- Two-page spread for magazine experience

**Mobile:**
- Swipe left/right to turn pages
- Single-page view optimized for small screens
- Touch-enabled controls

## Mobile Optimization

At 768px and below:
- Single-page display (no spread)
- Full-width pages for readability
- Swipe navigation
- Optimized touch targets

## Updating Content

To update tournament data:
1. Replace `data.json` with new version
2. Refresh the page

The flipbook automatically loads the latest data without file edits.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Cover Design

**Milano Cortina 2026**
- Olympic rings with decorative lines
- Transparent title overlay
- Official Milano Cortina logo

**Content Sections:**
- Introduction with Olympic history
- Tournament information
- Team rosters and statistics
- Historical medals data

---

*Production version - No ESPN integration or editing controls*
