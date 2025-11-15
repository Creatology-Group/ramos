# SEO Metadata Template - Ramos Website

## Document Information
- **Date Created:** 2025-11-15
- **Purpose:** Complete documentation of current SEO metadata and template for new content
- **Source File:** index.htm (head section)

---

## 1. CURRENT SEO METADATA

### 1.1 Basic Meta Tags

#### Page Title
- **Tag:** `<title>`
- **Current Content:** "Ramos"
- **Character Count:** 5
- **Location:** Line ~2 in head section
- **HTML:** `<title>Ramos</title>`
- **Status:** ⚠️ Too short, needs improvement
- **Recommendation:** 50-60 characters optimal

#### Meta Charset
- **Tag:** `<meta charset>`
- **Current Content:** "utf-8"
- **HTML:** `<meta charset="utf-8">`
- **Status:** ✅ Correct

#### Viewport Meta
- **Tag:** `<meta name="viewport">`
- **Current Content:** "width=device-width, initial-scale=1"
- **HTML:** `<meta content="width=device-width, initial-scale=1" name="viewport">`
- **Status:** ✅ Correct
- **Additional:** Also has `maximum-scale=1.0` in custom meta tag

#### Generator Meta
- **Tag:** `<meta name="generator">`
- **Current Content:** "Webflow"
- **HTML:** `<meta content="Webflow" name="generator">`
- **Status:** ℹ️ Informational (can be removed)

#### Meta Description
- **Tag:** `<meta name="description">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **CRITICAL - Must be added**
- **Recommendation:** 150-160 characters
- **Purpose:** Appears in search results, crucial for SEO

---

### 1.2 Open Graph (Facebook/LinkedIn) Tags

#### og:title
- **Tag:** `<meta property="og:title">`
- **Current Content:** "Ramos"
- **Character Count:** 5
- **HTML:** `<meta content="Ramos" property="og:title">`
- **Status:** ⚠️ Too short, should be more descriptive
- **Recommendation:** 60-90 characters optimal

#### og:image
- **Tag:** `<meta property="og:image">`
- **Current Content:** "https://cdn.prod.website-files.com/669a3911a488f72cbabca56d/66e2a2f99cd9c144f25d469f_Opengraph.png"
- **HTML:** `<meta content="https://..." property="og:image">`
- **Status:** ✅ Present, needs replacement
- **Recommended Size:** 1200x630px
- **Format:** PNG or JPG

#### og:description
- **Tag:** `<meta property="og:description">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **Should be added**
- **Recommendation:** Same as meta description or custom

#### og:url
- **Tag:** `<meta property="og:url">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **Should be added**
- **Purpose:** Canonical URL for social sharing

#### og:type
- **Tag:** `<meta property="og:type">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Recommended**
- **Suggested Value:** "website"

#### og:site_name
- **Tag:** `<meta property="og:site_name">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Optional but recommended**
- **Suggested Value:** Company name

---

### 1.3 Twitter Card Tags

#### twitter:card
- **Tag:** `<meta name="twitter:card">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **Should be added**
- **Recommended Value:** "summary_large_image"

#### twitter:title
- **Tag:** `<meta property="twitter:title">`
- **Current Content:** "Ramos"
- **Character Count:** 5
- **HTML:** `<meta content="Ramos" property="twitter:title">`
- **Status:** ⚠️ Too short, should be more descriptive
- **Recommendation:** 70 characters max

#### twitter:image
- **Tag:** `<meta property="twitter:image">`
- **Current Content:** "https://cdn.prod.website-files.com/669a3911a488f72cbabca56d/66e2a2f99cd9c144f25d469f_Opengraph.png"
- **HTML:** `<meta content="https://..." property="twitter:image">`
- **Status:** ✅ Present, needs replacement
- **Recommended Size:** 1200x675px (or 1200x630px)

#### twitter:description
- **Tag:** `<meta name="twitter:description">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **Should be added**
- **Recommendation:** Same as meta description

#### twitter:site
- **Tag:** `<meta name="twitter:site">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Optional**
- **Purpose:** Twitter handle of website (@username)

#### twitter:creator
- **Tag:** `<meta name="twitter:creator">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Optional**
- **Purpose:** Twitter handle of content creator

---

### 1.4 Additional Recommended Meta Tags (Missing)

#### Canonical Link
- **Tag:** `<link rel="canonical">`
- **Current Content:** ❌ **MISSING**
- **Status:** ⚠️ **Should be added**
- **Purpose:** Prevents duplicate content issues
- **Format:** `<link rel="canonical" href="https://yourdomain.com/">`

#### Robots Meta
- **Tag:** `<meta name="robots">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Recommended**
- **Suggested Value:** "index, follow"
- **Format:** `<meta name="robots" content="index, follow">`

