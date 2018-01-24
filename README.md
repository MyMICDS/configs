# MyMICDS Common Configs
This repository houses configuration files that are commonly used in MyMICDS projects.

## How to Use

### EditorConfig
Unfortunately, `.editorconfig` files cannot be shared over npm, so you will have to just copy and paste the file into your project.

### ESLint
Install the `@mymicds/configs` package, then add the following to `.eslintrc.json`:
```json
{
	"extends": "@mymicds/configs/eslint"
}
```

### TSLint
Install the `@mymicds/configs` package, then add the following to `tslint.json`:
```json
{
	"extends": "@mymicds/configs/tslint"
}
```
