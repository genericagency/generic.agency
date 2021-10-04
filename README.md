# Generic Agency

Generic Agency is a satire of marketing agency websites, built on SvelteKit.

## Our Initial Scaffolding of the App

```bash
pnpm init svelte@next generic.agency -y && pnpx svelte-add@latest postcss tailwindcss mdsvex
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
pnpm dev

# or start the server and open the app in a new browser tab
pnpm dev -- --open
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
pnpm build
```

> You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
