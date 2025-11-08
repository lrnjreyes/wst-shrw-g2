Project Title: Study Habits Resource Website
Course: Web Systems and Technologies
Team Members: Nhorman Jhay Reyes, John Rexcel Gonzales, Edilyn Valeriano
GitHub Repository
Link: https://github.com/lrnjreyes/wst-shrw-g2
Live Preview (GitHub Pages)
Link: https://lrnjreyes.github.io/wst-shrw-g2/

Project Overview

Before (Milestone 1):
 The initial version of the Study Habits Resource Website was built using pure HTML and CSS, focusing on static content creation. It provided students with educational tips, guides, and resources for better online learning habits. However, the prototype lacked responsive behavior, advanced interactivity, and structured design elements. Navigation and layout were fully custom-coded, making scalability limited.
After (Milestone 2):
 The project was enhanced with Bootstrap 5, JavaScript, and jQuery integration. The team applied a consistent design system, responsive grid layouts, and accessibility improvements. Custom branding (logo and icons) was added to create visual identity, and interactivity was introduced for a more dynamic user experience while maintaining all original features.





Bootstrap Components Implemented
1. Responsive Navigation Bar
Implementation:
Converted the original custom navigation into a Bootstrap .navbar component.


Integrated .navbar-expand-lg, .navbar-toggler, and .collapse classes for adaptive mobile responsiveness.
Added Bootstrap’s data attributes data-bs-toggle and data-bs-target for collapse behavior.
The menu now automatically converts into a hamburger icon on smaller screens.
Files Modified: index.html, about.html, resources.html, tips.html, contact.html
2. Bootstrap Grid System
Usage:
Applied .container, .row, and .col-md-* classes to section layouts for uniform alignment.
Ensured content responsiveness across viewports (mobile, tablet, desktop).
Retained custom layout logic where Bootstrap grid wasn’t necessary to prevent visual disruption.
3. Buttons and Utility Classes
Enhancements:
Replaced standard <button> tags with .btn, .btn-primary, and .btn-outline-secondary classes.
Utilized Bootstrap utility classes for margin (.mt-5, .mb-3) and padding (.py-3, .px-4).
Applied .fw-bold, .text-center, and .text-white for consistent typography and color tokens.



4. Forms and Contact Page
Integration:
Implemented Bootstrap’s .form-group, .form-control, and .form-check structures.
Added built-in validation styling for input fields and email submission form.
Preserved EmailJS and validation scripts for sending feedback messages.
5. Icons and Typography
Details:
Integrated Flaticon and Themify Icons for graphical representation.
Each page section (Resources, Tips, About) now features an icon-based heading using flaticon- and ti- classes.
Fonts were configured in flaticon.css and themify-icons.css for consistency.
6. Visual Enhancements
Highlights:
Added Bootstrap carousel for testimonials and feature sections.
Integrated modals for detailed resource previews.
Used Bootstrap badges and cards to stylize tips and resource listings.
Technical Implementation Strategy
CSS Override System
To maintain custom branding while utilizing Bootstrap’s framework, overrides were applied in style.css.
/* Custom navbar colors */
.navbar.custom-nav {
  background-color: #002347 !important;
}

/* Accent color overrides */
.btn-primary {
  background-color: #fdc632 !important;
  border-color: #fdc632 !important;
}

Reason: Bootstrap’s CSS loads before custom styles; using !important ensures project-specific designs remain dominant.
JavaScript and jQuery Enhancements
Integrated jQuery 3.2.1 for event handling and DOM interactions.
Used Bootstrap.bundle.js for responsive toggling and modals.
Added scroll animations, smooth scrolling, and form validation scripts.
Existing theme.js and contact.js scripts were preserved and extended.
File Assets Overview
CSS: bootstrap.css, flaticon.css, themify-icons.css, style.css
JS: bootstrap.min.js, jquery-3.2.1.min.js, mail-script.js, theme.js
Images: Banners, icons, and custom logos (logo.png, icon.png) used for branding.
Responsive Design and Accessibility
Key Enhancements:
Integrated Bootstrap’s grid system to ensure layout adaptability.
Implemented breakpoints for mobile, tablet, and desktop.
Improved accessibility with alt attributes for images and proper heading structure.
Added visible focus outlines for keyboard navigation.
Ensured color contrast ratios met WCAG AA standards (#002347 background and #fdc632 text).


Breakpoints:
≤480px → Mobile
576–768px → Tablet
≥1024px → Desktop (default)



Testing and Deployment
Testing Environment:
Local testing via Apache localhost
Cross-browser testing: Chrome, Edge, Firefox, Safari
Responsive simulation using Chrome DevTools


Functional Tests:
 Navbar collapse/expand works smoothly
 All internal navigation links functional
Contact form validated and sent via EmailJS
Resource cards responsive on all devices
All animations and icons load correctly
Challenges and Solutions
Challenge
Resolution
Maintaining custom design while integrating Bootstrap
Used targeted CSS overrides (!important) for colors, typography, and spacing.
Navbar logo alignment breaking in mobile view
Adjusted Bootstrap flex utilities (.justify-content-between) and container padding.
Form responsiveness
Wrapped fields inside .row and .col-md-6 for balanced layout.
Icon fonts not displaying
Confirmed correct font paths in flaticon.css and themify-icons.css.


Project Statistics
Total Pages: 5 (Home, Tips, Resources, About, Contact)
Bootstrap Version: 5.3.2
Lines of Custom CSS: ~950 lines
Lines of Bootstrap Overrides: ~120 lines
JavaScript Files: 5 total (including Bootstrap and custom scripts)
External Libraries: jQuery, EmailJS, Flaticon, Themify Icons
Key Achievements
Fully integrated Bootstrap framework while preserving custom branding and layout.
Implemented responsive, accessible UI aligned with modern web standards.
Enhanced interactivity and consistency across devices using jQuery and Bootstrap utilities.
Applied academic feedback from MS1 by establishing a design system, navigation consistency, and accessibility compliance.


Evidence of Learning:
Mastery of Bootstrap components and responsive design.
Advanced CSS specificity and override techniques.
Awareness of accessibility (WCAG 2.1 AA) and usability principles.
Practical integration of framework-based and custom-built front-end systems.
Final Outcome:
The Study Habits Resource Website now demonstrates a professional, responsive, and accessible structure powered by Bootstrap and JavaScript enhancements. It achieves the project’s goal of centralizing student resources while adhering to usability and accessibility best practices.

