# Website Content Replacement Checklist

## Document Information
- **Purpose:** Track all content replacement tasks with verification steps
- **Date Created:** 2025-11-15
- **Status:** Ready for use
- **Priority Legend:** 🔴 High | 🟡 Medium | 🟢 Low

---

## How to Use This Checklist

1. **Work by priority** - Complete all 🔴 High priority items first
2. **Check boxes** as you complete each item
3. **Verify** using the verification steps provided
4. **Document issues** in the Notes column
5. **Get approval** before moving to next priority level

---

## PRIORITY: 🔴 HIGH (Critical for Launch)

### Brand Identity Elements

- [ ] **Replace company name "Ramos" in preloader**
  - Location: `.preloader-mark`
  - Verification: Load page and check preloader animation
  - Notes: _______________

- [ ] **Replace company name in footer brand mark**
  - Location: `.footer-ramos-mark`
  - Verification: Scroll to footer and verify text
  - Notes: _______________

- [ ] **Replace company name in CTA description**
  - Location: `.cta-sc .body-b1`
  - Current: "Start using Ramos today"
  - Verification: Check CTA section text
  - Notes: _______________

- [ ] **Search and replace all remaining "Ramos" occurrences**
  - Method: Use find/replace in code editor
  - Verification: Search HTML for "Ramos" (case-insensitive)
  - Notes: _______________

### Logo Assets

- [ ] **Replace favicon (32x32px PNG)**
  - Old: `669a3911a488f72cbabca56d/669a3c1a57c3b0f5c2f3036b_faviocn.png`
  - New: `new-content/images/logo/favicon.png`
  - Verification: Check browser tab icon
  - Notes: _______________

- [ ] **Replace webclip/Apple touch icon (180x180px PNG)**
  - Old: `669a3911a488f72cbabca56d/669a3c1d835c44b0a97cee7a_webclip.png`
  - New: `new-content/images/logo/webclip.png`
  - Verification: Add to iOS home screen and check icon
  - Notes: _______________

- [ ] **Replace main logo SVG in header**
  - Location: `.ramos-logo-second svg` (inline SVG)
  - Verification: Check header logo displays correctly
  - Notes: _______________

- [ ] **Replace logo SVG in footer**
  - Location: Footer inline SVG
  - Verification: Check footer logo displays correctly
  - Notes: _______________

