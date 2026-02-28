I have seen different file extenison in React today, they are .mjs, .cjs, and the most widely used .js


.js Files
Default JavaScript extension

Module system depends on package.json :
  If "type": "commonjs" (or no type specified) → Uses CommonJS
  If "type": "module" → Uses ES modules
Most common extension for JavaScript files


.mjs Files
Explicitly ES Module files

Always uses ES module syntax regardless of package.json
"Module JavaScript" - the 'm' stands for "module"
Forces ES module behavior even in CommonJS projects

.cjs Files
Explicitly CommonJS files
Always uses CommonJS syntax regardless of package.json
"CommonJS" - explicit CommonJS designation

Example JSON I mostly use

```JSON

{
  "name": "code-in-react-19",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview"
  },
  "dependencies": {
    "axios": "^1.12.2",
    "react": "^19.1.0",
    "react-dom": "^19.1.0",
    "react-error-boundary": "^4.0.13"
  },
  "devDependencies": {
    "@tailwindcss/postcss": "^4.0.0",
    "@types/react": "npm:types-react@rc",
    "@types/react-dom": "npm:types-react-dom@rc",
    "@vitejs/plugin-react": "^4.2.1",
    "eslint": "^8.57.0",
    "eslint-plugin-react": "^7.34.1",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.6",
    "postcss": "^8.4.38",
    "tailwindcss": "^4.0.0",
    "vite": "^5.2.0"
  }
}

```

