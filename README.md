# ESlint and Prettier setup

These are my settings for ESLint and Prettier

You might like them - or you might not. Don't worry you can always change them.

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
