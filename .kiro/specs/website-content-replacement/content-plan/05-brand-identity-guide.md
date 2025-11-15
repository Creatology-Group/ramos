# Brand Identity Guide - Ramos Website

## Document Information
- **Date Created:** 2025-11-15
- **Purpose:** Complete documentation of current brand identity elements
- **Source Files:** index.htm, CSS files, SVG assets

---

## 1. COMPANY NAME & BRANDING

### 1.1 Company Name
- **Current Name:** Ramos
- **Trademark:** Ramos® (with registered trademark symbol)
- **Domain:** ramos.com
- **Email Domain:** @ramos.com

### 1.2 Brand Name Occurrences

#### HTML Locations:
1. **Preloader Section**
   - Location: `.preloader-mark`
   - Text: "Ramos®"
   - Line: ~132

2. **Logo SVG (Text)**
   - Location: `.ramos-logo-second svg`
   - Text: "ramos" (lowercase, as SVG path)
   - Line: ~165

3. **Navigation Email**
   - Location: `.menu-mail`
   - Text: "hello@ramos.com"
   - Line: ~180

4. **CTA Section**
   - Location: `.text-wrapper.cta-s .body-b1`
   - Text: "Start using Ramos today"
   - Line: ~350

5. **Footer Email**
   - Location: `.ramos-mail`
   - Text: "hello@ramos.com"
   - Display: "hello" + "@" + "ramos.com"
   - Line: ~380

6. **Footer Brand Mark**
   - Location: `.footer-ramos-mark`
   - Text: "Ramos®"
   - Line: ~395

7. **Footer Icon SVG**
   - Location: `.footer-svg-icon`
   - SVG logo icon
   - Line: ~398

8. **Form Icon SVG**
   - Location: `.form-svg`
   - SVG logo icon
   - Line: ~420

#### Total Occurrences: 8+ instances
- **With ® symbol:** 2 instances
- **In email addresses:** 2 instances
- **In SVG logos:** 4+ instances
- **In body text:** 1 instance

---

## 2. COLOR PALETTE

### 2.1 Primary Brand Color

#### Orange (#FE4A23)
- **Hex Code:** #FE4A23
- **RGB:** rgb(254, 74, 35)
- **HSL:** hsl(11, 99%, 57%)
- **Color Name:** Vibrant Orange / Coral Red
- **Usage:** Primary brand color, accents, CTAs, buttons, links

#### Locations in HTML/CSS:
1. **Preloader SVG Icons** (Multiple instances)
   - Fill and stroke colors in animated icons
   - Lines: 133-152

2. **Navigation Menu SVG**
   - `.menu-svg` - Arrow decoration
   - Stroke and fill: #FE4A23
   - Line: ~178

3. **Button Circles**
   - `.button-circle.orange`
   - Background color

4. **Inline SVG Icons**
   - Various decorative elements
   - Multiple occurrences throughout

5. **Selection Color**
   - `::selection` pseudo-element
   - Background: #fe4a22 (slight variation)
   - Line: ~10 (in style block)

6. **Confetti Animation**
   - Colors array: ['#FE4A23', '#FFD027']
   - Line: ~900

#### CSS Class References:
- `.button-circle.orange`
- Various inline styles
- SVG fill and stroke attributes

### 2.2 Secondary Colors

#### White (#FFFFFF)
- **Hex Code:** #FFFFFF
- **Usage:** Text on dark backgrounds, button text, icons
- **Locations:** Throughout, especially in SVG icons and overlays

#### Yellow (#FFD027)
- **Hex Code:** #FFD027
- **RGB:** rgb(255, 208, 39)
- **Usage:** Accent color, confetti animation, sticker backgrounds
- **Locations:** 
  - `.radial-sticker.yellow` background
  - Confetti colors array

#### Dark Grey (#0D0D0D)
- **Hex Code:** #0D0D0D
- **RGB:** rgb(13, 13, 13)
- **Usage:** Footer icon, dark text elements
- **Locations:**
  - Footer SVG icon fill
  - Body text color (via CSS variable)

