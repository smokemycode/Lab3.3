## Developing with Tailwind
This repository contains my submission for the Developing with Tailwind lab, where I practiced refactoring  design files into polished, responsive, and accessible web components using Tailwind. It demonstrates my ability to interpret design specs, write clean HTML and CSS, and build professional components suitable for a development portfolio.

## 📋 Project Overview
Semantic HTML Structure
Used landmark HTML elements (<header>, <nav>, <main>, <section>, <article>, <footer>) instead of generic <div> containers to create meaningful document structure.

Implemented a logical heading hierarchy, starting with <h1> in the hero section, <h2> for major sections, and <h3> for individual cards and service items.

Structure follows accessibility standards and mirrors the layout organization from the Figma design files.

## 🎨 Layout & Responsive Design
Accuracy to Design
Matched the Figma design precisely — alignment, spacing, font sizes, and element dimensions follow the provided style guide.

Colors, typography, and component sizing all reflect the original design specifications.

Flexbox Implementation
Header & Navigation: Built with Flexbox to align the logo and navigation links. On desktop, items sit inline with space between; on smaller screens (under 600px), the layout gracefully stacks into a centered column.

CSS Grid Implementation
Services Section: Uses CSS Grid with adaptive column layouts:

Desktop (1025px+): 3-column layout (repeat(3, 1fr))

Tablet (601px–1024px): 2-column layout for better readability

Mobile (≤600px): Single-column layout for easy scrolling on phones

CSS Styling
CSS is well-organized and matches the style guide exactly — colors, fonts, and sizes align with the Figma specifications.

Custom properties and media queries keep the styling consistent across all breakpoints.

## ♿ Accessibility Features
Keyboard Navigation & Interactive Elements
Hover and focus states are implemented as specified in the design, with smooth transitions and responsive feedback.

Keyboard focus management ensures all interactive elements are reachable and clearly indicated.

Color Contrast
All text, buttons, and background combinations have been checked against WCAG 2.1 AA standards using contrast checking tools to ensure readability.

Decorative Elements
Service icons are purely decorative and include alt="" to prevent screen readers from announcing them unnecessarily.

## 🛠️ Technologies Used
HTML — Semantic markup and accessibility

CSS — Flexbox, Grid, media queries, and custom properties

Figma — Design interpretation and style guide adherence

Frontend Mentor — Challenge specifications and assets

Tailwind - A utility first CSS library

## ✅ Assessment Criteria Met
☑ Matches design precisely — pixel-perfect alignment, spacing, and sizing
☑ CSS well-organized and matches style guide (colors, fonts, sizes)
☑ Hover and focus states implemented with smooth transitions
☑ Clean, semantic HTML structure following accessibility standards
☑ All challenge requirements met with full interactivity
☑ Responsive design using Flexbox and CSS Grid
☑ Media queries for multiple screen sizes
☑ Sufficient color contrast ratios
☑ Decorative vs. meaningful image handling

## REFLECTION
1. What challenges did you face when refactoring your code to use Tailwind?
   I did not face any challenges refactoring these projects using Tailwind. With the project already being styled it was easy for me to read through the css file and match the styling with tailwind with that.
2. How did using Tailwind utility classes and components simplify your styling process?
   It made it easier for me to copy and paste stylings for different sections that were simliar in style.
3. In what scenarios might you choose not to use Tailwind and write custom CSS instead?
   I would use custom css in instances where the styling is significant to a certain section and will not be shared amongst other elements.
