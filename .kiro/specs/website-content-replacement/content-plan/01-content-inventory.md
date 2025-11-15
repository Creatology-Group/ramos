# Content Inventory - Ramos Website

## Document Information
- **Date Created:** 2025-11-15
- **Purpose:** Complete inventory of all text content in the website
- **Source File:** index.htm

---

## 1. TEXT CONTENT INVENTORY

### 1.1 Preloader Section

#### Company Name (Preloader)
- **Location:** `.preloader-mark`
- **Current Text:** "Ramos®"
- **Character Count:** 7 (including ®)
- **CSS Selector:** `.preloader-mark`
- **Notes:** Includes registered trademark symbol

#### Preloader Status Text
- **Location:** `.preloader-text`
- **Current Text:** "Data Processing"
- **Character Count:** 15
- **CSS Selector:** `.preloader-text`

---

### 1.2 Header / Navigation Section

#### Logo Text (SVG)
- **Location:** `.ramos-logo-second` (SVG text)
- **Current Text:** "ramos" (lowercase, part of logo SVG)
- **Character Count:** 5
- **CSS Selector:** `.ramos-logo-second svg path`
- **Notes:** This is part of the logo SVG graphic

#### Navigation Menu Items
1. **Nav Link 1**
   - **Location:** `[data-navlink="1"]`
   - **Current Text:** "Key Features"
   - **Character Count:** 12
   - **CSS Selector:** `a[data-navlink="1"]`
   - **Link Target:** #key-features

2. **Nav Link 2**
   - **Location:** `[data-navlink="2"]`
   - **Current Text:** "Explore"
   - **Character Count:** 7
   - **CSS Selector:** `a[data-navlink="2"]`
   - **Link Target:** #explore

3. **Nav Link 3**
   - **Location:** `[data-navlink="3"]`
   - **Current Text:** "Solutions"
   - **Character Count:** 9
   - **CSS Selector:** `a[data-navlink="3"]`
   - **Link Target:** #solutions

4. **Nav Link 4**
   - **Location:** `[data-navlink="4"]`
   - **Current Text:** "Tools"
   - **Character Count:** 5
   - **CSS Selector:** `a[data-navlink="4"]`
   - **Link Target:** #tools

5. **Nav Link 5 (Contact)**
   - **Location:** `[data-navlink="5"]`
   - **Current Text:** "Contact"
   - **Character Count:** 7
   - **CSS Selector:** `a[data-navlink="5"]`
   - **Link Target:** #contact

#### Menu Email Link
- **Location:** `.menu-mail`
- **Current Text:** "hello@ramos.com"
- **Character Count:** 16
- **CSS Selector:** `.menu-mail`
- **Link Type:** mailto link

#### Sign Up Button (Header)
- **Location:** `.button-text` (in menu)
- **Current Text:** "Sign Up"
- **Character Count:** 7
- **CSS Selector:** `.main-button.menu .button-text`

---

### 1.3 Hero Section

#### Main Headline (Hidden for SEO)
- **Location:** `.headline-h1.hero-hide`
- **Current Text:** "Analytics that helps you shape the future"
- **Character Count:** 42
- **CSS Selector:** `.headline-h1.hero-hide`
- **Notes:** Hidden element for SEO purposes

#### Hero Headline - Line 1
- **Location:** `.hero-text-line-n1 .headline-h1`
- **Current Text:** "Analytics"
- **Character Count:** 9
- **CSS Selector:** `.hero-text-line-n1 p.headline-h1`

#### Hero Headline - Line 2 (Multiple Parts)
1. **Part 1:** "that"
   - **Location:** `.headline-h1.that`
   - **Character Count:** 4
   
2. **Part 2:** "helps" (hidden initially)
   - **Location:** `.headline-h1.grey.center`
   - **Character Count:** 5
   
3. **Part 3:** "you"
   - **Location:** `.span-text-mask.you .headline-h1`
   - **Character Count:** 3

#### Hero Headline - Line 3 (Multiple Parts)
1. **Part 1:** "shape"
   - **Location:** `.span-text-mask.space .headline-h1`
   - **Character Count:** 5
   
