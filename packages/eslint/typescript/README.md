# yuguaa-eslint-config
## Usage

### Install Dependencies

```bash
pnpm add -D @yugu/eslint-config-ts
```



```json
// .eslintrc
{
  "extends": "@yugu/eslint-config-ts"
}
```

Create a new file called `.eslintignore`

```txt
dist
node_modules
public
```

### Add Script

```json
// package.json
{
  "scripts": {
    "lint": "npx eslint --ext .js,.ts,.json,.vue --fix ."
  }
}
```