#### Language/Locale
- **Tag:** `<html lang="...">`
- **Current Content:** `lang="en"` ✅ Present
- **Status:** ✅ Correct

#### Theme Color (Mobile)
- **Tag:** `<meta name="theme-color">`
- **Current Content:** ❌ **MISSING**
- **Status:** ℹ️ **Optional**
- **Purpose:** Browser UI color on mobile
- **Suggested Value:** Primary brand color

---

## 2. FAVICON AND APP ICONS

### 2.1 Current Icons

#### Favicon
- **Tag:** `<link rel="shortcut icon">`
- **Current Path:** "669a3911a488f72cbabca56d/669a3c1a57c3b0f5c2f3036b_faviocn.png"
- **Type:** "image/x-icon"
- **HTML:** `<link href="..." rel="shortcut icon" type="image/x-icon">`
- **Status:** ✅ Present, needs replacement

#### Apple Touch Icon
- **Tag:** `<link rel="apple-touch-icon">`
- **Current Path:** "669a3911a488f72cbabca56d/669a3c1d835c44b0a97cee7a_webclip.png"
- **HTML:** `<link href="..." rel="apple-touch-icon">`
- **Status:** ✅ Present, needs replacement

### 2.2 Recommended Additional Icons (Missing)

#### Favicon ICO
- **Tag:** `<link rel="icon">`
- **Type:** "image/x-icon"
- **Size:** 16x16, 32x32, 48x48 (multi-size ICO)
- **Status:** ℹ️ **Optional but recommended**

#### Favicon PNG (Multiple Sizes)
- **Sizes:** 16x16, 32x32, 96x96, 192x192
- **Format:** PNG
- **Status:** ℹ️ **Optional but recommended**

#### Apple Touch Icon (Multiple Sizes)
- **Sizes:** 120x120, 152x152, 167x167, 180x180
- **Format:** PNG
- **Status:** ℹ️ **Optional**

---

## 3. STRUCTURED DATA / SCHEMA.ORG

### 3.1 Current Status
- **Structured Data:** ❌ **MISSING**
- **Status:** ℹ️ **Recommended for better SEO**

### 3.2 Recommended Schema Types

#### Organization Schema
```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "[Company Name]",
  "url": "[Website URL]",
  "logo": "[Logo URL]",
  "description": "[Company Description]",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Street]",
    "addressLocality": "[City]",
    "addressRegion": "[State]",
    "postalCode": "[ZIP]",
    "addressCountry": "US"
  },
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "[Phone]",
    "contactType": "customer service",
    "email": "[Email]"
  }
}
```

#### WebSite Schema
```json
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "[Company Name]",
  "url": "[Website URL]",
  "description": "[Website Description]"
}
```

---

## 4. SEO ISSUES IDENTIFIED

### 4.1 Critical Issues (Must Fix)
1. ❌ **Missing meta description** - Critical for search results
2. ⚠️ **Title too short** - Only 5 characters, should be 50-60
3. ❌ **Missing canonical link** - Important for SEO
4. ❌ **Missing og:description** - Important for social sharing
5. ❌ **Missing twitter:card** - Required for Twitter cards

### 4.2 Important Issues (Should Fix)
1. ⚠️ **og:title too short** - Should be more descriptive
2. ⚠️ **twitter:title too short** - Should be more descriptive
3. ❌ **Missing og:url** - Recommended for social sharing
4. ❌ **Missing og:type** - Recommended for social sharing
5. ❌ **Missing twitter:description** - Recommended for Twitter

### 4.3 Optional Improvements
1. ℹ️ Add robots meta tag
2. ℹ️ Add theme-color meta tag
3. ℹ️ Add structured data (Schema.org)
4. ℹ️ Add additional favicon sizes
5. ℹ️ Add og:site_name
6. ℹ️ Remove generator meta tag

---

## 5. NEW SEO METADATA TEMPLATE

### 5.1 Complete Head Section Template

