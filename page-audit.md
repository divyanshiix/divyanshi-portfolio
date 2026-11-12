# Page Audit Report

## SEO & Meta Tags
- **Title**: `Divyanshi Yadav - Personal Portfolio`
- **Meta description**: Provides a concise summary of skills, education, and projects.
- **Open Graph** tags (optional) can be added later for social sharing.

## Accessibility Audit (Chrome DevTools a11y)
- All images have descriptive `alt` attributes.
- Semantic HTML5 elements (`header`, `section`, `footer`).
- ARIA label on the theme toggle button.
- Contrast ratios meet WCAG AA for both light and dark modes.
- Keyboard navigation: Tab order follows logical flow.

## Performance (LCP, CLS)
- Implemented glassmorphism cards with `backdrop-filter` (GPU‑accelerated).
- Images are lazy‑loaded (`loading="lazy"`).
- Minimal CSS & JS, no external frameworks → fast paint.
- Expected LCP < 2.5 s on typical 3G connection.

## Responsive Design
- Tested on viewport widths: 320 px, 768 px, 1024 px.
- Layout adapts using CSS Grid/Flexbox and media queries.
- Navigation remains usable on mobile.

## Validation
- HTML validated with W3C validator – **No errors**.
- CSS linted with Stylelint – **No warnings**.

## Next Steps
- Add Open Graph meta tags for richer link previews.
- Integrate contact form (e.g., Formspree) if desired.
- Deploy to Vercel and verify live URL.

*Generated on $(date)*
