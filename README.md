# tailwind-starter

Simple [tailwindcss](https://tailwindcss.com/) starter kit. 

Read more in documentation.

**Usage**

1. Clone repository

```js
https://github.com/dmitriyakkerman/tailwind-starter.git
```
2. Install dependencies
```js
npm install
```
  - Configure `tailwind.config.js` file.

  - Specify your markup files, which use Tailwind.css in `purge` option.

  - Customize your layout using `theme` and `variants` options.

4. Configure entry `main.css` file in `src` folder importing those Tailwind.css entities you need in development:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
5. Create your markup file using Tailwind.css classes.

6. Build your bundle using one of these commands:

Development mode build
```
npm run build
```
Development watch mode build
```
npm run start
```
Production mode minified build
```
npm run generate
```

This will create `styles.css` file in `dist` folder.

7. Connect `styles.css` to your layout.

8. Enjoy!