- [ ] **Replace company icon SVG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805117_ramos.svg`
  - New: `new-content/images/icons/company-icon.svg`
  - Verification: Check where icon appears
  - Notes: _______________

### Primary Brand Color

- [ ] **Replace primary color #FE4A23 in all inline styles**
  - Method: Find/replace in HTML
  - Verification: Visual inspection of all orange elements
  - Notes: _______________

- [ ] **Update button colors**
  - Location: `.button-circle.orange` and related classes
  - Verification: Check all buttons render correctly
  - Notes: _______________

- [ ] **Update SVG fill colors**
  - Location: Various inline SVG elements
  - Verification: Check all icons and graphics
  - Notes: _______________


### Hero Section Content

- [ ] **Replace hero main headline**
  - Location: `.headline-h1.hero-hide`
  - Current: "Analytics that helps you shape the future"
  - Verification: Check hidden SEO headline and visible animated text
  - Notes: _______________

- [ ] **Update hero animated headline parts**
  - Locations: Multiple spans with animation
  - Verification: Watch full headline animation
  - Notes: _______________

- [ ] **Replace hero video**
  - Old: `s/87iozgh1s9pw46j3cn49i/ramos-promo-half.mp4`
  - New: `new-content/videos/hero-video.mp4`
  - Verification: Video plays correctly, no errors
  - Notes: _______________

### Key Features Section

- [ ] **Replace section header**
  - Location: `.widgets-sc .header-block .headline-h2`
  - Current: "Your key to strategic success through analytics"
  - Verification: Check section title displays correctly
  - Notes: _______________

- [ ] **Replace section description**
  - Location: `.widgets-sc .text-wrapper.widgets-s p.body-b2`
  - Current: "Ready for exciting, instantaneous..."
  - Verification: Check subtitle text
  - Notes: _______________

- [ ] **Replace left widget subheader**
  - Location: `.left-widget-text-content .subheader`
  - Current: "Fast and easy access to analytics"
  - Verification: Check feature title
  - Notes: _______________

### Solutions Section

- [ ] **Replace section header**
  - Location: `.control-sc .headline-h2`
  - Current: "Gain control over your data"
  - Verification: Check section title
  - Notes: _______________

- [ ] **Replace section description**
  - Location: `.control-sc .body-b2`
  - Current: "Bring together all your data..."
  - Verification: Check subtitle
  - Notes: _______________


### Tools Section

- [ ] **Replace section header**
  - Location: `.tools-sc .headline-h2`
  - Current: "Powerful tools for data-driven decisions"
  - Verification: Check section title
  - Notes: _______________

- [ ] **Replace section description**
  - Location: `.tools-sc .body-b2`
  - Current: "Leverage advanced analytics tools..."
  - Verification: Check subtitle
  - Notes: _______________

### Call-to-Action Section

- [ ] **Replace CTA header**
  - Location: `.cta-sc .headline-h1`
  - Current: "Get Started"
  - Verification: Check animated headline
  - Notes: _______________

- [ ] **Replace CTA button 1 text**
  - Location: `.main-button.first-view .button-text`
  - Current: "Request a demo"
  - Verification: Check button text and functionality
  - Notes: _______________

- [ ] **Replace CTA button 2 text**
  - Location: `.main-button.second-view .button-text`
  - Current: "Start for free"
  - Verification: Check button text and functionality
  - Notes: _______________

### Contact Information

- [ ] **Replace email in header menu**
  - Location: `.menu-mail`
  - Current: "hello@ramos.com"
  - Verification: Check mailto link works
  - Notes: _______________

- [ ] **Replace email in footer**
  - Location: `.ramos-mail`
  - Current: "hello@ramos.com"
  - Verification: Check mailto link works
  - Notes: _______________

### SEO Metadata

- [ ] **Replace page title**
  - Location: `<title>` tag
  - Current: "Ramos"
  - Verification: Check browser tab title
  - Notes: _______________

- [ ] **Replace og:title**
  - Location: `<meta property="og:title">`
  - Current: "Ramos"
  - Verification: Test with Facebook Debugger
  - Notes: _______________

- [ ] **Replace og:image**
  - Location: `<meta property="og:image">`
  - New: Upload 1200x630px image
  - Verification: Test with Facebook Debugger
  - Notes: _______________

- [ ] **Replace twitter:title**
  - Location: `<meta name="twitter:title">`
  - Current: "Ramos"
  - Verification: Test with Twitter Card Validator
  - Notes: _______________

- [ ] **Replace twitter:image**
  - Location: `<meta name="twitter:image">`
  - New: Upload 1200x675px image
  - Verification: Test with Twitter Card Validator
  - Notes: _______________


---

## PRIORITY: 🟡 MEDIUM (Important but Not Blocking)

### Navigation Menu

- [ ] **Replace nav item 1**
  - Location: `a[data-navlink='1']`
  - Current: "Key Features"
  - Verification: Click link, verify navigation works
  - Notes: _______________

- [ ] **Replace nav item 2**
  - Location: `a[data-navlink='2']`
  - Current: "Explore"
  - Verification: Click link, verify navigation works
  - Notes: _______________

- [ ] **Replace nav item 3**
  - Location: `a[data-navlink='3']`
  - Current: "Solutions"
  - Verification: Click link, verify navigation works
  - Notes: _______________

- [ ] **Replace nav item 4**
  - Location: `a[data-navlink='4']`
  - Current: "Tools"
  - Verification: Click link, verify navigation works
  - Notes: _______________

- [ ] **Replace nav item 5**
  - Location: `a[data-navlink='5']`
  - Current: "Contact"
  - Verification: Click link, verify navigation works
  - Notes: _______________

- [ ] **Replace sign up button in header**
  - Location: `.main-button.menu .button-text`
  - Current: "Sign Up"
  - Verification: Check button displays correctly
  - Notes: _______________

### Explore Section (Right Widget)

- [ ] **Replace widget tag**
  - Location: `.widget-right .widget-tag`
  - Current: "Monitoring"
  - Verification: Check tag displays
  - Notes: _______________

- [ ] **Replace subheader**
  - Location: `.widget-right .subheader`
  - Current: "Monitoring 24 hours a day"
  - Verification: Check title displays
  - Notes: _______________

- [ ] **Replace description**
  - Location: `.widget-right .body-b1.middle-grey`
  - Current: "Collect data in real time..."
  - Verification: Check description displays
  - Notes: _______________

### Solution Cards

- [ ] **Replace Card 1 tag**
  - Current: "Dashboards"
  - Verification: Check card 1 tag
  - Notes: _______________

- [ ] **Replace Card 1 title**
  - Current: "Customizable dashboards"
  - Verification: Check card 1 title
  - Notes: _______________

- [ ] **Replace Card 1 description**
  - Current: "Tailor your dashboard..."
  - Verification: Check card 1 description
  - Notes: _______________

- [ ] **Replace Card 2 tag**
  - Current: "Integrations"
  - Verification: Check card 2 tag
  - Notes: _______________

- [ ] **Replace Card 2 title**
  - Current: "Seamless integrations"
  - Verification: Check card 2 title
  - Notes: _______________

- [ ] **Replace Card 2 description**
  - Current: "Connect with your favorite tools..."
  - Verification: Check card 2 description
  - Notes: _______________

- [ ] **Replace Card 3 tag**
  - Current: "Security"
  - Verification: Check card 3 tag
  - Notes: _______________

- [ ] **Replace Card 3 title**
  - Current: "Advanced security"
  - Verification: Check card 3 title
  - Notes: _______________

- [ ] **Replace Card 3 description**
  - Current: "Rest easy knowing..."
  - Verification: Check card 3 description
  - Notes: _______________


### Media Assets - Features

- [ ] **Replace iPad mockup SVG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd6395918050ff_ipad.svg`
  - New: `new-content/images/features/ipad-mockup.svg`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace iPad elements top PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805113_ipad-elements-top.png`
  - New: `new-content/images/features/ipad-elements-top.png`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace phone elements top PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805136_phone-elements-top.png`
  - New: `new-content/images/features/phone-elements-top.png`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace card grid PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180511a_card-grid.png`
  - New: `new-content/images/features/card-grid.png`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace mobile grid PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180513b_mobile-grid-p.png`
  - New: `new-content/images/features/mobile-grid.png`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace form banner PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180516c_form-banner.png`
  - New: `new-content/images/features/form-banner.png`
  - Verification: Check image displays correctly
  - Notes: _______________

- [ ] **Replace form iPad PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805165_fomr-ipad.png`
  - New: `new-content/images/features/form-ipad.png`
  - Verification: Check image displays correctly
  - Notes: _______________

