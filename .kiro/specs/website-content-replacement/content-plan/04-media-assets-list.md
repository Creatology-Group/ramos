# Media Assets Catalog - Ramos Website

## Document Information
- **Date Created:** 2025-11-15
- **Purpose:** Complete catalog of all media assets (images, videos, icons, animations)
- **Source File:** index.htm and asset directories

---

## 1. LOGO ASSETS

### 1.1 Favicon
- **File Path:** `669a3911a488f72cbabca56d/669a3c1a57c3b0f5c2f3036b_faviocn.png`
- **Type:** PNG Image
- **Recommended Dimensions:** 32x32px (standard favicon size)
- **Format:** PNG
- **Usage:** Browser tab icon
- **HTML Reference:** `<link href="..." rel="shortcut icon" type="image/x-icon">`
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement

### 1.2 Apple Touch Icon (Webclip)
- **File Path:** `669a3911a488f72cbabca56d/669a3c1d835c44b0a97cee7a_webclip.png`
- **Type:** PNG Image
- **Recommended Dimensions:** 180x180px (Apple standard)
- **Format:** PNG
- **Usage:** iOS home screen icon
- **HTML Reference:** `<link href="..." rel="apple-touch-icon">`
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement

### 1.3 Main Logo SVG (Inline - Icon Part)
- **Location:** `.ramos-logo-first` (inline SVG in HTML)
- **Type:** Inline SVG
- **Dimensions:** Scalable (viewBox="0 0 20 19")
- **Colors:** Uses `currentColor` (inherits from CSS)
- **Usage:** Header logo icon (animated on hover - rotates 180deg)
- **HTML Location:** Line ~152 in index.htm
- **CSS Class:** `.ramos-logo-first`
- **Animation:** Rotates 180deg on hover
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement
- **Notes:** SVG path data needs to be replaced with new logo design

### 1.4 Main Logo SVG (Inline - Text Part)
- **Location:** `.ramos-logo-second` (inline SVG in HTML)
- **Type:** Inline SVG
- **Dimensions:** Scalable (viewBox="0 0 66 13")
- **Colors:** Uses `currentColor` (inherits from CSS)
- **Usage:** Header logo text "ramos"
- **HTML Location:** Line ~165 in index.htm
- **CSS Class:** `.ramos-logo-second`
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement
- **Notes:** SVG path data spells out "ramos" text

### 1.5 Footer Logo Icon
- **Location:** `.footer-svg-icon` (inline SVG in HTML)
- **Type:** Inline SVG
- **Dimensions:** Scalable (viewBox="0 0 57 57")
- **Colors:** Fill="#0D0D0D" (dark color)
- **Usage:** Footer brand icon (animated on hover - rotates 180deg)
- **CSS Class:** `.ramos-flip-icon`
- **Animation:** Rotates 180deg on hover
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement

### 1.6 Form Pop-up Logo Icon
- **Location:** `.form-svg` (inline SVG in form)
- **Type:** Inline SVG
- **Dimensions:** Scalable (viewBox="0 0 20 20")
- **Colors:** Fill="white"
- **Usage:** Form header icon
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement

### 1.7 Email Link Logo Icon
- **Location:** `.mail-icon` (inline SVG in footer)
- **Type:** Inline SVG
- **Dimensions:** Scalable (viewBox="0 0 48 49")
- **Colors:** Fill="white"
- **Usage:** Email link hover animation
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement

---

## 2. VIDEO ASSETS

### 2.1 Hero Video
- **File Path:** `s/87iozgh1s9pw46j3cn49i/ramos-promo-half.mp4`
- **Type:** MP4 Video
- **Estimated Dimensions:** 1920x1080 or similar (HD)
- **Format:** MP4
- **Usage:** Hero section background video
- **HTML Element:** `<video>` with id="heroVideo"
- **Attributes:** loop, playsinline, autoplay, muted
- **Controls:** Custom play/pause button
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement
- **Notes:** 
  - Video plays automatically on page load
  - Has custom play/pause controls
  - Pauses when scrolled out of view
  - Should be optimized for web (compressed)

---

## 3. LOTTIE ANIMATIONS

