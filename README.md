# @madebywild/config-eslint

To use it in your project, you need to install this package, eslint and prettier:

```bash
npm i eslint-config-wearewild eslint prettier --save-dev
```

Then, edit your projects `package.json`:

```json
{
  "eslintConfig": {
    "extends": "eslint-config-wearewild"
  }
}
```

How to bump version:

```bash
npm version patch -m "Bumped version" && npm publish --access public
```