### Form Pop-up Content

- [ ] **Replace form header**
  - Location: `.form-block .form-headline`
  - Current: "Get Access"
  - Verification: Open form modal, check header
  - Notes: _______________

- [ ] **Replace form description**
  - Location: `.form-block .body-b2`
  - Current: "Create your account and dive into..."
  - Verification: Check form description
  - Notes: _______________

- [ ] **Replace form submit button**
  - Location: `.main-button.form-s .button-text`
  - Current: "Sign Up"
  - Verification: Check button text
  - Notes: _______________

- [ ] **Replace success message header**
  - Location: `.success-message .form-headline`
  - Current: "Request submited"
  - Verification: Submit form, check success message
  - Notes: _______________

- [ ] **Replace success message description**
  - Location: `.success-message .body-b2`
  - Current: "Thank you for your interest..."
  - Verification: Check success description
  - Notes: _______________

### Footer Content

- [ ] **Replace footer nav link 1**
  - Current: "Key Features"
  - Verification: Check footer navigation
  - Notes: _______________

- [ ] **Replace footer nav link 2**
  - Current: "Explore"
  - Verification: Check footer navigation
  - Notes: _______________

- [ ] **Replace footer nav link 3**
  - Current: "Solutions"
  - Verification: Check footer navigation
  - Notes: _______________

- [ ] **Replace footer nav link 4**
  - Current: "Tools"
  - Verification: Check footer navigation
  - Notes: _______________

- [ ] **Update address 1**
  - Location: `.adress-text.set-1`
  - Current: Raleigh office
  - Verification: Check address displays correctly
  - Notes: _______________

- [ ] **Update address 2**
  - Location: `.adress-text.set-2`
  - Current: Charlotte office
  - Verification: Check address displays correctly
  - Notes: _______________

### SEO - Additional Tags

- [ ] **Add meta description**
  - Location: Add `<meta name="description">`
  - Verification: Check HTML source
  - Notes: _______________

- [ ] **Add og:description**
  - Location: Add `<meta property="og:description">`
  - Verification: Test with Facebook Debugger
  - Notes: _______________

- [ ] **Add og:url**
  - Location: Add `<meta property="og:url">`
  - Verification: Check HTML source
  - Notes: _______________

- [ ] **Add og:type**
  - Location: Add `<meta property="og:type" content="website">`
  - Verification: Check HTML source
  - Notes: _______________

- [ ] **Add twitter:description**
  - Location: Add `<meta name="twitter:description">`
  - Verification: Test with Twitter Card Validator
  - Notes: _______________

