# tsconfig

## Motivation and Positioning of this repository

[here README.md](https://github.com/smockoro/typescript-shared-configurations)

## Consideration of setting values

[here and docs/tsconfig](https://github.com/smockoro/typescript-shared-configurations/blob/main/docs/tsconfig/README.md)

## How to import

install packages

```bash
npm install -D @smockoro/tsconfig
```

import from `tsconfig.json`

```json
{
  "extends": "@smockoro/tsconfig/bases",
  ...
  "include": ["src"] // override base configuration
}
```

## How to publish common definitions

npm package and publish.

# License

MIT
