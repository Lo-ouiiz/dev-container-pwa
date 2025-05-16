# 🧱 Dev Container Environment

This development environment provides **Node.js 20** with the following VS Code extensions:

- 🛠️ ESLint
- 🎨 Prettier
- 🌿 Git Graph
- 🔄 Auto Rename Tag
- ❌ Auto Close Tag
- 💅 Sass Indented

## 📋 Table of Contents

- [🎯 Purpose](#-purpose)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Configuration](#-configuration)
- [🔌 Included VS Code Extensions](#-included-vs-code-extensions)
- [💡 Tips](#-tips)

## 🎯 Purpose

This container includes **no project dependencies**.

Use it to start a new JavaScript/TypeScript/PWA project by running `npm init` or `npm create vite@latest`.

## 🚀 Getting Started

1. Open this folder in VS Code.
2. Click **Reopen in Container**.
3. Run your project creation command or initialize a `package.json`.

## ⚙️ Configuration

- 🔌 Port **3000** is forwarded by default (for local web servers).
- 👤 The user inside the container is `node` (non-root).

## 🔌 Included VS Code Extensions

- `dbaeumer.vscode-eslint` — JavaScript/TypeScript linting
- `esbenp.prettier-vscode` — code formatting
- `mhutchie.git-graph` — Git graphical visualization
- `formulahendry.auto-rename-tag` — automatic HTML tag renaming
- `formulahendry.auto-close-tag` — automatic HTML tag closing
- `syler.sass-indented` — support for indented Sass syntax

## 💡 Tips

- Consider adding a `.eslintrc` and `.prettierrc` file to your projects.
- You can customize settings in `.vscode/settings.json` as needed.