- [ ] **Add twitter:card**
  - Location: Add `<meta name="twitter:card" content="summary_large_image">`
  - Verification: Check HTML source
  - Notes: _______________


---

## PRIORITY: 🟢 LOW (Nice to Have)

### Preloader

- [ ] **Replace preloader status text**
  - Location: `.preloader-text`
  - Current: "Data Processing"
  - Verification: Reload page, watch preloader
  - Notes: _______________

### Widget Details

- [ ] **Replace left widget tag**
  - Location: `.widget-tag`
  - Current: "Setting up reports"
  - Verification: Check widget tag
  - Notes: _______________

- [ ] **Replace left widget description**
  - Location: `.left-widget-text-content .body-b1.middle-grey`
  - Current: "One platform is a comprehensive system..."
  - Verification: Check widget description
  - Notes: _______________

- [ ] **Replace sales statistic label**
  - Location: `.sales-text`
  - Current: "Sales statistic"
  - Verification: Check chart label
  - Notes: _______________

- [ ] **Replace profit label**
  - Location: `.profit-text`
  - Current: "Profit"
  - Verification: Check metric label
  - Notes: _______________

- [ ] **Update profit value**
  - Location: `.profit-value`
  - Current: "$742k"
  - Verification: Check metric value
  - Notes: _______________

### Media Assets - Optional

- [ ] **Replace video cover image**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd6395918050ef_video-cover.jpg`
  - New: `new-content/images/hero/video-cover.jpg`
  - Verification: Check video poster image
  - Notes: _______________

- [ ] **Replace iPad elements down SVG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805169_ipad-down-elements-2.svg`
  - New: `new-content/images/features/ipad-elements-down.svg`
  - Verification: Check image displays
  - Notes: _______________

- [ ] **Replace phone elements down PNG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805166_phone-elements-down.png`
  - New: `new-content/images/features/phone-elements-down.png`
  - Verification: Check image displays
  - Notes: _______________

- [ ] **Replace widget statistic SVG**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180515b_widget-statistic.svg`
  - New: `new-content/images/features/widget-statistic.svg`
  - Verification: Check widget graphic
  - Notes: _______________

- [ ] **Replace background image**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180511e_ramos-bg.jpg`
  - New: `new-content/images/backgrounds/main-bg.jpg`
  - Verification: Check background displays
  - Notes: _______________

- [ ] **Replace CTA icon background**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd63959180515c_cta-icon-bg.png`
  - New: `new-content/images/backgrounds/cta-icon-bg.png`
  - Verification: Check CTA section background
  - Notes: _______________

