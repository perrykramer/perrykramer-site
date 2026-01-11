# Case Academy Logo Files

## Files Included

### SVG Files (for web)
- `case-academy-full-wordmark.svg` — Full "Case Academy" + arrow (navy on transparent)
- `case-academy-full-wordmark-white.svg` — Full wordmark for dark backgrounds
- `case-academy-ca-mark.svg` — Abbreviated "CA" + arrow (navy on transparent)
- `case-academy-ca-mark-white.svg` — CA mark for dark backgrounds

### Export Kit
- `logo-export-kit.html` — Open in browser to screenshot PNG exports at various sizes

---

## Typography

**Font:** Space Grotesk  
**Weight:** 700 (Bold)  
**Source:** [Google Fonts](https://fonts.google.com/specimen/Space+Grotesk)

### How to use on your site
Add to your HTML `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@700&display=swap" rel="stylesheet">
```

Or import in CSS:
```css
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@700&display=swap');
```

---

## Brand Colors

| Color  | Hex       | RGB              | Use                     |
|--------|-----------|------------------|-------------------------|
| Navy   | `#1e3a5f` | rgb(30, 58, 95)  | Primary text/wordmark   |
| Amber  | `#f59e0b` | rgb(245, 158, 11)| Arrow accent            |
| White  | `#ffffff` | rgb(255, 255, 255)| Wordmark on dark bg    |

---

## Usage Guidelines

### Full Wordmark
Use for:
- Website header
- Landing page hero
- Email headers (as PNG)
- Presentations

### CA Mark
Use for:
- Favicon
- Social media avatars
- Circle community icon
- Mobile headers
- App icons

### Minimum Sizes
- Full wordmark: 150px wide minimum
- CA mark: 32px wide minimum

### Clear Space
Maintain padding equal to the height of the arrow on all sides.

### Don'ts
- Don't change the colors
- Don't stretch or distort
- Don't add effects (shadows, gradients)
- Don't separate the arrow from the wordmark

---

## Exporting PNGs

1. Open `logo-export-kit.html` in Chrome or Edge
2. Wait for the Space Grotesk font to load
3. Right-click the logo you need → Inspect
4. In DevTools, right-click the `.export-box` element → "Capture node screenshot"
5. Save the PNG

### Recommended exports:
| File | Size | Use |
|------|------|-----|
| `logo-full-800.png` | 800×160 | Hero sections |
| `logo-full-400.png` | 400×80 | ConvertKit email header |
| `ca-mark-512.png` | 512×512 | High-res icon |
| `ca-mark-256.png` | 256×256 | Social avatars |
| `ca-mark-128.png` | 128×128 | Circle community |
| `ca-mark-32.png` | 32×32 | Favicon |

---

## ConvertKit Setup

ConvertKit doesn't support web fonts in emails, so:

1. Export `logo-full-400.png` from the export kit
2. Upload to ConvertKit as your email header image
3. Set alt text to "Case Academy"

For your ConvertKit landing pages (which do support web fonts), you can use the SVG directly or reference the Google Font.

---

## Questions?

Contact: [your email]
