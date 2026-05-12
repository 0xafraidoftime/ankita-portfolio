# ankitapal.com

Personal portfolio site for [Ankita Pal](https://ankitapal.com) — Machine Learning Engineer.

> "Until death, all defeat is psychological."

## Stack

- Pure HTML / CSS / JS — zero dependencies, zero build step
- Terminal/cyberpunk aesthetic: deep blacks, electric cyan `#00d4ff`
- Custom scanline + grid background texture
- CSS scroll-reveal animations

## Sections

- **Hero** — terminal boot-style intro with typing cursor
- **About** — bio, stats, current focus
- **Projects** — 6 featured GitHub projects with live links
- **Skills** — ML stack + currently learning
- **Miscellanea** — fun links from the original site
- **Contact** — email, Twitter, GitHub, LinkedIn

## Hosting on ankitapal.com

This site is hosted via **GitHub Pages** with a custom domain.

### Setup steps

1. Push this repo to GitHub (e.g. `ankita-portfolio`)
2. Go to **Settings → Pages**
3. Set source: `Deploy from a branch → main → / (root)`
4. Add custom domain: `ankitapal.com`
5. In your GoDaddy DNS, add these records:

| Type  | Name | Value               |
|-------|------|---------------------|
| A     | @    | 185.199.108.153     |
| A     | @    | 185.199.109.153     |
| A     | @    | 185.199.110.153     |
| A     | @    | 185.199.111.153     |
| CNAME | www  | YOUR-GH-USERNAME.github.io |

6. Check **Enforce HTTPS** in GitHub Pages settings
7. DNS propagation takes ~30 min to a few hours

## Resume

Place your resume PDF as `AnkitaPal-Resume.pdf` in the root.  
Update the resume link in `index.html` (search for `RESUME.PDF`).

## Local dev

```bash
# No build needed — just open in browser
open index.html

# Or serve locally
python3 -m http.server 3000
```

## License

© 2026 Ankita Pal. All rights reserved.
