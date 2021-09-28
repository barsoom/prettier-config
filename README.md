# @barsoom/prettier-config

Use this with our [eslint config](https://github.com/barsoom/eslint-config-barsoom).

## How to use?

Install:

    npm install --save-dev @barsoom/prettier-config

Then put this in package.json:

    "prettier": "@barsoom/prettier-config"

## Updating

1. Change the config in `prettierrc.json`.
2. Bump the version in `package.json`.
3. Run `npm publish`.
4. Run `npm update @barsoom/prettier-config` (or update all deps) in projects that use this.
