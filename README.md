# ELL Inc. — IT Consulting, Training, and Education

Static site for a professional IT consultant. Deployed with GitHub Pages (no custom domain).

## Features
- Accessible, responsive, SEO optimized
- JSON-LD for Organization, Person, Service
- Lazy-loaded images, reduced-motion friendly
- No-JS fallback: content remains visible

## Local preview
Open `index.html` in a browser.

## Deploy on GitHub Pages
1. Create the repository `ellinc-site` (Public) under your account `littbarskiadeh`.
2. Add these files and push to the `main` branch.
3. In the repository: Settings → Pages → Build and deployment
   - Source: "Deploy from a branch"
   - Branch: `main` — `/ (root)`
4. Wait a minute for publishing, then visit:
   - https://littbarskiadeh.github.io/ellinc-site/

### Git commands (optional)
```bash
mkdir ellinc-site && cd ellinc-site
# Add the files above into this folder
git init
git add .
git commit -m "Initial commit: ELL Inc. site"
git branch -M main
git remote add origin https://github.com/littbarskiadeh/ellinc-site.git
git push -u origin main
```

## Update placeholders anytime
- Logo (JSON-LD): https://via.placeholder.com/512x512.png?text=Logo
- OG image: https://via.placeholder.com/1200x630.png?text=ELL+Inc+OG+Image
- Founder name and photo in JSON-LD: currently "Your Name" and a placeholder image
- Client logos: placeholder images
- Favicons (favicon.ico, icon.svg, apple-touch-icon.png): either add files or remove references

## Links configured
- Booking: https://calendly.com/lit-adeh
- LinkedIn: https://linkedin.com/in/littbarskiadeh
- Instagram: https://instagram.com/IBN_ADEH