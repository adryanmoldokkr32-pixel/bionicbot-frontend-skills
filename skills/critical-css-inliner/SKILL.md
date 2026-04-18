---
name: critical-css-inliner
description: Optimize initial load speed by inlining critical styles.
---

# Critical CSS Inliner

This skill identifies and extracts the CSS needed for the 'above the fold' content and inlines it for instant rendering.

## Instructions

1. Identify elements visible on initial page load (Header, Hero, Navigation).
2. Extract the minimum CSS required for these elements.
3. Inline this CSS in the HTML `<head>`.
4. Defer the rest of the CSS to load asynchronously.
5. Test rendering performance using specialized speed tools.

## Examples

- "Identify the critical CSS for my landing page's hero section."
- "Explain how to defer non-critical CSS in a Next.js project."