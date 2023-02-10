# yuguaa-eslint-config
## Usage

### Install Dependencies

```bash
pnpm add -D @yugu/eslint-config-vue2
```



```json
// .eslintrc
{
  "extends": "@yugu/eslint-config-vue2"
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
