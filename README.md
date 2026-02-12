# geragaraza.com

Personal link-in-bio page — single HTML file, zero dependencies, hosted on GitHub Pages.

**[→ geragaraza.com](https://geragaraza.com)**

## Stack

- Semantic HTML5
- CSS Custom Properties + `clamp()` responsive typography
- Vanilla JavaScript (scramble text effect)
- GitHub Pages + custom domain

## Features

- Staggered entrance animations with `@keyframes`
- Text scramble effect using `requestAnimationFrame`
- Copy-to-clipboard email on desktop, `mailto:` on mobile
- Respects `prefers-reduced-motion` and `prefers-color-scheme`
- Hover states scoped to `@media (hover: hover)` — no sticky hover on touch
- Structured data (JSON-LD) for search engines
- Open Graph + Twitter Card meta tags
- Custom 404 page

## Files

```
├── index.html      Main page
├── 404.html        Custom error page
├── icon.png        Favicon
├── preview.png     OG/Twitter preview image
├── CNAME           Custom domain config
├── robots.txt      Search engine directives
├── sitemap.xml     Sitemap
├── .nojekyll       Bypass Jekyll processing
└── README.md
```

## License

© Herman Harazha. All rights reserved.
