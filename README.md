# teleplank.com

Official website for teleplank - Tools for working across boundaries.

## What's Here

This is the landing page showcasing:
- **teleplank** brand and philosophy
- **teledrop** - our first product (available now on npm)

## Structure

```
teleplank.com/
├── index.html    # Main landing page
├── styles.css    # All styling
└── README.md     # This file
```

## Local Development

Just open `index.html` in a browser. No build step needed!

```bash
open index.html
```

## Deployment to GitHub Pages

### Setup

1. **Create repo in teleplank org:**
   - Name: `teleplank.github.io` (or `teleplank.com`)
   - Push this directory to it

2. **Configure DNS in Google Workspace:**
   ```
   Type    Name    Value
   ─────────────────────────────────────────
   A       @       185.199.108.153
   A       @       185.199.109.153
   A       @       185.199.110.153
   A       @       185.199.111.153
   CNAME   www     teleplank.github.io
   ```

3. **Enable GitHub Pages:**
   - Repo Settings → Pages
   - Source: Deploy from main branch
   - Custom domain: `teleplank.com`
   - Enforce HTTPS: ✅

4. **Done!**
   - `teleplank.com` will be live in ~10 minutes

### Updates

```bash
# Make changes
git add .
git commit -m "Update site"
git push

# GitHub Pages auto-deploys
```

## Design Philosophy

- **Dark mode first** - Professional, modern aesthetic
- **ASCII art** - Matches our doc style, technical vibe
- **Clean typography** - San Francisco font stack
- **Minimal** - Focus on content, not decoration
- **Responsive** - Mobile-friendly
- **Fast** - Static HTML, no framework bloat

## Colors

- Background: #0a0a0a (pure dark)
- Text: #ffffff (crisp white)
- Accent: #3b82f6 (blue)
- Success: #10b981 (green for "Available Now" badge)

## Sections

1. **Hero** - Brand identity + manifesto
2. **teledrop Product** - Main showcase with problem/solution
3. **Philosophy** - Our values
4. **Use Cases** - Who it's for
5. **Footer** - Links and info

---

Built with ❤️ by the teleplank team
