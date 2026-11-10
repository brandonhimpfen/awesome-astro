# Awesome Astro [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for Astro, Island Architecture components, content collections, framework UI integrations, serverless deployment adapters, and developer tooling.

Astro is an all-in-one web framework designed for content-driven websites, static site generation (SSG), and dynamic server-side rendering (SSR). Pioneering the "Islands Architecture," Astro renders HTML with zero client-side JavaScript by default, enabling selective hydration of UI framework components (React, Vue, Svelte, Solid) only when needed. This list is intended for frontend engineers, full-stack developers, content architects, and web performance leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Framework UI Integrations](#framework-ui-integrations)
- [Content Management & CMS Adapters](#content-management--cms-adapters)
- [Deployment Adapters & Serverless](#deployment-adapters--serverless)
- [SEO, Analytics & Optimization](#seo-analytics--optimization)
  - [Asset & Image Optimization](#asset--image-optimization)
  - [Sitemaps & Metadata](#sitemaps--metadata)
- [Developer Tooling & Extensions](#developer-tooling--extensions)
- [Related Awesome Lists](#related-awesome-lists)

## Framework UI Integrations

Official integration modules bringing multi-framework Island Architecture rendering to Astro pages.

- [@astrojs/react](https://github.com/withastro/astro) — Integration enabling React components and JSX rendering with directive-based client hydration.
- [@astrojs/vue](https://github.com/withastro/astro) — Integration enabling Vue 3 Single-File Components (SFCs) and composition utilities inside Astro.
- [@astrojs/svelte](https://github.com/withastro/astro) — Official integration for embedding Svelte components into Astro pages with selective hydration.
- [@astrojs/solid-js](https://github.com/withastro/astro) — Integration for embedding high-performance SolidJS reactive UI components.
- [@astrojs/tailwind](https://github.com/withastro/astro) — Integration for embedding Tailwind CSS utility styling into Astro projects seamlessly.

## Content Management & CMS Adapters

Integrations and content loaders for pairing headless CMS platforms with Astro Content Collections.

- [Astro Content Collections](https://github.com/withastro/astro) — Native Type-safe schema validation engine powered by Zod for local Markdown and MDX content.
- [Astro DB](https://github.com/withastro/astro) — Fully managed SQL database integration built specifically for Astro applications on LibSQL.
- [Astro MDX Integration](https://github.com/withastro/astro) — Integration for utilizing MDX components inside Astro content workflows.
- [Storyblok Astro SDK](https://github.com/storyblok/storyblok-astro) — Official plugin for bridging Storyblok headless visual CMS editor with Astro pages.

## Deployment Adapters & Serverless

Official server-side rendering (SSR) deployment adapters for serverless environments and edge networks.

- [@astrojs/cloudflare](https://github.com/withastro/astro) — Adapter for deploying Astro SSR websites to Cloudflare Workers and Pages edge runtime.
- [@astrojs/vercel](https://github.com/withastro/astro) — Serverless and edge deployment adapter for Vercel platform infrastructure.
- [@astrojs/netlify](https://github.com/withastro/astro) — Serverless functions and edge adapter for deploying Astro to Netlify.
- [@astrojs/node](https://github.com/withastro/astro) — Standalone Node.js server adapter for self-hosted container deployments.

## SEO, Analytics & Optimization

Asset pipelines, image optimization libraries, schema generators, and RSS feeds.

### Asset & Image Optimization

- [@astrojs/image](https://github.com/withastro/astro) — Built-in image processing component powering responsive image generation and WebP/AVIF conversions.
- [astro-compress](https://github.com/astro-community/astro-compress) — Automated post-build compression utility for HTML, CSS, JavaScript, SVG, and images.

### Sitemaps & Metadata

- [@astrojs/sitemap](https://github.com/withastro/astro) — Integration for automatically generating XML sitemaps upon static site compilation.
- [@astrojs/rss](https://github.com/withastro/astro) — Official utility for generating valid RSS 2.0 feeds from Content Collections.

## Developer Tooling & Extensions

Language servers, linter plugins, VS Code extensions, and community template starters.

- [Astro Language Server](https://github.com/withastro/language-tools) — Official LSP implementation delivering syntax highlighting, diagnostics, and auto-completion.
- [ESLint Plugin Astro](https://github.com/ota-meshi/eslint-plugin-astro) — Official ESLint rules and parser plugin for checking `.astro` files.
- [Prettier Plugin Astro](https://github.com/withastro/prettier-plugin-astro) — Code formatting plugin for automatically formatting Astro component templates.

## Related Awesome Lists

- [Awesome Svelte](https://github.com/brandonhimpfen/awesome-svelte) — Svelte compiler tools, SvelteKit framework, and fine-grained reactivity.
- [Awesome Vue](https://github.com/brandonhimpfen/awesome-vue) — Progressive framework tools, Nuxt engines, and Vue SFC ecosystem.
- [Awesome React](https://github.com/brandonhimpfen/awesome-react) — Component frameworks, SSR engines, state management tools, and JSX ecosystems.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