- [ ] **Replace avatar 1**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd6395918050ee_avatar-2435.jpg`
  - New: `new-content/images/avatars/avatar-1.jpg`
  - Verification: Check avatar displays
  - Notes: _______________

- [ ] **Replace avatar 2**
  - Old: `66e58efe40dd6395918050ce/66e58efe40dd639591805103_avatar-2436.jpg`
  - New: `new-content/images/avatars/avatar-2.jpg`
  - Verification: Check avatar displays
  - Notes: _______________

### Form Labels

- [ ] **Replace name input label**
  - Location: `.input-lable:nth-child(1)`
  - Current: "Hello, My name is"
  - Verification: Open form, check label
  - Notes: _______________

- [ ] **Replace email input label**
  - Location: `.input-lable:nth-child(2)`
  - Current: "My contact Email"
  - Verification: Open form, check label
  - Notes: _______________

- [ ] **Replace success return button**
  - Location: `.success-message .button-text`
  - Current: "Return to home"
  - Verification: Submit form, check button
  - Notes: _______________

### Footer Optional

- [ ] **Update footer credit line**
  - Location: `.adress-span.made-by`
  - Current: "Made by Outcrowd"
  - Verification: Check footer credit
  - Notes: _______________

### SEO - Optional Tags

- [ ] **Add robots meta tag**
  - Location: Add `<meta name="robots" content="index, follow">`
  - Verification: Check HTML source
  - Notes: _______________

- [ ] **Add canonical link**
  - Location: Add `<link rel="canonical" href="[URL]">`
  - Verification: Check HTML source
  - Notes: _______________


---

## VERIFICATION PROCEDURES

### Text Content Verification

**Step 1: Visual Inspection**
- [ ] Load website in browser
- [ ] Scroll through entire page
- [ ] Check all sections for old company name
- [ ] Verify all text is readable and properly formatted

**Step 2: Search for Old Content**
- [ ] Open HTML file in text editor
- [ ] Search for "Ramos" (case-insensitive)
- [ ] Search for "ramos.com"
- [ ] Search for old email addresses
- [ ] Verify all instances replaced or intentional

**Step 3: Link Testing**
- [ ] Click all navigation links
- [ ] Test all buttons
- [ ] Verify email mailto links work
- [ ] Check external links (if any)

### Media Assets Verification

**Step 1: Image Loading**
- [ ] Check browser console for 404 errors
- [ ] Verify all images load correctly
- [ ] Check image quality and sizing
- [ ] Test on different screen sizes

**Step 2: Video Verification**
- [ ] Verify hero video plays
- [ ] Check video quality
- [ ] Test on different browsers
- [ ] Verify poster image displays before play

**Step 3: Logo Verification**
- [ ] Check favicon in browser tab
- [ ] Verify header logo displays
- [ ] Check footer logo displays
- [ ] Test Apple touch icon (add to home screen on iOS)

### Brand Identity Verification

**Step 1: Color Consistency**
- [ ] Check all buttons use new primary color
- [ ] Verify accent colors throughout site
- [ ] Check hover states
- [ ] Verify SVG icon colors

**Step 2: Typography**
- [ ] Verify new font loads correctly
- [ ] Check all font weights display properly
- [ ] Test fallback fonts
- [ ] Verify text is readable on all backgrounds

**Step 3: Overall Brand Consistency**
- [ ] Compare to brand guidelines
- [ ] Check for visual consistency
- [ ] Verify tone and messaging align
- [ ] Get stakeholder approval

### SEO Metadata Verification

**Step 1: HTML Source Check**
- [ ] View page source
- [ ] Verify all meta tags present
- [ ] Check for duplicate tags
- [ ] Verify tag content is correct

**Step 2: Social Media Preview Testing**
- [ ] Test with Facebook Debugger (https://developers.facebook.com/tools/debug/)
- [ ] Test with Twitter Card Validator (https://cards-dev.twitter.com/validator)
- [ ] Test with LinkedIn Post Inspector
- [ ] Verify images and text display correctly

**Step 3: SEO Tools**
- [ ] Run through Google's Rich Results Test
- [ ] Check with SEO browser extension
- [ ] Verify structured data (if applicable)
- [ ] Test mobile-friendliness

### Responsive Design Verification

**Desktop Testing**
- [ ] Test at 1920px width
- [ ] Test at 1366px width
- [ ] Test at 1024px width

**Tablet Testing**
- [ ] Test at 768px width (portrait)
- [ ] Test at 1024px width (landscape)
- [ ] Verify touch interactions work

**Mobile Testing**
- [ ] Test at 375px width (iPhone)
- [ ] Test at 414px width (iPhone Plus)
- [ ] Test at 360px width (Android)
- [ ] Verify mobile menu works
- [ ] Test touch interactions

### Browser Compatibility Verification

- [ ] Chrome (latest version)
- [ ] Firefox (latest version)
- [ ] Safari (latest version)
- [ ] Edge (latest version)
- [ ] iOS Safari (mobile)
- [ ] Chrome Mobile (Android)

### Performance Verification

- [ ] Run Google PageSpeed Insights
- [ ] Check page load time (target: <3 seconds)
- [ ] Verify images are optimized
- [ ] Check video file size
- [ ] Test on slow connection (throttle in DevTools)

---

## FINAL SIGN-OFF

### Pre-Launch Checklist

- [ ] All 🔴 HIGH priority items completed
- [ ] All 🟡 MEDIUM priority items completed (or documented as deferred)
- [ ] All verification procedures passed
- [ ] Stakeholder approval received
- [ ] Backup of original site confirmed
- [ ] Rollback plan documented and tested

### Sign-Off

**Completed by:** _______________  
**Date:** _______________  
**Approved by:** _______________  
**Date:** _______________  

### Post-Launch Monitoring

- [ ] Monitor for 404 errors (first 24 hours)
- [ ] Check analytics tracking works
- [ ] Monitor form submissions
- [ ] Check for user-reported issues
- [ ] Verify SEO rankings maintained

---

## NOTES & ISSUES LOG

Use this section to document any issues encountered during replacement:

**Issue 1:**
- Description: _______________
- Resolution: _______________
- Date: _______________

**Issue 2:**
- Description: _______________
- Resolution: _______________
- Date: _______________

**Issue 3:**
- Description: _______________
- Resolution: _______________
- Date: _______________

---

**Checklist Version:** 1.0  
**Last Updated:** 2025-11-15  
**Total Items:** 100+  
**Status:** Ready for use