```html
<head>
  <!-- Basic Meta Tags -->
  <meta charset="utf-8">
  <title>[Company Name] - [Brief Description 50-60 chars]</title>
  <meta name="description" content="[Compelling description 150-160 characters that includes main keywords and value proposition]">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="robots" content="index, follow">
  
  <!-- Canonical Link -->
  <link rel="canonical" href="https://[yourdomain.com]/">
  
  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://[yourdomain.com]/">
  <meta property="og:title" content="[Company Name] - [Descriptive Title 60-90 chars]">
  <meta property="og:description" content="[Same as meta description or custom 150-160 chars]">
  <meta property="og:image" content="https://[yourdomain.com]/images/og-image.png">
  <meta property="og:site_name" content="[Company Name]">
  
  <!-- Twitter -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:url" content="https://[yourdomain.com]/">
  <meta name="twitter:title" content="[Company Name] - [Descriptive Title max 70 chars]">
  <meta name="twitter:description" content="[Same as meta description or custom]">
  <meta name="twitter:image" content="https://[yourdomain.com]/images/twitter-card.png">
  <!-- Optional: <meta name="twitter:site" content="@yourusername"> -->
  <!-- Optional: <meta name="twitter:creator" content="@yourusername"> -->
  
  <!-- Favicons -->
  <link rel="icon" type="image/x-icon" href="/favicon.ico">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  
  <!-- Theme Color (Optional) -->
  <meta name="theme-color" content="[#PRIMARY_COLOR]">
  
  <!-- Existing Webflow/Custom Styles -->
  <!-- ... rest of head content ... -->
</head>
```

---

## 6. CONTENT GUIDELINES

### 6.1 Page Title Guidelines

#### Format Options:
1. **Brand First:** `[Company Name] - [Value Proposition]`
2. **Value First:** `[Value Proposition] | [Company Name]`
3. **Descriptive:** `[Main Keyword] - [Secondary Keyword] | [Company Name]`

#### Best Practices:
- **Length:** 50-60 characters (optimal for Google)
- **Keywords:** Include primary keyword near the beginning
- **Branding:** Include company name
- **Unique:** Different from other pages
- **Compelling:** Encourage clicks from search results

#### Examples (Based on Current Content):
- "Ramos - Analytics Platform for Data-Driven Decisions"
- "Real-Time Analytics & Data Insights | Ramos"
- "Business Analytics Software - Transform Data | Ramos"

### 6.2 Meta Description Guidelines

#### Best Practices:
- **Length:** 150-160 characters (optimal for Google)
- **Keywords:** Include primary and secondary keywords naturally
- **Value Proposition:** Clearly state what you offer
- **Call-to-Action:** Encourage clicks (e.g., "Learn more", "Get started")
- **Unique:** Different from other pages
- **Accurate:** Reflects page content

#### Examples (Based on Current Content):
- "Transform your business with Ramos analytics platform. Get real-time insights, customizable dashboards, and data-driven decisions. Start your free trial today."
- "Ramos provides powerful analytics tools for businesses. Monitor data 24/7, create custom reports, and gain actionable insights. Sign up for free."

### 6.3 Open Graph Title Guidelines

#### Best Practices:
- **Length:** 60-90 characters (can be longer than page title)
- **Descriptive:** More detailed than page title
- **Engaging:** Optimized for social sharing
- **Keywords:** Include relevant keywords

#### Examples:
- "Ramos Analytics - Real-Time Data Insights for Your Business"
- "Transform Your Business with Powerful Analytics Tools | Ramos"

### 6.4 Social Media Image Guidelines

#### Open Graph Image:
- **Dimensions:** 1200x630px (Facebook/LinkedIn standard)
- **Format:** PNG or JPG
- **File Size:** Under 1MB
- **Content:** Include logo, tagline, and visual elements
- **Text:** Keep text minimal and readable
- **Safe Zone:** Keep important content in center 1200x600px

#### Twitter Card Image:
- **Dimensions:** 1200x675px (or use same as OG: 1200x630px)
- **Format:** PNG or JPG
- **File Size:** Under 1MB
- **Aspect Ratio:** 16:9 or 1.91:1

---

## 7. TESTING AND VALIDATION

### 7.1 Testing Tools

#### Meta Tags Testing:
1. **Facebook Debugger:** https://developers.facebook.com/tools/debug/
   - Test Open Graph tags
   - Preview how links appear on Facebook
   - Clear cache if needed

2. **Twitter Card Validator:** https://cards-dev.twitter.com/validator
   - Test Twitter Card tags
   - Preview how links appear on Twitter
   - Validate image dimensions

