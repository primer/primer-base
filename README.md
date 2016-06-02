# Primer CSS Base

[![NPM version](http://img.shields.io/npm/v/primer-base.svg)](https://www.npmjs.org/package/primer-base)
[![Build Status](https://travis-ci.org/primer/base.svg?branch=master)](https://travis-ci.org/primer/base)

> GitHub's CSS to reset the browsers default styles. Built on top of normalize.css

This repository is a module of the full [primer-css][primer] repository. And is built off of [normalize.css](https://github.com/necolas/normalize.css/)

## Install

This repository is distributed with [npm][npm]. After [installing npm][install-npm], you can install `primer-base` with this command.

```
$ npm install --save primer-base
```

## Usage

The source files included are written in [Sass][sass] (`scss`) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "primer-base/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **css** version of this module, a npm script is included that will output a css version to `build/build.css`

```
$ npm run build
```

## Documentation

You can read more about base in the [docs][docs].

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[primer]: https://github.com/primer/primer
[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
