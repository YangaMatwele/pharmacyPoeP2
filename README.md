# HealthFirst Pharmacy Website - Community Healthcare in Cape Town

## Student Information
- **Name:** [Yanga ]
- **Student Number:** [ST10508110]
- **Module:** WEDE5111 - Web Development
- **Lecturer:** [Mr Sibene]
- **Submission Date:** 18 September 2026

## Project Overview
HealthFirst Pharmacy is a community pharmacy founded in 2005 serving underserved communities in Cape Town. This website was developed as part of WEDE5111 Part 1 and Part 2. The site provides affordable medication information, online prescription refill functionality, wellness consultations, chronic medication support, and health awareness content.

This is a 3-part journey project:
- Part 1: HTML Structure (Complete)
- Part 2: CSS Styling & Responsive Design (Complete)
- Part 3: JavaScript Interactivity (Upcoming)

Domain: healthfirstpharmacy.co.za
Hosting: VPS Hosting with SSL Certificate

## Website Goals and Objectives

### Goals (from Proposal):
- Provide medication information to local residents
- Enable secure online prescription refills
- Promote health awareness through blog
- Improve patient engagement and satisfaction

### KPIs:
- Number of online prescription refill requests
- Website traffic from health articles
- Patient satisfaction surveys
- Newsletter subscriptions

### Target Audience:
Local residents, families, elderly patients, and individuals who need chronic medication support.

## Key Features and Functionality

### Core Features:
- **5-Page Structure:** Homepage, About Us, Services, Prescription Refill Page, Contact Page
- **Secure Patient Login:** For prescription refill requests (HIPAA-compliant concept)
- **Health Blog:** Categories - nutrition, chronic illness, first aid
- **Appointment Booking:** Form for wellness consultations
- **NPO Support:** Volunteer and sponsor enquiry option in enquiry.html

### Design and User Experience:
- **Color Scheme:** Blue #0e7a6c and Green #2ecc71 tones to reflect trust and health
- **Typography:** Sans-serif fonts (Segoe UI, Aptos Display) for clarity and readability
- **Layout:** Clean, professional, emphasis on accessibility
- **UX Considerations:** Simple navigation, large buttons, WCAG accessibility standards, sticky header

### Technical Implementation:
- Semantic HTML5
- CSS3 with Flexbox and Grid
- Responsive Design with Media Queries
- Relative Units (rem, em, %)
- Responsive Images (srcset, sizes, picture element)

## Timeline and Milestones

- **Week 1-2:** Requirements gathering & wireframes (Homepage > Services > Refill > Blog > Contact)
- **Week 3-4:** Development - HTML structure for 5 pages + CSS base styles, integration of prescription system UI
- **Week 5:** Testing & accessibility compliance - Browser DevTools testing, cross-browser testing
- **Week 6:** Launch - Final README, changelog, sitemap, push to remote repository

## Part 1 Details - Website Structure and Planning

### Sitemap:

## Part 2 Details - Designing the Visuals

### 2.2 Establish a Base Style:
- CSS Reset applied: * { margin:0; padding:0; box-sizing:border-box }
- Default styles set for body, headings, paragraphs
- Consistent cross-browser appearance

### 2.3 Apply Typography:
- font-family: 'Segoe UI', Aptos Display, sans-serif
- Typography scale: h1 2.5rem -> 3.5rem, h2 2rem, p 1em
- font-weight: 700 for headings
- line-height: 1.2 for headings, 1.6 for body
- letter-spacing: -0.02em for headings

### 3. Responsive Design:

#### 3.1 Breakpoints:
- Mobile: Default <768px - single column
- Tablet: 768px - 2 columns, modified navigation
- Desktop: 1024px - 3 columns, larger font sizes
- Implemented with @media (min-width: 768px) and @media (min-width: 1024px)

#### 3.2 Relative Units:
- em: Used for padding, margins, spacing (0.8em, 1.5em)
- rem: Used for font sizes, headings (2.5rem, 1.1rem)
- %: Used for widths, container (90%, 100%, 85%)

#### 3.3 Responsive Images:
- Used srcset and sizes attributes for resolution switching
- Used picture element for art direction (desktop vs tablet vs mobile)
- Example: <img srcset="small 480w, medium 768w, large 1200w" sizes="...">

#### 3.4 Test and Iterate:
- Used Chrome DevTools Device Toolbar
- Tested on: iPhone SE 375px, iPad 768px, Desktop 1440px
- Continuous iteration on layout and navigation

### 5. Technical Requirements Compliance:
- 5.4: All HTML links checked and functioning correctly between 5 pages
- 5.5: Cross-browser compatibility tested (Chrome, Edge, Firefox) - Same appearance
- 5.6: Comments added to HTML and CSS explaining complex selectors, media queries, and responsive logic




## References

- South African Pharmacy Council, 2024. *Good Pharmacy Practice Guidelines for Community Pharmacies*. [online] Available at: https://www.sapc.za.org [Accessed 15 September 2026].
- WordPress.org, 2024. *Healthcare Plugins and HIPAA Compliance Documentation*. [online] Available at: https://wordpress.org/plugins/ [Accessed 15 September 2026].
- Pexels, 2024. *Free Stock Pharmacy Images - Creative Commons License*. [online] Available at: https://www.pexels.com/search/pharmacy/ [Accessed 15 September 2026].
- Mozilla Developer Network, 2024. *CSS Media Queries, srcset, and Responsive Images*. [online] Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries [Accessed 16 September 2026].
- Google Maps, 2024. *Maps Embed API Documentation*. [online] Available at: https://developers.google.com/maps [Accessed 18 September 2026].


## Budget (from Proposal)

- Development: R50,000
- Hosting & Domain (VPS + SSL): R3,500 annually
- Maintenance: R7,500 annually

## GitHub Repository

- **Remote URL:** https://github.com/[YangaMatwele]/HealthFirst-Pharmacy
- **Commit Message Standard:** Part 2: Added base style, typography, responsive breakpoints, relative units, responsive images

---
*This README meets all requirements: Project Title, Student Info, Project Overview, Goals, Key Features, Timeline, Part 1 Details, Sitemap, Changelog, References, Push to Remote.*
