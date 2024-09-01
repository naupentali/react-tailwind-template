# React Tailwind Template

This is a template that makes initializing a vite react+typescript project with tailwindcss faster.

## Usage

`git clone && cd react-tailwind-template && rm -rf .git && npm install`

This will be equivalent to running the following commands:

```
npm create vite@latest react-tailwind-template
✔ Select a framework: › React
✔ Select a variant: › TypeScript
```

```
npm i tailwindcss autoprefixer postcss
npx tailwindcss init -p
```

Add index.html and src to tailwind.config.js
removing vite branding from index.html
cleaning up src folder and adding tailwindcss directives to App.css


