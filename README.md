# Paisa landing page

Landing page for [Paisa](https://play.google.com/apps/testing/com.twopixellabs.paisa), a private expense tracker for UPI on Android. The page explains the app and walks people through joining the closed beta.

Built with [Astro](https://astro.build).

## Structure

```text
src/
├── layouts/Layout.astro   # <head>, meta tags, Open Graph
└── pages/index.astro      # Whole page: hero, beta steps, features, gallery, privacy, FAQ
public/                    # App icon, screenshots, feature graphic
```

Images in `public/` are copies of `store/play/` in the [jaimin1503/paisa](https://github.com/jaimin1503/paisa) repo. The social preview image (`og:image`) still points at GitHub because it needs an absolute URL.

## Commands

| Command           | Action                                  |
| :---------------- | :-------------------------------------- |
| `npm install`     | Install dependencies                    |
| `npm run dev`     | Start dev server at `localhost:4321`    |
| `npm run build`   | Build production site to `./dist/`      |
| `npm run preview` | Preview the build locally               |

## Links

- Beta tester group: https://groups.google.com/g/ravenroll-testers/about
- Privacy policy: https://jaimin1503.github.io/paisa/privacy-policy
- Contact: jaiminviramgama152@gmail.com
# paisa-landing
