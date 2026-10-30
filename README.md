# wede-part.2-oydp
Olifantsfontein Youth Development NPC (OYDP) - Web Development Portfolio (Part 2)
Introduction


This repository holds the fully responsive, multi-page web platform created for the Olifantsfontein Youth Development NPC (OYDP) to fulfill the deliverables of the WEDE5020 module. Building directly upon the groundwork laid in Part 1, this phase focuses heavily on custom desktop styling, modern layout mechanisms like Flexbox and CSS Grid, cross-browser reliability, consistent image formatting, and thorough testing documentation.

Technical & Architectural Overview

1. Unified Stylesheet & Global Reset
 Consolidated Design: All pages (⁠index.html⁠, ⁠about.html⁠, ⁠services.html⁠, ⁠gallery.html⁠, ⁠register.html⁠, ⁠contact.html⁠) point to a single master stylesheet (⁠style.css⁠).
 Consistent Box Model: Enforces a universal reset (⁠* { margin: 0; padding: 0; box-sizing: border-box; }⁠) to ensure predictable element rendering across different web browsers.
 Design Tokens: Relies on CSS Custom Properties (⁠:root⁠) for color palettes, text hierarchies, animation timings, and standard border radii to guarantee visual harmony.


2. Layout & Visual Structure
 Flexbox Integration: Implements flexible containers (⁠display: flex⁠) for adaptive navigation bars, footer alignment, and internal card content distribution.
 CSS Grid Systems: Employs CSS Grid (⁠display: grid⁠) with explicit column rules to structure multi-item sections such as service offerings, photo galleries, and contact details.
 Image Scaling & Cropping: Uses fixed box heights (⁠200px⁠) combined with ⁠object-fit: cover⁠ on card images to avoid distortion and deliver a neat, uniform presentation.
 User Interaction: Incorporates pseudo-classes (⁠:hover⁠, ⁠:focus⁠, ⁠:active⁠) across navigational links, form inputs, and buttons to improve interactivity.


3. Responsive Web Design (RWD)
 Adaptive Breakpoints: Features media queries customized for tablet screens (⁠992px⁠) and mobile devices (⁠768px⁠).
 Fluid Layout Switching: Automatically shifts multi-column desktop grids (such as 3-column galleries or 2-column service/contact sections) into clean, single-column stacks on smaller viewports.
 Flexible Media: Applies fluid image parameters (⁠max-width: 100%⁠) to prevent unwanted horizontal scrolling on compact screens.


Testing & Quality Assurance

Desktop - 1920 x 1080
Tablet - 768 x 1024
Mobile - 375 x 812

Viewport Documentation
 Desktop Layout: ⁠[Desktop View](screenshots/desktop.png)⁠
 Tablet Layout: ⁠ [Tablet View](screenshots/tablet.png)⁠
 Mobile Layout: ⁠ [Mobile View](screenshots/mobile.png)

References
 MDN Web Docs. (2024). CSS Layout - Grid and Flexbox. Available at: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout [Accessed 2026].
 W3C. (2023). Responsive Web Design Basics. Available at: https://www.w3.org/WAI/tutorials/ [Accessed 2026].
