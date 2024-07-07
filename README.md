<!--
Created: Mon Jul 08 2024 00:01:22 GMT+0600 (Bangladesh Standard Time)
Modified: Mon Jul 08 2024 00:02:27 GMT+0600 (Bangladesh Standard Time)
-->

# electron-app-2

An Electron application with Svelte and TypeScript

## Recommended IDE Setup

* [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) + [Svelte](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode)

## Project Setup

### Install

```bash
$ npm install
```

### Development

```bash
$ npm run dev
```

### Build

```bash
# For windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```

### Editing

App main body CSS:

> src > renderer > index.css

Theme:

> src > renderer > index.html >>> body data-theme="skeleton" ...

server expose host:
electron.vite.config.ts >>>> renderer: {server: {host: true}}
