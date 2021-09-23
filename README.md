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

__Extending/overwriting__

> Note: In most cases this shouldn't be necessary.

```js
module.exports = {
  ...require('@simplefocus/prettier-config'),
  tabWidth: 2,
}
```


## Publishing to npm

Read npm's docs on [How to Update a Package](https://docs.npmjs.com/getting-started/publishing-npm-packages#how-to-update-a-package).

1. Checkout and pull the `main` branch.

2. Run the release script to bump the version numbers (the script will create a commit and push up the release branch to GitHub for you).

    ```shell
    ./scripts/release
    ```

    Use [semantic versioning](https://docs.npmjs.com/about-semantic-versioning/) to choose the appropriate version number.

3. Submit and merge a PR from the release branch into `main`.

4. Make sure you're logged into npm from the command line using `npm whoami`. If you're not logged in, `npm login`.

5. `npm publish`


## Additional Plugins

### Tailwind

- https://github.com/Acidic9/prettier-plugin-tailwind

### Twig

- https://github.com/trivago/prettier-plugin-twig-melody
- https://github.com/mubaraqwahab/prettier-plugin-twig-enhancements
