# yuguaa-eslint-config
## Usage

### Install Dependencies

```bash
pnpm add -D @yugu/eslint-config-basic
```



```json
// .eslintrc
{
  "extends": "@yugu/eslint-config-basic"
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