3. **LinkedIn Post Inspector:** https://www.linkedin.com/post-inspector/
   - Test how links appear on LinkedIn
   - Uses Open Graph tags

#### SEO Testing:
1. **Google Search Console**
   - Submit sitemap
   - Check indexing status
   - Monitor search performance

2. **Google Rich Results Test:** https://search.google.com/test/rich-results
   - Test structured data
   - Validate Schema.org markup

3. **HTML Validator:** https://validator.w3.org/
   - Validate HTML structure
   - Check for errors

### 7.2 Testing Checklist

#### Before Launch:
- [ ] Page title displays correctly in browser tab
- [ ] Meta description appears in search results preview
- [ ] Open Graph tags validated with Facebook Debugger
- [ ] Twitter Card tags validated with Twitter Card Validator
- [ ] LinkedIn preview looks correct
- [ ] Favicon displays in browser tab
- [ ] Apple Touch Icon displays on iOS home screen
- [ ] All image URLs are accessible
- [ ] Canonical URL is correct
- [ ] No duplicate meta tags

#### After Launch:
- [ ] Submit sitemap to Google Search Console
- [ ] Monitor search appearance in Google
- [ ] Check social media sharing on all platforms
- [ ] Verify analytics tracking
- [ ] Monitor for crawl errors

---

## 8. IMPLEMENTATION CHECKLIST

### Phase 1: Critical Updates
- [ ] Add meta description (150-160 chars)
- [ ] Update page title (50-60 chars)
- [ ] Add canonical link
- [ ] Add og:description
- [ ] Add twitter:card meta tag
- [ ] Add twitter:description

### Phase 2: Important Updates
- [ ] Update og:title (more descriptive)
- [ ] Update twitter:title (more descriptive)
- [ ] Add og:url
- [ ] Add og:type
- [ ] Replace og:image with new image
- [ ] Replace twitter:image with new image

### Phase 3: Recommended Updates
- [ ] Add robots meta tag
- [ ] Add og:site_name
- [ ] Add theme-color meta tag
- [ ] Replace favicon
- [ ] Replace apple-touch-icon
- [ ] Add structured data (Schema.org)

### Phase 4: Optional Enhancements
- [ ] Add multiple favicon sizes
- [ ] Add twitter:site handle
- [ ] Add twitter:creator handle
- [ ] Add additional Open Graph tags
- [ ] Remove generator meta tag
- [ ] Add breadcrumb schema
- [ ] Add FAQ schema (if applicable)

---

## 9. KEYWORD RESEARCH NOTES

### Current Content Keywords:
- Analytics
- Data processing
- Real-time insights
- Business intelligence
- Dashboards
- Data-driven decisions
- Monitoring
- Reports

### Recommended Keyword Research:
1. Use Google Keyword Planner
2. Analyze competitor meta tags
3. Research long-tail keywords
4. Consider user intent
5. Include location if relevant

---

## 10. MONITORING AND MAINTENANCE

### Regular Tasks:
- **Monthly:** Review search rankings
- **Monthly:** Check Google Search Console for errors
- **Quarterly:** Update meta descriptions if needed
- **Quarterly:** Refresh social media images
- **Annually:** Review and update all SEO metadata

### Metrics to Track:
- Organic search traffic
- Click-through rate (CTR) from search results
- Social media shares
- Bounce rate
- Time on page
- Conversion rate

---

## 11. REPLACEMENT TEMPLATE (FILL IN)

### New Company Information:

```
Company Name: [TO BE FILLED]
Domain: [TO BE FILLED]
Primary Email: [TO BE FILLED]

Page Title: [TO BE FILLED - 50-60 chars]
Meta Description: [TO BE FILLED - 150-160 chars]

OG Title: [TO BE FILLED - 60-90 chars]
OG Description: [TO BE FILLED - 150-160 chars]
OG Image URL: [TO BE FILLED]

Twitter Title: [TO BE FILLED - max 70 chars]
Twitter Description: [TO BE FILLED - 150-160 chars]
Twitter Image URL: [TO BE FILLED]
Twitter Handle: [TO BE FILLED - optional]

Canonical URL: [TO BE FILLED]
Theme Color: [TO BE FILLED - hex code]

Favicon Path: [TO BE FILLED]
Apple Touch Icon Path: [TO BE FILLED]
```

---

**Document Status:** Complete
**Last Updated:** 2025-11-15
**Next Steps:** Create content mapping JSON and replacement checklist