#### Light Grey (#E3E2E2)
- **Hex Code:** #E3E2E2
- **RGB:** rgb(227, 226, 226)
- **Usage:** Grid borders, subtle backgrounds
- **Locations:**
  - Canvas grid stroke color
  - Line: ~715 (in JavaScript)

#### Medium Grey (#B8B8B8)
- **Hex Code:** #B8B8B8
- **RGB:** rgb(184, 184, 184)
- **Usage:** Highlighted grid cells
- **Locations:**
  - Canvas cell highlight
  - Line: ~745 (in JavaScript)

### 2.3 CSS Color Variables
Based on CSS file analysis:
- `--colors--dark-grey`: Used for body text
- Additional color variables may exist in the CSS file

### 2.4 Color Usage Summary

| Color | Hex Code | Primary Use | Frequency |
|-------|----------|-------------|-----------|
| Orange | #FE4A23 | Brand primary, CTAs, accents | Very High (50+ instances) |
| White | #FFFFFF | Text, backgrounds, icons | Very High |
| Yellow | #FFD027 | Accent, stickers | Medium |
| Dark Grey | #0D0D0D | Text, footer elements | High |
| Light Grey | #E3E2E2 | Borders, subtle elements | Low |
| Medium Grey | #B8B8B8 | Interactive highlights | Low |

---

## 3. TYPOGRAPHY

### 3.1 Primary Font Family

#### Urbanist
- **Font Name:** Urbanist
- **Type:** Sans-serif
- **Source:** Google Fonts
- **Fallback:** sans-serif

#### Font Weights Used:
1. **100** - Thin
2. **200** - Extra Light
3. **300** - Light (default body weight)
4. **400** - Regular (normal)
5. **500** - Medium
6. **600** - Semi Bold
7. **700** - Bold
8. **800** - Extra Bold
9. **900** - Black

**Total Weights:** 9 weights loaded

#### Loading Method:
```javascript
WebFont.load({
  google: {
    families: ["Urbanist:100,200,300,regular,500,600,700,800,900"]
  }
});
```

#### CSS Implementation:
```css
body {
  font-family: Urbanist, sans-serif;
  font-size: 1.25rem;
  font-weight: 300;
}
```

### 3.2 Font Size System

#### Base Font Size:
- **Root:** 1rem (responsive, calculated via viewport width)
- **Body:** 1.25rem
- **Responsive Scaling:** Uses viewport width (vw) units

#### Responsive Font Sizing:
```css
/* Desktop (998px - 2800px) */
html { font-size: 1vw; }

/* Large Desktop (2801px+) */
html { font-size: 1vw; }

/* Tablet (480px - 997px) */
html { font-size: 1vw; }

/* Mobile (240px - 479px) */
html { font-size: 3.8vw; }

/* Ultra-wide (1920px+, 21:9 aspect) */
html { font-size: calc(1920px / 100); }
```

### 3.3 Typography Classes

#### Headlines:
- `.headline-h1` - Main hero headlines
- `.headline-h2` - Section headers
- `.subheader` - Subsection headers
- `.form-headline` - Form section headers

#### Body Text:
- `.body-b1` - Primary body text (larger)
- `.body-b2` - Secondary body text (smaller)

#### Special Text:
- `.preloader-mark` - Preloader brand name
- `.footer-ramos-mark` - Footer brand mark
- `.widget-tag` - Widget category tags
- `.sales-text`, `.profit-text` - Widget labels

### 3.4 Font Characteristics

#### Letter Spacing:
- Default (no custom letter-spacing observed)

#### Line Height:
- Default (no custom line-height observed in inline styles)

#### Text Transform:
- Mostly default case
- Some elements may use uppercase via CSS

---

## 4. LOGO SPECIFICATIONS

### 4.1 Logo Components

#### Icon Part (Abstract Symbol)
- **Type:** SVG (inline)
- **ViewBox:** 0 0 20 19
- **Colors:** Uses `currentColor` (inherits from parent)
- **Design:** Abstract geometric shape with interlocking elements
- **Animation:** Rotates 180° on hover
- **CSS Class:** `.ramos-logo-first`