2. **Part 2:** "the" (hidden initially)
   - **Location:** `.span-text-mask .headline-h1` (second instance)
   - **Character Count:** 3
   
3. **Part 3:** "future" (animated letter by letter)
   - **Location:** `.headline-h1.future`
   - **Character Count:** 6
   - **Notes:** Each letter (f, u, t, u, r, e) is wrapped in individual spans

**Complete Hero Headline:** "Analytics that helps you shape the future"
**Total Character Count:** 42

---

### 1.4 Key Features Section

#### Section Header
- **Location:** `.header-block` in widgets section
- **Current Text (Line 1):** "Your key to strategic"
  - Word 1: "Your" (4 chars)
  - Word 2: "key" (3 chars)
  - Word 3: "to" (2 chars)
  - Word 4: "strategic" (9 chars)
- **Current Text (Line 2):** "success through analytics"
  - Word 1: "success" (7 chars)
  - Word 2: "through" (7 chars)
  - Word 3: "analytics" (9 chars)
- **CSS Selector:** `.widgets-sc .header-block .headline-h2`
- **Total Character Count:** 51

#### Section Description
- **Location:** `.text-wrapper.widgets-s .body-b2`
- **Current Text:** "Ready for exciting, instantaneous, all-accessible insights in real time?"
- **Character Count:** 73
- **CSS Selector:** `.widgets-sc .text-wrapper.widgets-s p.body-b2`

#### Left Widget - Tag
- **Location:** `.widget-tag`
- **Current Text:** "Setting up reports"
- **Character Count:** 18
- **CSS Selector:** `.widget-tag`

#### Left Widget - Subheader
- **Location:** `.header-block.widget-s .subheader`
- **Current Text (Line 1):** "Fast and easy access"
- **Current Text (Line 2):** "to analytics"
- **Combined:** "Fast and easy access to analytics"
- **Character Count:** 33
- **CSS Selector:** `.left-widget-text-content .subheader`

#### Left Widget - Description
- **Location:** `.text-wrapper.widgets-s2 .body-b1`
- **Current Text:** "One platform is a comprehensive system of solutions that will be the first step towards digitalization of your business!"
- **Character Count:** 121
- **CSS Selector:** `.left-widget-text-content .body-b1.middle-grey`

#### Sales Statistic Text
- **Location:** `.sales-text`
- **Current Text:** "Sales statistic"
- **Character Count:** 15
- **CSS Selector:** `.sales-text`

#### Profit Text
- **Location:** `.profit-text`
- **Current Text:** "Profit"
- **Character Count:** 6
- **CSS Selector:** `.profit-text`

#### Profit Value
- **Location:** `.profit-value`
- **Current Text:** "$742k"
- **Character Count:** 5
- **CSS Selector:** `.profit-value`

---

### 1.5 Explore Section (Right Widget)

#### Widget Tag
- **Location:** `.widget-tag` (in right widget)
- **Current Text:** "Monitoring"
- **Character Count:** 10
- **CSS Selector:** `.widget-right .widget-tag`

#### Subheader
- **Location:** `.header-block.widget-s .subheader` (in right widget)
- **Current Text (Line 1):** "Monitoring"
- **Current Text (Line 2):** "24 hours a day"
- **Combined:** "Monitoring 24 hours a day"
- **Character Count:** 25
- **CSS Selector:** `.widget-right .subheader`

#### Description
- **Location:** `.text-wrapper.widgets-s2 .body-b1` (in right widget)
- **Current Text:** "Collect data in real time from multiple channels and start generating reports right away."
- **Character Count:** 89
- **CSS Selector:** `.widget-right .body-b1.middle-grey`

---

### 1.6 Solutions Section (Control Section)

#### Section Header
- **Location:** `.header-block.control-s .headline-h2`
- **Current Text (Line 1):** "Gain control"
- **Current Text (Line 2):** "over your data"
- **Combined:** "Gain control over your data"
- **Character Count:** 27
- **CSS Selector:** `.control-sc .headline-h2`

#### Section Description
- **Location:** `.text-wrapper.control-s .body-b2`
- **Current Text:** "Bring together all your data in one place and get a clear picture of your business."
- **Character Count:** 84
- **CSS Selector:** `.control-sc .body-b2`

