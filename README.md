# Nguyen Tran - Portfolio Website

Professional portfolio website built with [Astro](https://astro.build) and the [Astrofy](https://github.com/manuelernestog/astrofy) theme.

## Features

- Dark/Light mode toggle
- Responsive design (mobile, tablet, desktop)
- Clean, professional layout
- Experience timeline
- Skills showcase
- Project showcase
- Education & Certifications

## Tech Stack

- **Framework:** Astro 4.x
- **Styling:** TailwindCSS + DaisyUI
- **Deployment:** GitHub Pages

## Local Development

1. Install dependencies:
```bash
pnpm install
```

2. Start dev server:
```bash
pnpm run dev
```

3. Open http://localhost:4321

## Build

```bash
pnpm run build
```

Output will be in the `dist/` directory.

## Deployment

### GitHub Pages

1. Create a new GitHub repository
2. Push code to repository:
```bash
cd portfolio
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: GitHub Actions

4. Push changes to trigger deployment

## Customization

### Update Content

Edit these files:
- `src/config.ts` - Site title and description
- `src/pages/index.astro` - Home page content
- `src/pages/cv.astro` - Experience timeline
- `src/components/SideBarFooter.astro` - Social links
- `src/components/SideBarMenu.astro` - Navigation menu

### Update Profile Photo

Replace `public/profile.webp` with your photo.

### Themes

Edit `tailwind.config.cjs` to change available themes.

## License

MIT

---

Based on [Astrofy](https://github.com/manuelernestog/astrofy) template by Manuel Ernesto.
