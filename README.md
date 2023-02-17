# eslint-config-shidp

This package provides shidp's base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-shidp

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package
```sh
npm install --save-dev eslint-config-shidp eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "shidp"
}
```

### eslint-config-shidp/legacy

For some legacy project using es5.

First, install this package
```sh
npm install --save-dev eslint-config-shidp eslint
```
Then add following contents to your .eslintrc file
```
{
  "extends": "shidp/legacy"
}
```

### eslint-config-shidp/react
First, install this package and necessary plugins
```sh
npm install --save-dev eslint-config-shidp eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
Then add following contents to your .eslintrc file
```
{
  "extends": "shidp/react"
}
```

## License
MIT
