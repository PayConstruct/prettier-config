## Prettier-Config
A Prettier shareable config for projects using Prettier.
## Usage
This package add configuration for prettier but not prettier it self, so install [Prettier](https://www.npmjs.com/package/prettier) and follow the instructions

**Install**:


```bash
$ npm i --dev @payperform/prettier-config
```

**Edit `package.json`**:
Add the following line on the same level as **script**.

```jsonc
{
  // ...
  //"main": "index.js",
  "prettier": "@payperform/prettier-config",
  //"scripts": {}
}
```