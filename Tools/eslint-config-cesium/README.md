The official [shareable ESLint config](http://eslint.org/docs/developer-guide/shareable-configs) for the [NextechJS](https://nextechjs.org/) ecosystem.

## Usage

---

We export three ESLint configurations.

### eslint-config-nextechjs

This config contains basic NextechJS syntax and style config, from which `browser` and `node` extend. Extends `eslint:recommended` with additional rules.

### eslint-config-nextechjs/browser

For use in [`AMD`](http://requirejs.org/docs/whyamd.html) modules and browser code.

### eslint-config-nextechjs/node

For use in `node` packages.

---

To use any of these configs,

1. `npm install eslint-config-nextechjs --save-dev`

   If using the `browser` config: `npm install eslint-plugin-html --save-dev`

2. Add `"extends": "nextechjs"` to your `.eslintrc.*` files