### 3.1 Hero Sticker Animation 1
- **File Path:** `https://cdn.prod.website-files.com/66e58efe40dd6395918050ce/66e58efe40dd63959180513d_vidget22.json`
- **Type:** Lottie JSON Animation
- **Duration:** 3.033 seconds
- **Usage:** Hero section animated sticker (grey background)
- **CSS Class:** `.radial-sticker.grey`
- **Priority:** MEDIUM
- **Status:** ⬜ Decide: Keep or Replace
- **Notes:** Interactive animation triggered on hover

### 3.2 Hero Sticker Animation 2
- **File Path:** `https://cdn.prod.website-files.com/66e58efe40dd6395918050ce/66e58efe40dd63959180511f_vidget23.json`
- **Type:** Lottie JSON Animation
- **Duration:** 3.033 seconds
- **Usage:** Hero section animated sticker (orange background)
- **CSS Class:** `.radial-sticker.orange`
- **Priority:** MEDIUM
- **Status:** ⬜ Decide: Keep or Replace
- **Notes:** Interactive animation triggered on hover

### 3.3 Hero Sticker Animation 3
- **File Path:** `https://cdn.prod.website-files.com/66e58efe40dd6395918050ce/66e58efe40dd639591805150_vidget24.json`
- **Type:** Lottie JSON Animation
- **Duration:** 4.367 seconds
- **Usage:** Hero section animated sticker (yellow background)
- **CSS Class:** `.radial-sticker.yellow`
- **Priority:** MEDIUM
- **Status:** ⬜ Decide: Keep or Replace
- **Notes:** Interactive animation triggered on hover

---

## 4. FEATURE SECTION IMAGES

### 4.1 iPad Mockup
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd6395918050ff_ipad.svg`
- **Type:** SVG Image
- **Format:** SVG
- **Usage:** Widget/feature section device mockup
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update
- **Notes:** May need color adjustments to match new brand

### 4.2 iPad Elements Top
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805113_ipad-elements-top.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** UI elements overlay for iPad mockup
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.3 iPad Elements Down
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805169_ipad-down-elements-2.svg`
- **Type:** SVG Image
- **Format:** SVG
- **Usage:** UI elements overlay for iPad mockup (bottom)
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.4 Phone Elements Top
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805136_phone-elements-top.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** UI elements overlay for phone mockup
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.5 Phone Elements Down
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805166_phone-elements-down.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** UI elements overlay for phone mockup (bottom)
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.6 Card Grid
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180511a_card-grid.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** Card layout visualization
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.7 Mobile Grid
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180513b_mobile-grid-p.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** Mobile grid layout visualization
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.8 Widget Statistic
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180515b_widget-statistic.svg`
- **Type:** SVG Image
- **Format:** SVG
- **Usage:** Statistics widget visualization
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

### 4.9 Ramos Icon/Logo
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805117_ramos.svg`
- **Type:** SVG Image
- **Format:** SVG
- **Usage:** Company icon/logo in features
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement

---

## 5. BACKGROUND IMAGES

### 5.1 Ramos Background
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180511e_ramos-bg.jpg`
- **Type:** JPG Image
- **Format:** JPG
- **Usage:** Background image
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update
- **Notes:** May need to match new brand colors

### 5.2 CTA Icon Background
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180515c_cta-icon-bg.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** CTA section icon background
- **Priority:** LOW
- **Status:** ⬜ Needs Replacement or Update

---

## 6. FORM SECTION IMAGES

### 6.1 Form iPad Mockup
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805165_fomr-ipad.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** Form popup iPad mockup
- **CSS Class:** `.form-ipad`
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update
- **Notes:** Filename has typo "fomr" instead of "form"

### 6.2 Form Banner
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd63959180516c_form-banner.png`
- **Type:** PNG Image
- **Format:** PNG
- **Usage:** Form popup banner image
- **CSS Class:** `.form-banner`
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement or Update

---

## 7. AVATAR/PROFILE IMAGES

### 7.1 Avatar 1
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd6395918050ee_avatar-2435.jpg`
- **Type:** JPG Image
- **Format:** JPG
- **Usage:** User avatar/profile image
- **Priority:** LOW
- **Status:** ⬜ Needs Replacement
- **Notes:** Replace with new team member or testimonial photo

### 7.2 Avatar 2
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd639591805103_avatar-2436.jpg`
- **Type:** JPG Image
- **Format:** JPG
- **Usage:** User avatar/profile image
- **Priority:** LOW
- **Status:** ⬜ Needs Replacement
- **Notes:** Replace with new team member or testimonial photo

