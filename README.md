# `@simplefocus/prettier-config`

> Simple Focus base prettier configuration.


## Usage

__Install:__

```bash
$ yarn add --dev @simplefocus/prettier-config
```

__Create `prettier.config.js`:__

```js
module.exports = require('@simplefocus/prettier-config')
```

## Extending/overwriting

> Note: In most cases this shouldn't be necessary.

```js
module.exports = {
  ...require('@simplefocus/prettier-config'),
  tabWidth: 2,
}
```


## Additional Plugins

### Tailwind

- https://github.com/Acidic9/prettier-plugin-tailwind

### Twig

- https://github.com/trivago/prettier-plugin-twig-melody
- https://github.com/mubaraqwahab/prettier-plugin-twig-enhancements
