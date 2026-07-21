# A Clear Path

One-on-one mentoring for young Muslim men, ages 11–17, in Kanata. Built with [Astro](https://astro.build) and deployed on Cloudflare.

## Pages

- `/` — Mentorship (landing): overview, what we cover, pricing, apply CTA
- `/about` — About the mentor
- `/testimonials` — Testimonials
- `/apply` — Application form

## Before launch

- Replace the photo placeholder on the About page with a real photo (`public/about-photo.jpg`, then update `src/pages/about.astro`).
- Replace the placeholder quotes on the Testimonials page with real quotes from the people listed there.
- Set `GOOGLE_FORM_EMBED_URL` in `src/consts.ts` once the Google Form is ready.
- Point the `aclearpath.ca` domain at the Cloudflare deployment, if using a custom domain.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                           | Action                                           |
| :--------------------------------- | :------------------------------------------------ |
| `npm install`                     | Installs dependencies                            |
| `npm run dev`                     | Starts local dev server at `localhost:4321`      |
| `npm run build`                   | Build your production site to `./dist/`          |
| `npm run preview`                 | Preview your build locally, before deploying     |
| `npm run build && npm run deploy` | Deploy your production site to Cloudflare        |