#### Text Part ("ramos")
- **Type:** SVG (inline)
- **ViewBox:** 0 0 66 13
- **Colors:** Uses `currentColor` (inherits from parent)
- **Design:** Custom letterforms spelling "ramos"
- **CSS Class:** `.ramos-logo-second`

### 4.2 Logo Variations

#### Header Logo
- **Location:** `.ramos-logo` in header
- **Display:** Icon + Text (horizontal layout)
- **Color:** Inherits from CSS (likely dark)
- **Size:** Responsive

#### Footer Logo
- **Location:** `.footer-svg-icon`
- **Display:** Icon only (larger version)
- **Color:** #0D0D0D (dark grey)
- **Size:** Larger than header
- **Animation:** Rotates 180° on hover

#### Form Logo
- **Location:** `.form-svg`
- **Display:** Icon only
- **Color:** White
- **Size:** Medium
- **Background:** Orange circular sticker

#### Email Link Logo
- **Location:** `.mail-icon`
- **Display:** Icon only
- **Color:** White
- **Usage:** Appears on hover in email link

### 4.3 Logo Usage Rules (Current)

#### Spacing:
- Logo has adequate padding in header
- Responsive sizing based on viewport

#### Minimum Size:
- Scales down for mobile devices
- Maintains readability at all sizes

#### Color Variations:
- Dark version (header, footer)
- Light version (form, overlays)
- Uses `currentColor` for flexibility

---

## 5. BRAND ASSETS SUMMARY

### 5.1 Favicon & App Icons
- **Favicon:** 32x32px PNG
- **Apple Touch Icon:** 180x180px PNG
- **File Naming:** Uses Webflow CDN naming convention

### 5.2 Social Media Assets
- **Open Graph Image:** 1200x630px PNG
- **Twitter Card Image:** Same as OG image
- **URL:** https://cdn.prod.website-files.com/.../Opengraph.png

---

## 6. BRAND IDENTITY ELEMENTS CHECKLIST

