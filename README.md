# Gnome vue

## Requirements

- Node.js - tested on v16.15.1
- PNPM - tested on 7.1.7
- GJS - tested on 1.72.0

To generate GIR Typings:

- ts-for-gir - tested on 2.0.0 ([install from github](https://github.com/sammydre/ts-for-gir))
- GTK4 development package - `gtk4-devel` on fedora & `libgtk-4-dev` on ubuntu

## Building
1. `pnpm install`
2. `cd packages/core`
3. `npm install`
4. `npx @ts-for-gir/cli generate`
5. `pnpm run build`

Once built, you can install this via
`npm install /path/to/gnome-vue/packages/core`

or you can install it globally with `npm link`