### 7.3 Video Cover
- **File Path:** `66e58efe40dd6395918050ce/66e58efe40dd6395918050ef_video-cover.jpg`
- **Type:** JPG Image
- **Format:** JPG
- **Usage:** Video thumbnail/cover image
- **Priority:** MEDIUM
- **Status:** ⬜ Needs Replacement

---

## 8. INLINE SVG ICONS

### 8.1 Navigation Arrow Icon
- **Location:** `.menu-svg` (inline SVG)
- **Type:** Inline SVG
- **Dimensions:** viewBox="0 0 360 80"
- **Colors:** Stroke="#FE4A23" (orange), Fill="#FE4A23"
- **Usage:** Navigation menu decoration
- **Priority:** MEDIUM
- **Status:** ⬜ Update Colors

### 8.2 Profit Icon
- **Location:** `.progit-icon-svg` (inline SVG)
- **Type:** Inline SVG
- **Dimensions:** viewBox="0 0 19 20"
- **Colors:** Stroke="white", Fill="white"
- **Usage:** Profit widget icon
- **Priority:** LOW
- **Status:** ⬜ Keep or Replace

### 8.3 Play/Pause Button Icons
- **Location:** `.play-svg` and `.pause-svg` (inline SVG)
- **Type:** Inline SVG
- **Dimensions:** viewBox="0 0 12 15" and "0 0 14 16"
- **Colors:** Fill="white"
- **Usage:** Video controls
- **Priority:** LOW
- **Status:** ⬜ Keep (functional icons)

### 8.4 Close Form Icon
- **Location:** `.close-form-svg` (inline SVG)
- **Type:** Inline SVG
- **Dimensions:** viewBox="0 0 24 24"
- **Colors:** Stroke="currentColor"
- **Usage:** Close button for form popup
- **Priority:** LOW
- **Status:** ⬜ Keep (functional icon)

---

## 9. EXTERNAL SCRIPTS AND LIBRARIES

### 9.1 Lenis Smooth Scroll
- **File Path:** `66e58efe40dd6395918050ce/6721f90a00f356aaaaa63b0e_lenis.txt`
- **Type:** JavaScript Library
- **Usage:** Smooth scrolling functionality
- **Priority:** LOW
- **Status:** ✅ Keep (functional script)

### 9.2 Canvas Confetti
- **File Path:** `npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js`
- **Type:** JavaScript Library
- **Usage:** Confetti animation on form success
- **Priority:** LOW
- **Status:** ✅ Keep (functional script)

### 9.3 WebFont Loader
- **File Path:** `ajax/libs/webfont/1.6.26/webfont.js`
- **Type:** JavaScript Library
- **Usage:** Google Fonts loading
- **Priority:** LOW
- **Status:** ✅ Keep (functional script)

---

## 10. CSS FILES

