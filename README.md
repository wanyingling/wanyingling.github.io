# Wanying's website

> 🍻 a minimalist personal site with some style and serious nonsense

[![Go to mingze-gao.com](https://mingze-gao.com/favicon.png)](https://mingze-gao.com)

## 🚀 Project Structure

This site is build with [Astro](https://astro.build) with the following structure:

```text
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md`/`.mdx` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where to place any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build production site to `./dist/`               |
| `npm run preview`      | Preview build locally, before deploying          |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

Configuration:

- Google Analytics v4 code is located at `src/components/BaseHead.astro`
- giscus comment code is located at `src/layouts/BlogPost.astro`

## Credit

This theme is based off of the Astro's [blog theme](https://astro.build/themes/blog/) and lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