#### Control Cards (3 Cards)

**Card 1:**
- **Tag:** "Dashboards"
- **Title:** "Customizable dashboards"
- **Description:** "Tailor your dashboard to display the metrics that matter most to your business."
- **Character Counts:** Tag: 10, Title: 23, Description: 80

**Card 2:**
- **Tag:** "Integrations"
- **Title:** "Seamless integrations"
- **Description:** "Connect with your favorite tools and platforms for a unified data experience."
- **Character Counts:** Tag: 12, Title: 21, Description: 78

**Card 3:**
- **Tag:** "Security"
- **Title:** "Advanced security"
- **Description:** "Rest easy knowing your data is protected with top-tier security measures."
- **Character Counts:** Tag: 8, Title: 17, Description: 74

---

### 1.7 Tools Section

#### Section Header
- **Location:** `.header-block.tools-s .headline-h2`
- **Current Text:** "Powerful tools for data-driven decisions"
- **Character Count:** 40
- **CSS Selector:** `.tools-sc .headline-h2`

#### Section Description
- **Location:** `.text-wrapper.tools-s .body-b2`
- **Current Text:** "Leverage advanced analytics tools to transform raw data into actionable insights."
- **Character Count:** 80
- **CSS Selector:** `.tools-sc .body-b2`

---

### 1.8 CTA (Call-to-Action) Section

#### CTA Header
- **Location:** `.header-block.cta-s .headline-h1`
- **Current Text:** "Get Started"
- **Character Count:** 11
- **CSS Selector:** `.cta-sc .headline-h1`
- **Notes:** Each letter is wrapped in individual spans with animation

#### CTA Description
- **Location:** `.text-wrapper.cta-s .body-b1`
- **Current Text:** "Turn information into advantage! Start using Ramos today. Sign up for a free trial."
- **Character Count:** 83
- **CSS Selector:** `.cta-sc .body-b1`

#### CTA Buttons
1. **Button 1:** "Request a demo"
   - **Character Count:** 14
   - **CSS Selector:** `.main-button.first-view .button-text`

2. **Button 2:** "Start for free"
   - **Character Count:** 14
   - **CSS Selector:** `.main-button.second-view .button-text`

---

### 1.9 Footer Section

#### Footer Navigation Links
1. **Link 1:** "Key Features"
   - **Character Count:** 12
   - **Link Target:** #key-features

2. **Link 2:** "Explore"
   - **Character Count:** 7
   - **Link Target:** #explore

3. **Link 3:** "Solutions"
   - **Character Count:** 9
   - **Link Target:** #solutions

4. **Link 4:** "Tools"
   - **Character Count:** 5
   - **Link Target:** #tools

#### Footer Email
- **Location:** `.ramos-mail`
- **Current Text:** "hello@ramos.com"
- **Character Count:** 16
- **Display Format:** "hello" + "@" + "ramos.com"
- **CSS Selector:** `.ramos-mail`
- **Link Type:** mailto:hello@ramos.com

#### Footer Addresses

**Address 1 - Raleigh:**
- **Location:** `.adress-text.set-1`
- **Current Text:** 
  ```
  Raleigh
  125 N. Harrington Street
  Raleigh, NC 27603
  919.833.6413
  ```
- **CSS Selector:** `.adress-text.set-1`

**Address 2 - Charlotte:**
- **Location:** `.adress-text.set-2`
- **Current Text:**
  ```
  Charlotte
  220 East Peterson Drive
  Charlotte, NC 28217
  704.333.7272
  ```
- **CSS Selector:** `.adress-text.set-2`

#### Footer Brand Mark
- **Location:** `.footer-ramos-mark`
- **Current Text:** "Ramos®"
- **Character Count:** 7
- **CSS Selector:** `.footer-ramos-mark`

#### Footer Credit
- **Location:** `.adress-span.made-by`
- **Current Text:** "Made by Outcrowd"
- **Character Count:** 16
- **CSS Selector:** `.adress-span.made-by`
- **Link Target:** https://www.outcrowd.io/

---