### 10.1 Main Stylesheet
- **File Path:** `66e58efe40dd6395918050ce/css/ramos-app.webflow.shared.dfcd8d708.css`
- **Type:** CSS Stylesheet
- **Usage:** Main website styles
- **Priority:** HIGH
- **Status:** ⬜ Update Colors and Fonts
- **Notes:** Contains brand colors (#FE4A23) that need updating

---

## 11. JAVASCRIPT FILES

### 11.1 jQuery
- **File Path:** `js/jquery-3.5.1.min.dc5e7f18c8.js`
- **Type:** JavaScript Library
- **Version:** 3.5.1
- **Usage:** Core JavaScript functionality
- **Priority:** LOW
- **Status:** ✅ Keep

### 11.2 Webflow Scripts
- **File Path 1:** `66e58efe40dd6395918050ce/js/webflow.schunk.57d5559d2f0cd9f8.js`
- **File Path 2:** `66e58efe40dd6395918050ce/js/webflow.schunk.aabe4bb50d231560.js`
- **File Path 3:** `66e58efe40dd6395918050ce/js/webflow.f95ebecf.e685dbfe816c3bce.js`
- **Type:** JavaScript
- **Usage:** Webflow interactions and animations
- **Priority:** LOW
- **Status:** ✅ Keep

---

## 12. SOCIAL MEDIA / SEO IMAGES

### 12.1 Open Graph Image
- **File Path:** `https://cdn.prod.website-files.com/669a3911a488f72cbabca56d/66e2a2f99cd9c144f25d469f_Opengraph.png`
- **Type:** PNG Image
- **Recommended Dimensions:** 1200x630px (Facebook/LinkedIn standard)
- **Format:** PNG
- **Usage:** Social media preview image (og:image, twitter:image)
- **Priority:** HIGH
- **Status:** ⬜ Needs Replacement
- **Notes:** Used for Facebook, Twitter, LinkedIn previews

---

## 13. SUMMARY STATISTICS

### Total Media Assets: 40+

### By Type:
- **Logo Assets:** 7 items (HIGH priority)
- **Videos:** 1 item (HIGH priority)
- **Lottie Animations:** 3 items (MEDIUM priority)
- **Feature Images:** 9 items (MEDIUM priority)
- **Background Images:** 2 items (MEDIUM priority)
- **Form Images:** 2 items (MEDIUM priority)
- **Avatar Images:** 3 items (LOW priority)
- **Inline SVG Icons:** 8+ items (MIXED priority)
- **External Scripts:** 3 items (Keep)
- **CSS Files:** 1 item (Update)
- **JavaScript Files:** 4 items (Keep)
- **Social Media Images:** 1 item (HIGH priority)

### By Priority:
- **HIGH Priority:** 10 items (logos, video, OG image)
- **MEDIUM Priority:** 16 items (feature images, animations)
- **LOW Priority:** 8 items (avatars, functional icons)
- **Keep As-Is:** 8 items (scripts, libraries)

### File Formats:
- **PNG:** 10 files
- **JPG:** 4 files
- **SVG:** 10+ files (inline and external)
- **MP4:** 1 file
- **JSON:** 3 files (Lottie animations)
- **CSS:** 1 file
- **JS:** 7 files

---

## 14. REPLACEMENT GUIDELINES

### Image Specifications:

#### Logos:
- **Favicon:** 32x32px, PNG, transparent background
- **Webclip:** 180x180px, PNG, can have background
- **Main Logo SVG:** Scalable, use currentColor for flexibility
- **OG Image:** 1200x630px, PNG or JPG

#### Hero Video:
- **Format:** MP4 (H.264 codec recommended)
- **Dimensions:** 1920x1080px (Full HD) or 1280x720px (HD)
- **Duration:** Keep similar to original (estimate 10-30 seconds)
- **File Size:** Compress for web (target < 5MB)
- **Attributes:** Must support autoplay, loop, muted

#### Feature Images:
- **Format:** PNG for UI elements (transparency), JPG for photos
- **Dimensions:** Match original or scale proportionally
- **Optimization:** Compress for web performance

#### Lottie Animations:
- **Format:** JSON
- **Duration:** 3-5 seconds recommended
- **File Size:** Keep under 100KB per animation
- **Decision:** Determine if keeping or replacing with new animations

---

## 15. ASSET NAMING CONVENTION

### Recommended Structure:
```
new-content/
├── images/
│   ├── logo/
│   │   ├── favicon.png (32x32)
│   │   ├── webclip.png (180x180)
│   │   ├── main-logo.svg
│   │   └── og-image.png (1200x630)
│   ├── hero/
│   │   └── hero-video.mp4
│   ├── features/
│   │   ├── ipad-mockup.svg
│   │   ├── phone-mockup.svg
│   │   └── [other feature images]
│   └── icons/
│       └── [various icons]
└── videos/
    └── hero-video.mp4
```

---

## 16. NOTES AND OBSERVATIONS

### Color Dependencies:
- Many SVG icons use `currentColor` - will automatically adapt to new brand colors
- Some SVGs have hardcoded colors (#FE4A23, white, #0D0D0D) that need updating
- Background images may need color adjustments

### Animation Considerations:
- Logo icons have rotation animations on hover
- Lottie animations are interactive (triggered on hover/scroll)
- Video has custom controls and viewport detection

### Optimization Opportunities:
- Compress all images for web
- Consider WebP format for better compression
- Lazy load below-fold images
- Use responsive images with srcset

### Accessibility:
- All images should have appropriate alt text
- Decorative images should have empty alt=""
- Video should have captions/subtitles option

---

**Document Status:** Complete
**Last Updated:** 2025-11-15
**Next Steps:** Document brand identity elements (colors, fonts)
