# ESlint and Prettier setup

These are my settings for ESLint and Prettier

You might like them - or you might not. Don't worry you can always change them.

You can see all the [rules here](https://github.com/MiguelMachado-dev/eslint-config-mmcoding/blob/master/.eslintrc.js)

## Local / Per Project Install

1. If you don't already have a `package.json` file, create one with `npm init`.

2. Then we need to install everything needed by the config:

```
npx install-peerdeps --dev eslint-config-mmcoding
```

3. You can see in your package.json there are now a big list of devDependencies.

4. Create a `.eslintrc` file in the root of your project's directory (it should live where package.json does). Your `.eslintrc` file should look like this:

```json
{
  "extends": ["mmcoding"]
}
```

### Absolute paths

This ESlint is setted up to use absolute paths, so if you want to use you can [check here](https://miguelmachado.dev/absolute-imports-with-create-react-app/) how to do it! Your ESlint will not complain about!! 😊
