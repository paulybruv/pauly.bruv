# Pauly Bruv Engraving | Bespoke Laser Artistry & Custom Gifts

Pauly Bruv Engraving is a responsive, single-page showcase and custom quote request website built for a Birmingham-based precision laser engraving workshop. The site highlights bespoke slate coasters, 3D layered MDF signage, localized merchandise, and commercial point-of-sale displays.

---

## Table of Contents

1. [Project Overview & UX](#project-overview--ux)
2. [Target Audience & User Goals](#target-audience--user-goals)
3. [Design & Styling Decisions](#design--styling-decisions)
4. [Wireframes](#wireframes)
5. [Features & Structure](#features--structure)
6. [Technologies Used](#technologies-used)
7. [Testing & Validation](#testing--validation)
8. [Deployment](#deployment)
9. [Credits & Acknowledgments](#credits--acknowledgments)

---

## Project Overview & UX

The primary objective of this site is to showcase artisan laser-crafted products, build brand trust through workshop imagery, and provide a low-friction inquiry path for bespoke customer commissions.

### User Stories

- **As a first-time visitor**, I want to quickly understand what materials and products the workshop specializes in.
- **As a potential customer**, I want to view high-resolution examples of past commissions and merchandise displays.
- **As a gift buyer**, I want to submit custom dimensions, artwork requests, or wording through an easy-to-use form to receive a quote.
- **As a social media user**, I want direct links to watch behind-the-scenes engraving videos and workshop drops on TikTok, Instagram, and Facebook.

---

## Design & Styling Decisions

### Color Palette

The color scheme was chosen to reflect natural workshop materials (slate stone, laser-cut timber, warm wood tones, and clean presentation surfaces):

- **Canvas Background (`#f8f7f4`):** Soft alabaster base that reduces eye strain compared to pure white.
- **Primary Charcoal (`#1a1a1a`):** Slate-inspired dark tone for clear text hierarchy, navigation, and main buttons.
- **Artisan Bronze / Timber Accent (`#8c6d46`):** Warm accent color used for icons, interactive hover states, active indicators, and focus outlines.
- **Panel & Card Surface (`#ffffff`):** Crisp white elevated islands to segment sections and frame content cleanly.
- **Matte Carousel Canvas (`#f1efe9`):** Neutral warm stone backing to allow uncropped workshop photos of varying aspect ratios to sit comfortably without distortion.

### Typography

- **Headings:** `'Noto Serif Display'`, Georgia, serif — provides an authentic, crafted editorial feel.
- **Body Text:** Modern System UI sans-serif stack (`-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`) — ensures high legibility across mobile and desktop devices.

---

## Wireframes

Wireframes were produced during the initial UX planning stage to map out responsive layout transitions, section order, and content hierarchy prior to development:

- **Site Wireframe:** [View Wireframe Design](assets/images/pbe-wireframe.png)

![Pauly Bruv Engraving Wireframe](assets/images/pbe-wireframe.png)

---

## Features & Structure

- **Sticky Navigation Bar:** Retains brand logo and links (`Home`, `Products`, `About the Maker`, `Follow Us`, and `Custom Quote` CTA) with mobile hamburger toggle support.
- **Hero Island Panel:** Direct value proposition with clear headline, dual CTAs, and a 3-point workshop guarantee checklist.
- **Featured Products Showcase:** 3-column responsive card grid highlighting pricing, descriptions, and CTAs for core product ranges.
- **Interactive Workshop Carousel:** 4-slide showcase displaying custom wood bar signs, 3D printed/engraved POS stands, and display sets with containment styling (`object-fit: contain`).
- **Social Community Hub:** Responsive cards linking out to TikTok, Instagram, and Facebook with secure `rel="noopener noreferrer"` attributes.
- **Quote Request Form & Feedback Page:** Interactive multi-field form with field validation (`name`, `email`, `projectType`, `message`) that directs users to a dedicated `thank-you.html` confirmation screen upon submission.

---

## Technologies Used

- **HTML5:** Semantic document structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3:** Custom properties (variables), Flexbox, CSS Grid, media queries, and transition micro-interactions.
- **Bootstrap 5.3.3:** Responsive grid framework, navbar collapse component, and carousel functionality.
- **Font Awesome 6.5.1:** Vector icons for UI navigation, feature bullet points, and social badges.
- **Google Fonts:** Embedded `Noto Serif Display` web font.

---

## Testing & Validation

### Responsiveness & Browser Compatibility

- Tested across mobile (320px–480px), tablet (768px–1024px), and desktop viewports (1200px+).
- Tested on Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari.
- Navigation collapse toggle functions correctly on smaller screens.

### Code Validation

- **W3C HTML Validator:** Passed with 0 errors and 0 warnings.
- **W3C CSS (Jigsaw) Validator:** Passed with 0 errors and 0 warnings.

### Form Verification

- Required input attributes prevent empty form submissions.
- Submitting the quote form redirects to `thank-you.html` with a clear confirmation message and a "Return Home" back button.

### Accessibility (a11y)

- All images include descriptive `alt` attributes.
- Form inputs are paired with accessible `<label>` elements.
- Social and external links include appropriate `aria-label` and security attributes.
- High color contrast ratios between text and background surfaces ensure readability.

---

## Deployment

1. The project repository is hosted on **GitHub**.
2. Live deployment is published via **GitHub Pages**:
   - Repository settings > **Pages** > Branch set to `main` / `root`.
   - Live URL: `https://paulybruv.github.io/`

---

## Credits & Acknowledgments

- Workshop product photography and laser engraving designs provided by **Pauly Bruv Engraving**.
- Icons provided by [Font Awesome](https://fontawesome.com/).
- Typography provided by [Google Fonts](https://fonts.google.com/).
- Responsive layout system provided by [Bootstrap 5](https://getbootstrap.com/).
