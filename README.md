```sh
pnpm i -D @arthurfiorette/biomejs-config
```

```jsonc
// biome.json

{
  "$schema": "https://biomejs.dev/schemas/1.9.0/schema.json",
  "extends": ["@arthurfiorette/biomejs-config"]
}
```

```jsonc
// package.json

{
  "scripts": {
    "format": "biome format --write .",
    "lint": "biome check .",
    "lint:ci": "biome ci .",
    "lint:fix": "biome check --write --unsafe ."
  }
}
```
