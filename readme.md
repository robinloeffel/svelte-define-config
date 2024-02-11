# `svelte-define-config`

[![version on npm](https://img.shields.io/npm/v/svelte-define-config)](https://npmjs.com/svelte-define-config)
[![weekly downloads on npm](https://img.shields.io/npm/dw/svelte-define-config)](https://npmjs.com/svelte-define-config)
[![sveltekit peer dep](https://img.shields.io/npm/dependency-version/svelte-define-config/peer/%40sveltejs%2Fkit?label=%40sveltejs%2Fkit%20peer%20dep)](https://www.npmjs.com/@sveltejs/kit)
[![license](https://img.shields.io/npm/l/svelte-define-config)](https://github.com/robinloeffel/svelte-define-config)

> Provide a `defineConfig` function for Svelte and SvelteKit. 👀

Basically just wraps the types coming from [`@sveltejs/kit`](https://github.com/sveltejs/kit) around a function.

## Usage

```sh
npm i svelte-define-config -D
```

```js
// svelte.config.js
import { defineConfig } from 'svelte-define-config';

export default defineConfig({
  // your config here
});
```

## Anything else?

No, there's nothing more to it. That's all there is. Go nuts, champ!

## License

MIT
