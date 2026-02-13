# Andy Miller — Filmmaker Portfolio

A static portfolio website for Andy Miller, a film school student showcasing short films, documentaries, and creative video projects.

## Tech Stack

- Plain HTML, CSS, JavaScript
- No build step required
- Deployed on Vercel

## Project Structure

```
src/
├── index.html            # Main page
├── styles/main.css       # All styles
├── scripts/main.js       # Scroll behavior & nav
└── assets/images/        # Creator photo & media
```

## Local Development

Open `src/index.html` directly in your browser, or use a local server:

```bash
npx serve src
```

## Deployment

Hosted on Vercel. Pushes to `main` auto-deploy.

- **Production URL**: https://andymiller.vercel.app

## Customization

- **Bio & stats**: Edit the About section in `src/index.html`
- **Videos**: Replace YouTube embed URLs and titles in the Portfolio section
- **Creator photo**: Drop an image into `src/assets/images/` and update the `<img>` tag in the hero
- **Contact links**: Update email, YouTube, Instagram, LinkedIn URLs in the Contact section
- **Colors**: All design tokens are CSS custom properties in `src/styles/main.css` under `:root`
