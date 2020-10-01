# @madebywild/config-eslint

To use it in your project, you need to install this package, eslint and prettier:

```bash
npm i eslint-config-wild-2020 eslint prettier --save-dev
```

Then, edit your projects `package.json`:

```json
{
  "eslintConfig": {
    "extends": "eslint-config-wild-2020"
  }
}
```

How to bump version:

```bash
npm version patch -m "Bumped version" && npm publish --access public
```
