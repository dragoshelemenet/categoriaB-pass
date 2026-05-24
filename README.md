# Categoria B Cumva

Static SEO website for Categoria B questions, lessons, videos and routes.

## Use in Codespaces

```bash
npm install
npm run build
npm run dev
```

The generated static site is in `dist/`. Deploy `dist/` on DigitalOcean Static Site, Cloudflare Pages, GitHub Pages, Netlify or Vercel.

## Edit content

- Questions: `data/questions.json`
- Lessons: `data/lessons.json`
- Videos: `data/videos.json`
- Routes: `data/routes.json`

Each question has its own SEO slug. Run `npm run build` after edits.

## Important

Correct answers imported from visual/PDF data are marked `needsReview: true`. Review before publishing exam mode seriously.
