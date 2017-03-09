# js-ipld-torrent

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPLD-blue.svg?style=flat-square)](http://github.com/ipld/ipld)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![Coverage Status](https://coveralls.io/repos/github/ipld/js-ipld-torrent/badge.svg?branch=master)](https://coveralls.io/github/ipld/js-ipld-dag-cbor?branch=master)
[![Travis CI](https://travis-ci.org/ipld/js-ipld-torrent.svg?branch=master)](https://travis-ci.org/ipld/js-ipld-dag-cbor)
[![Circle CI](https://circleci.com/gh/ipld/js-ipld-torrent.svg?style=svg)](https://circleci.com/gh/ipld/js-ipld-dag-cbor)
[![Dependency Status](https://david-dm.org/ipld/js-ipld-torrent.svg?style=flat-square)](https://david-dm.org/ipld/js-ipld-dag-cbor) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard)
![](https://img.shields.io/badge/npm-%3E%3D3.0.0-orange.svg?style=flat-square)
![](https://img.shields.io/badge/Node.js-%3E%3D4.0.0-orange.svg?style=flat-square)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/ipld-js-torrent.svg)](https://saucelabs.com/u/ipld-js-dag-cbor)

> JavaScript implementation of the [IPLD spec](https://github.com/ipfs/specs/tree/master/ipld).

## Table of Contents

- [Install](#install)
  - [npm](#npm)
  - [Use in Node.js](#use-in-nodejs)
  - [Use in a browser with browserify, webpack or any other bundler](#use-in-a-browser-with-browserify-webpack-or-any-other-bundler)
  - [Use in a browser Using a script tag](#use-in-a-browser-using-a-script-tag)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contribute](#contribute)
- [License](#license)

## Install

### npm

```sh
> npm install ipld-torrent
```

### Use in Node.js

```JavaScript
const torrent = require('ipld-torrent')
```

### Use in a browser with browserify, webpack or any other bundler

The code published to npm that gets loaded on require is in fact a ES5 transpiled version with the right shims added. This means that you can require it and use with your favourite bundler without having to adjust asset management process.

```JavaScript
const torrent = require('ipld-torrent')
```

### Use in a browser Using a script tag

Loading this module through a script tag will make the `IpldTorrent` obj available in the global namespace.

```html
<script src="https://unpkg.com/ipld-torrent/dist/index.min.js"></script>
<!-- OR -->
<script src="https://unpkg.com/ipld-torrent/dist/index.js"></script>
```

## Usage

```JavaScript
const torrent = require('ipld-torrent')
```

## BitTorrent Documentation

- [File Structure](https://wiki.theory.org/BitTorrentSpecification#Metainfo_File_Structure)

## Maintainers

[@diasdavid](https://github.com/diasdavid)

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipld/js-ipld-torrent/issues)!

Check out our [contributing document](https://github.com/ipld/ipld/blob/master/contributing.md) for more information on how we work, and about contributing in general. Please be aware that all interactions related to IPLD are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

[MIT](LICENSE) © 2017 David Dias
