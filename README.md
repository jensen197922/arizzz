# ARIZZZ.com

Official site for Ariz Lechuga — Chicago singer, creator & artist.

**Live site:** https://jensen197922.github.io/arizzz  
**Production domain:** https://arizzz.com (configure DNS + GitHub Pages)

## What's included

- Beautiful single-file static site (index.html)
- Tailwind CSS (CDN) + custom elegant styling
- Fully responsive with mobile menu
- Music section with SoundCloud + Instagram focus
- Gallery, Watch, and Connect sections
- Working simulated contact form
- 1111 / Leo easter eggs

## Quick start (local)

Open `index.html` directly in a browser, or:

```bash
# Simple local server (Python)
python -m http.server 5173
# or
npx serve .
```

## Deploy to GitHub Pages (done today)

This repo is set up for GitHub Pages.

1. Go to the repository **Settings** → **Pages**
2. Under "Build and deployment", set:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
3. Save. Your site will be live at `https://<username>.github.io/arizzz` within a minute.

### Custom domain (arizzz.com)

1. In GitHub repo **Settings → Pages**:
   - Enter custom domain: `arizzz.com` (and optionally `www.arizzz.com`)
   - Check "Enforce HTTPS"

2. At your domain registrar / DNS provider add these records:

**For www subdomain (recommended):**
```
CNAME  www  →  jensen197922.github.io
```

**For apex (naked) domain (optional but nice):**
Use one of these sets of A records:
```
A  @  →  185.199.108.153
A  @  →  185.199.109.153
A  @  →  185.199.110.153
A  @  →  185.199.111.153
```

You can also create a `CNAME` file in the repo root containing `arizzz.com` (GitHub will serve it).

After DNS propagates (usually quick), the site will be live on your real domain.

## Updating the site

Edit `index.html` (everything is self-contained). 

To publish:
- Use the GitHub UI to edit the file directly, or
- Push new files via your normal workflow.

## Customization tips

- Replace placeholder images (picsum.photos) with your actual photography
- Add real YouTube embeds when your channel has content
- Update the contact form to a real service (Formspree, Tally, etc.)
- Change accent color by updating the gold hex (#c5a26f)

## Tech

- Pure HTML + Tailwind Play CDN
- Font Awesome icons
- Vanilla JS (no build step)
- GitHub Pages ready

Built & deployed live in a single day.

---

1111 ✨ Chicago

For Ariz — keep creating.