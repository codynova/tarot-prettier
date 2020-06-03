Default Prettier config for [Tarot](https://github.com/codynova/tarot)

Install and use with Prettier by placing in `package.json`:

```bash
yarn add --dev tarot-prettier
```

```jsonc
{
  // ...
  "prettier": "tarot-prettier"
}
```


#### Rules

```json
{
  "semi": false,
  "useTabs": true,
  "singleQuote": true,
  "trailingComma": "es5",
  "endOfLine": "lf",
  "printWidth": 180
}
```