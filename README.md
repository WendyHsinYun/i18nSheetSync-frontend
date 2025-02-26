📄 **Languages:** [繁體中文](README.zh-tw.md) | [English](README.md)

# i18nSheetSync 🚀  

✨ **Sync i18n language files to [Google Sheets](https://www.google.com/sheets/about/), making translation management easier for non-engineers!**  

## 📖 Introduction  

`i18nSheetSync` is a **lightweight i18n sync tool** designed for **front-end developers**. It allows developers to upload TypeScript `.ts` localization files and convert them into a format that is easily editable in **[Google Sheets](https://www.google.com/sheets/about/)**, so that **non-technical users** can manage translations effortlessly. This ensures a smoother internationalization (i18n) workflow!  

Additionally, developers can **export translations from Google Sheets** and automatically convert them back into TypeScript `.ts` files, ensuring a **bidirectional sync** of language data!  

## 🔥 Key Features  

✅ **Upload TypeScript i18n files** (e.g., `zh-TW.ts`, `en.ts`, `th.ts`)  
✅ **Automatically flatten nested structures**, storing translations as `key.value.subValue` format in Google Sheets  
✅ **One-click sync to update translations in [Google Sheets](https://www.google.com/sheets/about/)**  
✅ **Supports large-scale translation updates with optimized performance**  
✅ **Export translations from Google Sheets and convert them back to `.ts` files** (bidirectional sync)  

## 💡 Who is this for?  

- **Front-end developers** who want non-engineers to manage translations  
- **Product managers / marketing teams** who need to update translations easily  
- **Projects with internationalization (i18n)** that require efficient multi-language management  

## 🔧 Tech Stack  

- **Node.js + Google Sheets API** (for reading and updating Google Sheets)  
- **TypeScript** (to ensure structured and correct translations)  
- **Lodash** (to transform nested objects)  

🎯 **Make i18n translation effortless—let Google Sheets handle it!** 🚀  

---

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
