# electron-vite-osx-sign

An Electron application with React and TypeScript

- Created with electron-vite
- www folder contains the assets of https://github.com/stephanrauh/ngx-extended-pdf-viewer and multiple times the "cmaps" to generate more files and is added as "extraResources" in the electron builder config
- check the ci that builds and signs a macos build -> it fails
- when you e.g. remove the cmaps folders inside the www folder signing works

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

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
