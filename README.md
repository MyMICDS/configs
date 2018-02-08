# MyMICDS Common Configs
This repository houses configuration files that are commonly used in MyMICDS projects.

## How to Use

### EditorConfig
Unfortunately, `.editorconfig` files cannot be shared over npm, so you will have to just copy and paste the file into your project.

### ESLint
Since ESLint _requires_ scoped packages to be prefixed with `eslint-config`, the config file will have to be referred to directly by name. (TODO: Try and find a better workaround that allows you to just use `@mymicds/configs/eslint`)

Install the `@mymicds/configs` package, then add the following to `.eslintrc.json`:
```json
{
	"extends": "./node_modules/@mymicds/configs/eslint.json"
}
```

### TSLint
Install the `@mymicds/configs` package, then add the following to `tslint.json`:
```json
{
	"extends": "@mymicds/configs/tslint"
}
```
