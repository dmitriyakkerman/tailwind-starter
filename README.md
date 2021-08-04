# tailwind-starter

Simple [tailwindcss](https://tailwindcss.com/) starter kit. 

Read more in documentation.

**Usage**

1.Clone repository

```js
https://github.com/dmitriyakkerman/tailwind-starter.git
```
2.Install dependencies
```js
npm install
```
3.Configure `tailwind.config.js` file.

3.1. Specify your markup files, which use Tailwind.css in `purge` option.

3.2. Customize your layout using `theme` and `variants` options.

4.Create and configure entry css file importing those Tailwind.css entities you need in development:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
5.Create your markup file using Tailwind.css classes.

6.Build your bundle using one of these commands:

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


