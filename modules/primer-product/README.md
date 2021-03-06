# Primer product

[![npm version](https://img.shields.io/npm/v/primer-product.svg)](https://www.npmjs.org/package/primer-product)
[![Build Status](https://travis-ci.org/primer/primer.svg?branch=master)](https://travis-ci.org/primer/primer)

> Primer product is one of 3 meta-packages that belong to the Primer framework. Primer product contains packages that are used on GitHub product websites.

This repository is a compilation of [several CSS packages](https://github.com/primer/primer). You can break it down into smaller sections using npm.

## Install

This repository is distributed with [npm][npm]. After [installing npm][install-npm], you can install `primer` with this command. **You must have npm >=3.0 installed to be able to satisfy the dependency paths**

```
$ npm install --save primer-core
```

## Usage

The source files included are written in [Sass][sass] (`scss`) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "primer-core/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **CSS** version of this module, a npm script is included that will output a CSS version to `build/build.css` The built CSS file is also included in the npm package.

```
$ npm run build
```

## Documentation

You can read more about primer in the [docs][docs].

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[primer]: https://github.com/primer/primer
[docs]: http://primer.github.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
