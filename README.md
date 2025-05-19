# 🚀 PWA Starter Template - Vanilla

This is a ready-to-use **Progressive Web App (PWA) starter template** built with **Vite** and **TypeScript**, configured for vanilla JavaScript/TypeScript projects.

## 📋 Table of Contents

- [🎯 Purpose](#-purpose)
- [⚙️ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [🛠️ Scripts](#-scripts)
- [💡 Tips](#-tips)

## 🎯 Purpose

Provide a functional PWA starter project with a modern development environment including:

- Vite + TypeScript
- ESLint + Prettier configured
- PWA support with `vite-plugin-pwa`
- Sass support using `sass-embedded`
- Service Worker and Web App Manifest setup

This template is ideal for quickly starting vanilla JavaScript/TypeScript PWA projects without extra frameworks.

## ⚙️ Features

- Fast development with Vite
- PWA ready: offline support, manifest, icons
- Linting and formatting with ESLint and Prettier
- Sass styling with `sass-embedded`
- Forwarded port 5173 for local development server

## 🚀 Getting Started

1. Clone the repo and switch to the **template-vite-vanilla** branch:
   ```bash
   git clone https://github.com/Lo-ouiiz/dev-container-pwa.git
   git switch template-vite-vanilla
   ```
2. Open the project in VS Code and click **Reopen in Container** to start the dev container.

3. Install dependencies.

   ```bash
   npm install
   ```

4. Start the development server.

   ```bash
   npm run dev
   ```

5. Open [http://localhost:5173](http://localhost:5173) in your browser to see your PWA in action.

## 🛠️ Scripts

- `npm run dev` — start development server
- `npm run build` — build for production
- `npm run preview` — locally preview production build
- `npm run lint` — run ESLint on source files

## 💡 Tips

- Customize the PWA manifest and icons in the `vite.config.ts` file.
- Add or update Sass files inside `src/` and import them in `main.ts`.
- Configure ESLint and Prettier rules to fit your coding style.
- Use the dev container for a consistent environment with all dependencies installed.
