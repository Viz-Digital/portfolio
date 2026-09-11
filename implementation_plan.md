# Portfolio Redesign Implementation Plan

This document outlines the plan to redesign your portfolio (`index.html`) using the modern, dark-themed Stitch design as a reference, while populating it with your updated content from `RESUME_UPDATED.pdf` and the original `index.html`.

## User Review Required

Please review the proposed structure and content mapping below. Let me know if you would like to adjust any of the sections, images, or colors before I begin the implementation.

## Proposed Changes

### 1. Design System & Foundation
- Migrate `index.html` to use the Tailwind CSS configuration and color palette from the Stitch design (dark theme, neon cyan accents).
- Implement the interactive WebGL shader background to give it a premium, tech-focused look.
- Replicate the glassmorphism UI components (`glass-panel`, `reveal-up` animations, hover effects).

### 2. Content Mapping & Structure

#### Navigation (Navbar)
- **Links**: Home, About, Experience, Projects, Skills, Contact.
- **Resume Button**: Direct link to `RESUME_UPDATED.pdf`.

#### Hero Section
- **Name**: Vishal Chandran
- **Title**: Technical Associate & Technical Lead
- **Bio**: Results-driven technical professional with 6+ years of experience in EdTech operations, automation workflows, and technical support.
- **Call to Actions**: "View Work" and "Get in Touch".

#### About Section
- Use the Professional Summary from your PDF.
- Retain the sleek image layout from the reference design (we will use a high-quality placeholder that matches the aesthetic, or an image from your existing portfolio if preferred).

#### Experience Section (New based on Resume)
- **Xylem Learning Pvt. Ltd.** (Technical Associate)
  - Highlight batch operations, bot-based automation, and SOP authoring.
- **MEDPG** (Technical Lead)
  - Highlight team leadership, project management, and support triage processes.

#### Skills & Competencies Section
- Combine the skills from your old HTML (HTML, CSS, JavaScript, Flutter, Python, SQL) with the Core Competencies from your PDF (Automation & Tools, LMS/CRM Administration, Agile/Scrum).
- Present these using modern "tech-chips" and progress/level indicators matching the new aesthetic.

#### Projects Section
- **BMI Calculator**: Flutter Material UI project from your old HTML.
- **Bot-Based Automation Pipeline**: Based on your Xylem experience.
- Present these in the sleek, glass-panel project cards from the reference design.

#### Contact & Footer
- **Location**: Thrissur, Kerala, India
- **Phone & Email**: 9633061238 / vizdigitaldeals@gmail.com
- **Socials**: Links to your GitHub and LinkedIn.

---

### [d:\TUTS\PORTFOLIO\index.html](file:///d:/TUTS/PORTFOLIO/index.html)
#### [MODIFY] `index.html`
- Completely rewrite the HTML structure to match the new Tailwind-based design.
- Remove old Bootstrap and legacy CSS dependencies to ensure the new design is clean and performant.

## Verification Plan

### Manual Verification
- Open the updated `index.html` in the browser.
- Verify that the WebGL shader background runs smoothly.
- Ensure all content from the resume is correctly displayed and formatted.
- Check responsive behavior on mobile and desktop viewports.
- Verify that the resume PDF link and social links work correctly.
