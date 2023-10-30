# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list


###Some used commnands

```
1> npm create vite@latest ./
2> npx tailwindcss init  
3> npm install -D tailwindcss
4> npx tailwindcss init -p 
5> npm install -D tailwindcss postcss autoprefixer
6> npm i react-dropzone
7> npx shadcn-ui@latest init
8> npx shadcn-ui@latest add textarea 
9> npm i -D @types/node  
10> npm install -D tailwindcss-animate           
11> npx tailwindcss init 
12> npm i @tanstack/react-query 
13> npx shadcn-ui@latest add toast  
14> npm i appwrite 
15> npx shadcn-ui@latest add input
16> npx shadcn-ui@latest add form 
17> npx shadcn-ui@latest add button 
18> npm i react-router-dom 
19> npm i react-intersection-observer  
20> npm run dev```
