# eslint-config-xinnfe

This package provides xinnfe's base JS .eslintrc as an extensible shared config.

## Usage

### eslint-config-xinnfe

Our default export contains all of our ESLint rules, including ECMAScript 6.

First, install this package

```sh
npm install --save-dev eslint-config-xinnfe eslint
```

Then add following contents to your .eslintrc file

```
{
  "extends": "xinnfe"
}
```

### eslint-config-xinnfe/legacy

For some legacy project using es5.

First, install this package

```sh
npm install --save-dev eslint-config-xinnfe eslint
```

Then add following contents to your .eslintrc file

```
{
  "extends": "xinnfe/legacy"
}
```

## License

MIT
