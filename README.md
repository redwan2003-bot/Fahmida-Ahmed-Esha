# Fahmida-Ahmed-Esha

> Professional Gatsby portfolio for an Industrial and Production Engineering student.

![GitHub stars](https://img.shields.io/github/stars/redwan2003-bot/Fahmida-Ahmed-Esha?style=for-the-badge&logo=github) ![GitHub forks](https://img.shields.io/github/forks/redwan2003-bot/Fahmida-Ahmed-Esha?style=for-the-badge&logo=github) ![GitHub issues](https://img.shields.io/github/issues/redwan2003-bot/Fahmida-Ahmed-Esha?style=for-the-badge&logo=github) ![Last commit](https://img.shields.io/github/last-commit/redwan2003-bot/Fahmida-Ahmed-Esha?style=for-the-badge&logo=github) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white) ![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

## 📑 Table of Contents

- [Description](#description)
- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Key Dependencies](#key-dependencies)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Development Setup](#development-setup)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## 📝 Description

This project is a professional web-based portfolio for Fahmida Ahmed Esha, an Industrial and Production Engineering student at RUET. It provides a structured, modern platform to present professional experience, projects, leadership roles, and academic achievements. By separating content from the display logic, the site ensures that personal information remains easy to maintain and update.

## ✨ Key Features

- **📂 Markdown-Driven Content Sourcing** — Portfolio details such as jobs, featured projects, and leadership history are sourced directly from local files inside the content directory.
- **⚛️ Gatsby Static Generation** — Utilizes Gatsby's robust framework configurations, including customized browser, Node, and SSR files, to pre-render highly optimized static pages.
- **🎨 Dedicated Design System** — Maintains design consistency across the application using a modular design system layout located in the repository.
- **🚀 Multi-Platform Deployment Support** — Comes pre-configured with Netlify and Vercel configuration files for straightforward hosting and instant preview deployments.
- **🧹 Automated Code Formatting** — Uses Husky and lint-staged alongside Prettier to ensure strict code style consistency prior to commits.

## 🎯 Use Cases

- Presenting academic work, student leadership, and internships in a structured web format.
- Updating a personal professional resume and portfolio cleanly using Markdown text files.
- Deploying a fast static website to hosting platforms like Netlify or Vercel using structured configurations.

## 🛠️ Tech Stack

- 🟨 **JavaScript**
- ⚛️ **React**

## ⚡ Quick Start

```bash

# 1. Clone the repository
git clone https://github.com/redwan2003-bot/Fahmida-Ahmed-Esha.git

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run start
```

## 📦 Key Dependencies

```
@parcel/core: ^2.8.3
ajv: ^8.12.0
animejs: ^3.1.0
babel-plugin-styled-components: ^2.1.4
gatsby: ^5.13.3
gatsby-plugin-gtag: ^1.0.13
gatsby-plugin-image: ^3.13.1
gatsby-plugin-manifest: ^5.13.1
gatsby-plugin-netlify: ^5.1.1
gatsby-plugin-offline: ^6.13.2
gatsby-plugin-react-helmet: ^6.13.1
gatsby-plugin-robots-txt: ^1.8.0
gatsby-plugin-sharp: ^5.13.1
gatsby-plugin-sitemap: ^6.13.1
gatsby-plugin-styled-components: ^6.13.1
```

## 🚀 Available Scripts

- **build** — `npm run build`
- **develop** — `npm run develop`
- **format** — `npm run format`
- **start** — `npm run start`
- **serve** — `npm run serve`
- **clean** — `npm run clean`
- **prepare** — `npm run prepare`
- **lint-staged** — `npm run lint-staged`

## 📁 Project Structure

```
.
├── .cursor
│   └── skills
│       └── ui-ux-pro-max
│           ├── SKILL.md
│           ├── data
│           │   ├── charts.csv
│           │   ├── colors.csv
│           │   ├── icons.csv
│           │   ├── landing.csv
│           │   ├── products.csv
│           │   ├── react-performance.csv
│           │   ├── stacks
│           │   │   └── ...
│           │   ├── styles.csv
│           │   ├── typography.csv
│           │   ├── ui-reasoning.csv
│           │   ├── ux-guidelines.csv
│           │   └── web-interface.csv
│           └── scripts
│               ├── core.py
│               ├── design_system.py
│               └── search.py
├── .husky
│   └── pre-commit
├── LICENSE
├── Professional Portfolio_ Fahmida Ahmed Esha.md
├── content
│   ├── featured
│   │   └── LaptopCooler
│   │       ├── demo.png
│   │       └── index.md
│   ├── jobs
│   │   ├── AkijCement
│   │   │   └── index.md
│   │   └── BSCF
│   │       └── index.md
│   └── projects
│       ├── efficiency-pioneers.md
│       ├── iscea-prize-2024.md
│       ├── nirob-blood-donation.md
│       ├── skills-canvas.md
│       └── university-innovation-hub.md
├── design-system
│   └── MASTER.md
├── gatsby-browser.js
├── gatsby-config.js
├── gatsby-node.js
├── gatsby-ssr.js
├── netlify.toml
├── package.json
├── prettier.config.js
├── src
│   ├── components
│   │   ├── email.js
│   │   ├── footer.js
│   │   ├── head.js
│   │   ├── icons
│   │   │   ├── appstore.js
│   │   │   ├── bookmark.js
│   │   │   ├── codepen.js
│   │   │   ├── external.js
│   │   │   ├── folder.js
│   │   │   ├── fork.js
│   │   │   ├── github.js
│   │   │   ├── hex.js
│   │   │   ├── icon.js
│   │   │   ├── index.js
│   │   │   ├── instagram.js
│   │   │   ├── linkedin.js
│   │   │   ├── loader.js
│   │   │   ├── logo.js
│   │   │   ├── playstore.js
│   │   │   ├── star.js
│   │   │   ├── twitter.js
│   │   │   └── whatsapp.js
│   │   ├── index.js
│   │   ├── layout.js
│   │   ├── loader.js
│   │   ├── menu.js
│   │   ├── nav.js
│   │   ├── sections
│   │   │   ├── about.js
│   │   │   ├── contact.js
│   │   │   ├── featured.js
│   │   │   ├── hero.js
│   │   │   ├── jobs.js
│   │   │   └── projects.js
│   │   ├── side.js
│   │   └── social.js
│   ├── config.js
│   ├── fonts
│   │   ├── Calibre
│   │   │   ├── Calibre-Light.ttf
│   │   │   ├── Calibre-Light.woff
│   │   │   ├── Calibre-Light.woff2
│   │   │   ├── Calibre-LightItalic.ttf
│   │   │   ├── Calibre-LightItalic.woff
│   │   │   ├── Calibre-LightItalic.woff2
│   │   │   ├── Calibre-Medium.ttf
│   │   │   ├── Calibre-Medium.woff
│   │   │   ├── Calibre-Medium.woff2
│   │   │   ├── Calibre-MediumItalic.ttf
│   │   │   ├── Calibre-MediumItalic.woff
│   │   │   ├── Calibre-MediumItalic.woff2
│   │   │   ├── Calibre-Regular.ttf
│   │   │   ├── Calibre-Regular.woff
│   │   │   ├── Calibre-Regular.woff2
│   │   │   ├── Calibre-RegularItalic.ttf
│   │   │   ├── Calibre-RegularItalic.woff
│   │   │   ├── Calibre-RegularItalic.woff2
│   │   │   ├── Calibre-Semibold.ttf
│   │   │   ├── Calibre-Semibold.woff
│   │   │   ├── Calibre-Semibold.woff2
│   │   │   ├── Calibre-SemiboldItalic.ttf
│   │   │   ├── Calibre-SemiboldItalic.woff
│   │   │   └── Calibre-SemiboldItalic.woff2
│   │   └── SFMono
│   │       ├── SFMono-Medium.ttf
│   │       ├── SFMono-Medium.woff
│   │       ├── SFMono-Medium.woff2
│   │       ├── SFMono-MediumItalic.ttf
│   │       ├── SFMono-MediumItalic.woff
│   │       ├── SFMono-MediumItalic.woff2
│   │       ├── SFMono-Regular.ttf
│   │       ├── SFMono-Regular.woff
│   │       ├── SFMono-Regular.woff2
│   │       ├── SFMono-RegularItalic.ttf
│   │       ├── SFMono-RegularItalic.woff
│   │       ├── SFMono-RegularItalic.woff2
│   │       ├── SFMono-Semibold.ttf
│   │       ├── SFMono-Semibold.woff
│   │       ├── SFMono-Semibold.woff2
│   │       ├── SFMono-SemiboldItalic.ttf
│   │       ├── SFMono-SemiboldItalic.woff
│   │       └── SFMono-SemiboldItalic.woff2
│   ├── hooks
│   │   ├── index.js
│   │   ├── useOnClickOutside.js
│   │   ├── usePrefersReducedMotion.js
│   │   └── useScrollDirection.js
│   ├── images
│   │   ├── favicons
│   │   │   ├── android-icon-144x144.png
│   │   │   ├── android-icon-192x192.png
│   │   │   ├── android-icon-36x36.png
│   │   │   ├── android-icon-48x48.png
│   │   │   ├── android-icon-72x72.png
│   │   │   ├── android-icon-96x96.png
│   │   │   ├── apple-icon-114x114.png
│   │   │   ├── apple-icon-120x120.png
│   │   │   ├── apple-icon-144x144.png
│   │   │   ├── apple-icon-152x152.png
│   │   │   ├── apple-icon-180x180.png
│   │   │   ├── apple-icon-57x57.png
│   │   │   ├── apple-icon-60x60.png
│   │   │   ├── apple-icon-72x72.png
│   │   │   ├── apple-icon-76x76.png
│   │   │   ├── apple-icon-precomposed.png
│   │   │   ├── apple-icon.png
│   │   │   ├── favicon-16x16.png
│   │   │   ├── favicon-32x32.png
│   │   │   ├── favicon-96x96.png
│   │   │   ├── favicon.ico
│   │   │   ├── ms-icon-144x144.png
│   │   │   ├── ms-icon-150x150.png
│   │   │   ├── ms-icon-310x310.png
│   │   │   └── ms-icon-70x70.png
│   │   ├── logo.png
│   │   ├── me.jpeg
│   │   ├── me.jpg
│   │   └── ups-shot.jpg
│   ├── pages
│   │   ├── 404.js
│   │   └── index.js
│   ├── styles
│   │   ├── GlobalStyle.js
│   │   ├── PrismStyles.js
│   │   ├── TransitionStyles.js
│   │   ├── fonts.js
│   │   ├── index.js
│   │   ├── mixins.js
│   │   ├── theme.js
│   │   └── variables.js
│   └── utils
│       ├── index.js
│       └── sr.js
├── static
│   ├── og.png
│   ├── og@2x.png
│   ├── resume.pdf
│   └── slides
│       └── intro-to-webdev-workshop.pdf
└── vercel.json
```

## 🛠️ Development Setup

### Node.js / JavaScript
1. Install Node.js (v18+ recommended)
2. Install dependencies: `npm install` (or `yarn` / `pnpm install` / `bun install`)
3. Start the dev server: see the **Quick Start** above

## 🚢 Deployment

### Vercel

This project is configured for [Vercel](https://vercel.com). Push to the connected branch or run `vercel` locally.

### Netlify

This project is configured for [Netlify](https://netlify.com). Connect the repo or run `netlify deploy`.

## 👥 Contributing

Contributions are welcome! Here's the standard flow:

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/redwan2003-bot/Fahmida-Ahmed-Esha.git`
3. **Branch**: `git checkout -b feature/your-feature`
4. **Commit**: `git commit -m 'feat: add some feature'`
5. **Push**: `git push origin feature/your-feature`
6. **Open** a pull request

Please follow the existing code style and include tests for new behavior where applicable.

## 📜 License

This project is licensed under the **MIT** License.

---
*This README was generated with ❤️ by [ReadmeBuddy](https://readmebuddy.com)*
