# @mkvlrn/prettier-config

ALL dependencies are installed with the package

```bash
yarn add prettier @mkvlrn/prettier-config -D
```

```js
// prettier.config.js
import config from "@mkvlrn/prettier-config";

// without modifications
export default config;

// with modifications
export default {
  ...config,
  printWidth: 100,
  // etc
};
```