### Colors to Replace:
- [x] Primary Orange (#FE4A23) - 50+ instances
- [x] Yellow Accent (#FFD027) - 5+ instances
- [ ] Consider: Dark Grey (#0D0D0D)
- [ ] Consider: Light/Medium Greys

### Fonts to Replace:
- [x] Urbanist (all 9 weights)
- [ ] Update WebFont.load() call
- [ ] Update CSS font-family declarations

### Logos to Replace:
- [x] Favicon (32x32px PNG)
- [x] Webclip (180x180px PNG)
- [x] Header Logo Icon (SVG)
- [x] Header Logo Text (SVG)
- [x] Footer Logo Icon (SVG)
- [x] Form Logo Icon (SVG)
- [x] Email Logo Icon (SVG)

### Brand Name to Replace:
- [x] "Ramos" text (8+ instances)
- [x] "Ramos®" with trademark (2 instances)
- [x] "ramos.com" domain (2 instances)
- [x] "hello@ramos.com" email (2 instances)

---

## 7. BRAND PERSONALITY (Current)

### Visual Style:
- **Modern:** Clean, contemporary design
- **Bold:** Strong use of vibrant orange
- **Dynamic:** Animated elements, interactive features
- **Professional:** Analytics/data-focused aesthetic
- **Playful:** Hover animations, confetti effects

### Color Psychology:
- **Orange (#FE4A23):** Energy, enthusiasm, innovation, creativity
- **White:** Clarity, simplicity, professionalism
- **Dark Grey:** Sophistication, authority, stability

### Typography Personality:
- **Urbanist:** Modern, geometric, clean, versatile
- **Multiple Weights:** Flexible hierarchy, emphasis options
- **Sans-serif:** Contemporary, approachable, digital-friendly

---

## 8. REPLACEMENT STRATEGY

### Phase 1: Color Replacement
1. **Find & Replace:** Search for #FE4A23 in all files
2. **Update Locations:**
   - Inline SVG fill/stroke attributes
   - CSS classes
   - JavaScript color arrays
   - Selection pseudo-element
3. **Test:** Verify all color changes render correctly

### Phase 2: Font Replacement
1. **Update WebFont.load():** Change font family name
2. **Update CSS:** Modify font-family declarations
3. **Test:** Verify all text renders with new font
4. **Adjust:** Fine-tune weights if needed

### Phase 3: Logo Replacement
1. **Create New SVGs:** Design new logo icon and text
2. **Replace Inline SVGs:** Update SVG path data in HTML
3. **Replace Image Files:** Update favicon and webclip
4. **Test:** Verify all logo instances display correctly

### Phase 4: Brand Name Replacement
1. **Text Content:** Replace all "Ramos" text instances
2. **Email Addresses:** Update email addresses
3. **Domain References:** Update domain name
4. **Trademark Symbols:** Decide on new trademark usage

---

## 9. TECHNICAL NOTES

### Color Format Consistency:
- Most colors use uppercase hex (#FE4A23)
- Some instances use lowercase (#fe4a22)
- Ensure consistency in replacement

### SVG Color Methods:
- **currentColor:** Inherits from parent CSS
- **Direct fill/stroke:** Hardcoded color values
- **CSS classes:** Applied via stylesheets

### Font Loading:
- **Method:** WebFont.js (Google Fonts)
- **Timing:** Loads on page load
- **Fallback:** Generic sans-serif

### Responsive Considerations:
- Font sizes scale with viewport
- Logo sizes adapt to screen size
- Colors remain consistent across breakpoints

---

## 10. BRAND CONSISTENCY CHECKLIST

### Visual Consistency:
- [ ] All orange instances use same hex code
- [ ] Logo appears consistently across all sections
- [ ] Font weights used appropriately for hierarchy
- [ ] Color contrast meets accessibility standards

### Technical Consistency:
- [ ] Color codes formatted consistently (uppercase/lowercase)
- [ ] SVG viewBox dimensions maintained
- [ ] Font weights loaded match usage
- [ ] Responsive scaling works across devices

### Content Consistency:
- [ ] Brand name spelled consistently
- [ ] Trademark symbol used appropriately
- [ ] Email addresses formatted consistently
- [ ] Domain references accurate

---

## 11. ACCESSIBILITY CONSIDERATIONS

### Color Contrast:
- **Orange on White:** High contrast (passes WCAG AA)
- **White on Orange:** High contrast (passes WCAG AA)
- **Dark Grey on White:** High contrast (passes WCAG AAA)

### Font Readability:
- **Minimum Size:** 1.25rem (20px equivalent)
- **Weight Range:** 300-900 (adequate for all uses)
- **Line Length:** Appropriate for readability

### Logo Accessibility:
- **SVG:** Scalable without quality loss
- **Alt Text:** Should be added to logo images
- **Color Independence:** Logo works in monochrome

---

## 12. BRAND ASSETS INVENTORY

### Digital Assets:
- [x] Favicon (PNG, 32x32px)
- [x] Webclip (PNG, 180x180px)
- [x] Logo Icon (SVG, inline)
- [x] Logo Text (SVG, inline)
- [x] OG Image (PNG, 1200x630px)

### Color Swatches:
- [x] Primary Orange (#FE4A23)
- [x] Accent Yellow (#FFD027)
- [x] Dark Grey (#0D0D0D)
- [x] Light Grey (#E3E2E2)
- [x] Medium Grey (#B8B8B8)
- [x] White (#FFFFFF)

### Font Files:
- [x] Urbanist (Google Fonts, 9 weights)

---

## 13. NEXT STEPS FOR REPLACEMENT

### Immediate Actions:
1. **Define New Brand Identity:**
   - Choose new company name
   - Select new primary color
   - Choose new font family
   - Design new logo

2. **Prepare Assets:**
   - Create new logo SVGs
   - Generate favicon and webclip
   - Create OG image
   - Prepare any new images

3. **Update Documentation:**
   - Fill in new brand values
   - Create replacement mapping
   - Document new color codes
   - List new font specifications

4. **Begin Replacement:**
   - Start with high-priority items (logo, colors)
   - Update text content
   - Replace media assets
   - Test thoroughly

---

**Document Status:** Complete
**Last Updated:** 2025-11-15
**Next Steps:** Extract SEO metadata and create replacement templates
