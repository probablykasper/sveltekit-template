# SvelteKit template

- **SvelteKit**
- **TypeScript**
- **`svelte-preprocess` support** with Sass installed by default
- **ESLint**
- **Prettier**
- **Static adapter**

[Svelte template](https://github.com/probablykasper/svelte-template)

## Limitations

- Source maps of `.svelte` files don't support CSS preprocessors ([vite#649](https://github.com/vitejs/vite/issues/649)) and Pug
- ESLint does not work for Linting for code-quality rules is not supported. Would need to use ESLint with eslint-plugin-svelte3, but that plugin needs to work with svelte-preprocess ([eslint-plugin-svelte3#10](https://github.com/sveltejs/eslint-plugin-svelte3/issues/10))

## Commands

- `npm run dev`: Start in dev mode
- `npm run build`: Build
- `npm run preview`: Preview production app
- `npm run check`: Run `svelte-check`
- `npm run lint`: Lint
