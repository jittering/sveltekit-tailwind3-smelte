# sveltekit-tailwind3-smelte

This is template/bootstrap combining:

- Svelte 3 (via svelte-kit)
- Tailwind CSS 3
- Smelte (via [fork](https://github.com/jittering/smelte/tree/peer) which corrects dependencies in package.json)

This builds on some [other](https://github.com/JanMalch/sveltekit-smelte-setup)
[similar](https://github.com/khanguyen88/smelte-typescript-snowpack) efforts to
combine Smelte in various ways.

Hopefully this will be useful to you in playing around with these projects.

## Quickstart

```sh
npm install
npm run dev
# or
npm run build
```

## Notes

The following are dependencies used by `smelte` which must be added to your project:

- tailwind-css-variables
- lodash
- rollup-plugin-postcss
- merge-deep
- svelte-waypoint
- svelte-typed-component
- tinycolor2

```sh
npm install --save-dev \
  tailwind-css-variables lodash rollup-plugin-postcss merge-deep svelte-waypoint \
  svelte-typed-component tinycolor2
```
