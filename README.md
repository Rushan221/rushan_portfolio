# Rushan Tamrakar — Personal Portfolio (static site)

This repository contains a small, responsive, static personal portfolio website for Rushan Tamrakar. It's a plain HTML/CSS site (no build step) and can be hosted on any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

## Quick overview

- Title: Rushan Tamrakar
- Purpose: Personal portfolio / resume website
- Tech: HTML5, CSS3 (no JavaScript build system), external icon fonts via Devicons
- Custom domain: `www.rushantamrakar.com.np` (CNAME file included)

## What’s in this repo

```
./
├─ index.html                  # Main page
├─ CNAME                       # Custom domain for GitHub Pages: www.rushantamrakar.com.np
├─ css/
│  └─ app.css                  # Styles for the site (large single stylesheet)
├─ images/
│  └─ rushan_tamrakar.png      # Profile image used on the site
└─ public/
   └─ Rushan_Tamrakar_CV.pdf   # Resume linked from the site
```

## How to preview locally

Pick one of the methods below:

- Open the HTML file directly in your browser (double-click `index.html` or run `open index.html` on macOS).
- Serve the folder with a minimal HTTP server (recommended) so assets load correctly:


## Notes & small suggestions

- Images are loaded from the local `images/` folder and some backgrounds use Unsplash remote images; consider optimizing and bundling images for faster load times.
- There is no license file in this repo. If you want to make this project reusable by others, add a `LICENSE` (for example, MIT).
- Consider adding basic SEO meta tags, social preview images (Open Graph), and accessibility improvements (alt text is present for the profile image). 
- If you plan to extend the site (scripts, bundling, SASS), add a minimal `package.json` and a build step.

## Contact

- Email: listed in the site (mailto link)
- GitHub: https://github.com/Rushan221

---
