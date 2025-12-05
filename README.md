# Portfolio Deliverable

## Overview
This package contains the fully optimized and refactored portfolio website for Sayam Mattoo.

## Files Included
- **index.html**: Main HTML file with updated structure, metadata, and content.
- **styles.css**: External CSS file with optimized styles, variables, and accessibility enhancements.
- **script.js**: External JavaScript file with deferred logic, mobile menu handling, and form submission.
- **favicon.png**: Generated favicon.
- **og-image.jpg**: Generated Open Graph social preview image.
- **papers/**: Directory for research papers (placeholders created).
- **Sayam Mattoo Resume.pdf**: Your existing resume file.

## Key Changes
1.  **Refactoring**: Code separated into `styles.css` and `script.js` for better performance.
2.  **Performance**:
    -   Lazy loading for images.
    -   Font preloading.
    -   Optimized blur effects (<= 60px).
    -   Defer attribute for scripts.
3.  **Accessibility**:
    -   Focus outlines for keyboard navigation.
    -   ARIA labels for interactive elements.
    -   `prefers-reduced-motion` support.
4.  **Content**:
    -   Added "Research Papers" section.
    -   Fixed "Download Resume" link.
    -   Updated stats and project descriptions.
5.  **Functionality**:
    -   Working Contact Form (Web3Forms) with honeypot spam protection.
    -   Mobile menu with 30px backdrop blur.
    -   Parallax effect on desktop.

## Instructions
1.  **Resume**: Ensure `Sayam Mattoo Resume.pdf` is in the root directory (it should already be there).
2.  **Research Papers**: Place your actual PDF files in the `papers/` directory:
    -   `papers/blockchain-student-records.pdf`
    -   `papers/cloud-printing-architecture.pdf`
3.  **Contact Form**:
    -   Open `index.html` and search for `YOUR_ACCESS_KEY_HERE`.
    -   Replace it with your actual Web3Forms Access Key.
4.  **Deployment**:
    -   Upload all files to your host (Netlify, Vercel, GitHub Pages).
    -   Ensure `og-image.jpg` is accessible for social previews.

## Lighthouse Targets
-   **Performance**: >90 (Optimized assets and CSS)
-   **Accessibility**: >90 (ARIA, Contrast, Focus)
-   **Best Practices**: >90 (HTTPS, No console errors)
-   **SEO**: >90 (JSON-LD, Meta tags)