### 1.10 Form Pop-up Section

#### Form Header
- **Location:** `.header-block.form-s .form-headline`
- **Current Text:** "Get Access"
- **Character Count:** 10
- **CSS Selector:** `.form-block .form-headline`

#### Form Description
- **Location:** `.text-wrapper-form.form-s .body-b2`
- **Current Text:** "Create your account and dive into data-driven insights."
- **Character Count:** 55
- **CSS Selector:** `.form-block .body-b2`

#### Form Input Labels
1. **Name Label:**
   - **Location:** `.input-lable` (first)
   - **Current Text:** "Hello, My name is"
   - **Character Count:** 17
   - **Placeholder:** "John"

2. **Email Label:**
   - **Location:** `.input-lable` (second)
   - **Current Text:** "My contact Email"
   - **Character Count:** 16
   - **Placeholder:** "John@example.com"

#### Form Submit Button
- **Location:** `.button-text.form-s`
- **Current Text:** "Sign Up"
- **Character Count:** 7
- **CSS Selector:** `.main-button.form-s .button-text`

#### Success Message Header
- **Location:** `.header-block.success-s .form-headline`
- **Current Text:** "Request submited"
- **Character Count:** 16
- **CSS Selector:** `.success-message .form-headline`
- **Notes:** Typo in original - "submited" should be "submitted"

#### Success Message Description
- **Location:** `.success-text.success-s .body-b2`
- **Current Text:** "Thank you for your interest in our product. Expect an email with early access details shortly."
- **Character Count:** 94
- **CSS Selector:** `.success-message .body-b2`

#### Success Return Button
- **Location:** `.main-button` (in success message)
- **Current Text:** "Return to home"
- **Character Count:** 14
- **CSS Selector:** `.success-message .button-text`

---

## 2. SUMMARY STATISTICS

### Total Text Elements Identified: 60+

### By Section:
- **Preloader:** 2 elements
- **Header/Navigation:** 7 elements
- **Hero Section:** 10+ elements (including animated parts)
- **Key Features Section:** 8 elements
- **Explore Section:** 3 elements
- **Solutions Section:** 11 elements (including 3 cards)
- **Tools Section:** 2 elements
- **CTA Section:** 4 elements
- **Footer:** 9 elements
- **Form Pop-up:** 10 elements

### Character Count Ranges:
- **Shortest:** 2 characters ("to")
- **Longest:** 121 characters (widget description)
- **Average:** ~25 characters per text element

### Brand Name Occurrences:
- "Ramos" appears: 8+ times
- "Ramos®" (with trademark): 2 times
- "ramos.com" (domain): 2 times

---

## 3. NOTES AND OBSERVATIONS

### Typography Patterns:
1. Headlines use `.headline-h1` and `.headline-h2` classes
2. Body text uses `.body-b1` and `.body-b2` classes
3. Subheaders use `.subheader` class
4. Many text elements have animation transforms applied

### Animation Considerations:
- Hero headline has complex letter-by-letter animations
- Many text elements use transform animations on scroll
- Text masks are used for reveal effects

### Accessibility Considerations:
- Hidden SEO headline exists for screen readers
- All interactive elements have proper text labels
- Form inputs have associated labels

### Special Characters:
- Registered trademark symbol (®) used with brand name
- Email addresses use @ symbol
- Phone numbers use period separators

---

## 4. REPLACEMENT CHECKLIST

### High Priority (Brand Identity):
- [ ] All "Ramos" brand name occurrences (8+)
- [ ] Email addresses (hello@ramos.com)
- [ ] Domain references (ramos.com)
- [ ] Trademark symbols (®)

### High Priority (Main Content):
- [ ] Hero headline (42 chars)
- [ ] Main section headers
- [ ] CTA text and buttons

### Medium Priority:
- [ ] Navigation menu items
- [ ] Section descriptions
- [ ] Widget content
- [ ] Form labels and messages

### Low Priority:
- [ ] Footer addresses (if applicable)
- [ ] Footer credit line
- [ ] Placeholder text

---

**Document Status:** Complete
**Last Updated:** 2025-11-15
**Next Steps:** Create media assets inventory and brand identity guide
