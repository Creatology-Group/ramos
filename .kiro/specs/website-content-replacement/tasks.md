# Implementation Plan - Website Content Replacement

## Overview
Danh sách tasks này sẽ hướng dẫn từng bước để thay đổi toàn bộ nội dung website từ Ramos sang công ty mới. Mỗi task được thiết kế để thực hiện độc lập và có thể kiểm tra kết quả ngay lập tức.

---

## Phase 1: Preparation and Analysis

- [x] 1. Create backup and project structure
  - Create backup directory and copy all original files
  - Create new-content directory structure (images/, videos/, content-ready.json)
  - Create content-plan directory under .kiro/specs/website-content-replacement/
  - Initialize git repository if not exists and create initial commit
  - _Requirements: 10.1, 10.2_

- [x] 2. Analyze and document current content
  - [x] 2.1 Extract all text content from HTML
    - Parse index.htm and identify all text elements (headlines, paragraphs, navigation, buttons)
    - Document CSS selectors for each text element
    - Count characters for each text element
    - Create content-plan/01-content-inventory.md with all findings
    - _Requirements: 1.1, 1.4_
  
  - [x] 2.2 Catalog all media assets
    - List all image files with paths, dimensions, and formats
    - List all video files with paths and metadata
    - Identify all inline SVG elements
    - Document Lottie animation files
    - Create content-plan/04-media-assets-list.md
    - _Requirements: 1.2_
  
  - [x] 2.3 Document brand identity elements
    - Extract all color codes used (especially #FE4A23)
    - Document font families and weights (Urbanist)
    - Identify logo locations (SVG inline, favicon, webclip)
    - List all brand name occurrences ("Ramos")
    - Create content-plan/05-brand-identity-guide.md
    - _Requirements: 1.3_
  
  - [x] 2.4 Extract SEO metadata
    - Document current title tag
    - List all meta tags (og:title, og:image, twitter:title, etc.)
    - Identify missing SEO tags that should be added
    - Create content-plan/06-seo-metadata-template.md
    - _Requirements: 1.5_

- [x] 3. Create content mapping and templates
  - [x] 3.1 Create JSON mapping file
    - Create content-plan/02-content-mapping.json
    - Structure with sections: textContent, mediaAssets, brandIdentity, seoMetadata, contactInfo
    - Include old values, new value placeholders, status, and priority for each item
    - _Requirements: 2.4_
  
  - [x] 3.2 Create text content template
    - Create content-plan/03-text-content-template.md
    - Include tables for Hero, Features, Navigation, Contact sections
    - Add character count guidelines
    - Provide instructions for filling out template
    - _Requirements: 4.1, 4.2, 4.3, 4.4, 4.5_
  
  - [x] 3.3 Create replacement checklist
    - Create content-plan/07-replacement-checklist.md
    - Include checkboxes for all content items
    - Organize by priority (high, medium, low)
    - Add verification steps for each item
    - _Requirements: 2.5, 8.1, 8.2, 8.3, 8.4_

---

## Phase 2: Content Preparation

- [ ] 4. Prepare new content specifications
  - [ ] 4.1 Define new brand identity
    - Document new company name
    - Define new primary color (hex code)
    - Define new secondary colors if any
    - Specify new font family and weights
    - Update content-plan/05-brand-identity-guide.md with new values
    - _Requirements: 6.1, 6.2, 6.5_
  
  - [ ] 4.2 Specify new media assets requirements
    - List required logo files (main logo SVG, favicon 32x32, webclip 180x180)
    - Specify hero video requirements (dimensions, duration, format)
    - List feature section images needed
    - Define naming convention for new assets
    - Update content-plan/04-media-assets-list.md with specifications
    - _Requirements: 5.1, 5.2, 5.3, 5.4, 5.5_
  
  - [ ] 4.3 Prepare SEO content
    - Write new page title (50-60 characters)
    - Write meta description (150-160 characters)
    - Prepare Open Graph title and description
    - Prepare Twitter Card content
    - Update content-plan/06-seo-metadata-template.md with new content
    - _Requirements: 7.1, 7.2, 7.3, 7.4_

- [ ] 5. Create implementation guide
  - Create content-plan/08-implementation-guide.md
  - Document step-by-step process for replacing text content
  - Document process for replacing media assets
  - Document process for updating colors
  - Include testing procedures
  - Include rollback procedures
  - _Requirements: 9.1, 9.2, 9.3, 9.4, 9.5_

---

## Phase 3: Content Replacement

- [ ] 6. Replace text content in HTML
  - [ ] 6.1 Update hero section
    - Replace main headline text
    - Replace hero description text
    - Update any call-to-action button text
    - Verify character counts don't break layout
    - _Requirements: 3.1_
  
  - [ ] 6.2 Update navigation menu
    - Replace all navigation link text
    - Verify link targets still work
    - Update mobile menu if different
    - _Requirements: 3.1, 3.5_
  
  - [ ] 6.3 Update features section
    - Replace section title
    - Replace all feature titles and descriptions
    - Update any statistics or numbers
    - _Requirements: 3.1_
  
  - [ ] 6.4 Update contact information
    - Replace email address (hello@ramos.com)
    - Update any phone numbers
    - Update any physical addresses
    - _Requirements: 3.1, 3.5_
  
  - [ ] 6.5 Replace company name throughout
    - Find and replace all "Ramos" occurrences
    - Check for "Ramos®" trademark symbol
    - Verify replacements in visible text and code comments
    - _Requirements: 3.1_

- [ ] 7. Replace media assets
  - [ ] 7.1 Update logo assets
    - Replace favicon PNG file
    - Replace webclip PNG file
    - Update inline SVG logo in header
    - Update logo SVG in footer if exists
    - Update file paths in HTML
    - _Requirements: 3.2, 6.3_
  
  - [ ] 7.2 Update hero video
    - Upload new hero video to appropriate directory
    - Update video source path in HTML
    - Verify video plays correctly
    - Add poster image if needed
    - _Requirements: 3.2_
  
  - [ ] 7.3 Update feature images
    - Replace all feature section images
    - Update image paths in HTML
    - Verify image dimensions match layout requirements
    - Add appropriate alt text
    - _Requirements: 3.2_
  
  - [ ] 7.4 Update icons and graphics
    - Replace or update SVG icons with new brand colors
    - Update any background images
    - Replace avatar/profile images if used
    - _Requirements: 3.2_

- [ ] 8. Update brand colors
  - [ ] 8.1 Replace primary color in CSS
    - Find all instances of #FE4A23 (old orange)
    - Replace with new primary color
    - Check inline styles in HTML
    - Check SVG fill colors
    - _Requirements: 3.4, 6.2_
  
  - [ ] 8.2 Update button and accent colors
    - Update .button-circle.orange class
    - Update link hover colors
    - Update any gradient definitions
    - _Requirements: 3.4_
  
  - [ ] 8.3 Update secondary colors if needed
    - Replace any secondary brand colors
    - Update background colors if changed
    - Update text colors if needed
    - _Requirements: 3.4_

- [ ] 9. Update typography
  - [ ] 9.1 Replace font family
    - Update Google Fonts WebFont.load() call
    - Update font-family in CSS
    - Verify all font weights are loaded
    - Test fallback fonts
    - _Requirements: 6.5_
  
  - [ ] 9.2 Adjust font sizes if needed
    - Check if new font requires size adjustments
    - Test responsive font sizes
    - Verify readability on all devices
    - _Requirements: 3.4_

- [ ] 10. Update SEO metadata
  - [ ] 10.1 Update basic meta tags
    - Replace <title> tag content
    - Add or update meta description
    - Add robots meta tag if missing
    - Add canonical link if missing
    - _Requirements: 3.3, 7.1, 7.2, 7.5_
  
  - [ ] 10.2 Update Open Graph tags
    - Update og:title
    - Update og:description
    - Update og:image (upload new OG image first)
    - Add og:url
    - Add og:type
    - _Requirements: 3.3, 7.3_
  
  - [ ] 10.3 Update Twitter Card tags
    - Update twitter:title
    - Update twitter:description
    - Update twitter:image
    - Add twitter:card type
    - _Requirements: 3.3, 7.4_

---

## Phase 4: Testing and Validation

- [ ] 11. Perform content verification
  - [ ] 11.1 Verify text content
    - Check all text has been replaced
    - Search for any remaining "Ramos" references
    - Verify no placeholder text remains
    - Check for typos and grammar
    - _Requirements: 8.1_
  
  - [ ] 11.2 Verify media assets
    - Check all images load correctly
    - Verify video plays properly
    - Check all icons display correctly
    - Verify no broken image links
    - _Requirements: 8.2_
  
  - [ ] 11.3 Verify brand consistency
    - Check all colors match brand guide
    - Verify logo displays correctly everywhere
    - Check font rendering
    - Verify overall visual consistency
    - _Requirements: 8.3_

- [ ] 12. Perform responsive testing
  - [ ] 12.1 Test desktop layouts
    - Test at 1920px width
    - Test at 1366px width
    - Test at 1024px width
    - Verify all content displays properly
    - _Requirements: 8.5_
  
  - [ ] 12.2 Test tablet layouts
    - Test at 768px width (portrait)
    - Test at 1024px width (landscape)
    - Verify navigation menu works
    - Check image scaling
    - _Requirements: 8.5_
  
  - [ ] 12.3 Test mobile layouts
    - Test at 375px width (iPhone)
    - Test at 414px width (iPhone Plus)
    - Test at 360px width (Android)
    - Verify mobile menu functionality
    - Check touch interactions
    - _Requirements: 8.5_

- [ ] 13. Perform browser compatibility testing
  - Test in Chrome (latest version)
  - Test in Firefox (latest version)
  - Test in Safari (latest version)
  - Test in Edge (latest version)
  - Test in mobile browsers (iOS Safari, Chrome Mobile)
  - Document any browser-specific issues
  - _Requirements: 8.5_

- [ ] 14. Perform SEO validation
  - [ ] 14.1 Validate meta tags
    - Use HTML validator to check meta tags
    - Verify all required tags present
    - Check for duplicate tags
    - _Requirements: 8.1_
  
  - [ ] 14.2 Test social media previews
    - Test with Facebook Debugger
    - Test with Twitter Card Validator
    - Test with LinkedIn Post Inspector
    - Verify images and text display correctly
    - _Requirements: 8.1_
  
  - [ ] 14.3 Check performance
    - Test page load speed (target < 3 seconds)
    - Check image optimization
    - Verify video loading
    - Test on slow connection
    - _Requirements: 8.5_

- [ ]* 15. Perform accessibility testing
  - [ ]* 15.1 Check color contrast
    - Verify text/background contrast meets WCAG AA (4.5:1 for normal text)
    - Check button contrast
    - Verify link contrast
    - _Requirements: 8.5_
  
  - [ ]* 15.2 Verify alt text
    - Check all images have descriptive alt text
    - Verify decorative images have empty alt
    - Check icon alt text
    - _Requirements: 8.2_
  
  - [ ]* 15.3 Test keyboard navigation
    - Verify all interactive elements are keyboard accessible
    - Check tab order is logical
    - Verify focus indicators are visible
    - _Requirements: 8.5_
  
  - [ ]* 15.4 Test with screen reader
    - Test with NVDA or JAWS (Windows) or VoiceOver (Mac)
    - Verify all content is announced correctly
    - Check heading structure
    - _Requirements: 8.5_

---

## Phase 5: Documentation and Deployment

- [ ] 16. Create final documentation
  - [ ] 16.1 Document all changes
    - Create comprehensive changelog
    - List all files modified
    - Document any issues encountered and solutions
    - _Requirements: 10.3_
  
  - [ ] 16.2 Update project README
    - Update company information
    - Document new brand colors and fonts
    - Add setup instructions
    - Include contact information
    - _Requirements: 9.5_
  
  - [ ] 16.3 Create maintenance guide
    - Document how to update content in future
    - List editable sections
    - Provide image size guidelines
    - Include troubleshooting tips
    - _Requirements: 9.1, 9.2, 9.3_

- [ ] 17. Prepare for deployment
  - [ ] 17.1 Final review
    - Review all checklist items completed
    - Get stakeholder approval
    - Verify backup is complete
    - _Requirements: 10.1_
  
  - [ ] 17.2 Create deployment package
    - Collect all modified files
    - Verify all new assets included
    - Create deployment instructions
    - Test deployment process in staging
    - _Requirements: 10.4_
  
  - [ ] 17.3 Deploy to production
    - Follow deployment instructions
    - Verify deployment successful
    - Test live site functionality
    - Monitor for any issues
    - _Requirements: 10.4_

- [ ] 18. Post-deployment verification
  - Verify all pages load correctly
  - Test all links and navigation
  - Check analytics tracking if applicable
  - Monitor for any error reports
  - Verify SEO tags with live URL
  - _Requirements: 8.1, 8.2, 8.3, 8.4, 8.5_

---

## Notes

- **Priority Levels:**
  - High: Critical for launch (logo, company name, primary colors, hero content)
  - Medium: Important but not blocking (feature descriptions, secondary images)
  - Low: Nice to have (animations, decorative elements)

- **Testing Notes:**
  - Tasks marked with * are optional but recommended for best practices
  - All testing should be done locally before deployment
  - Use browser dev tools for responsive testing
  - Keep screenshots of before/after for documentation

- **Rollback Plan:**
  - If issues found after deployment, restore from backup in backup/ directory
  - Follow rollback procedures in implementation guide
  - Document any issues for future reference

- **Success Criteria:**
  - All high-priority tasks completed
  - No references to old company name remain
  - All media assets replaced
  - Site passes responsive tests
  - Stakeholder approval received
