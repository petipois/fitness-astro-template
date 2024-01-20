# Fitness Astro Template

[Youtube Tutorial - Canva to Astro 4.0: Fitness Website](https://youtube.com/playlist?list=PLP5oBhNCHQF1VsRCSTpug63AYymmEvYpM&si=Y4A9d0PsXsRi-FlQ)

[Live Preview](https://fitness-astro-template.netlify.app/)

## 🚀 Project Structure

Inside of this Fitness Astro Template, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── About.astro
|   |   └── Card.astro -- not used
|   |   └── Hero.astro
|   |   └── HeroFooter.astro
|   |   └── ImageCard.astro
|   |   └── Offers.astro
|   |   └── Testimonials.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |).
