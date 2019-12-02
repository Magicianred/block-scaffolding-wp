# Block Extend

[![Build Status](https://travis-ci.com/xwp/block-extend.svg?branch=master)](https://travis-ci.com/xwp/block-extend)
[![Coverage Status](https://coveralls.io/repos/github/xwp/block-extend/badge.svg?branch=master)](https://coveralls.io/github/xwp/block-extend?branch=master)


## Requirements

- WordPress 5.0+ or the [Gutenberg Plugin](https://wordpress.org/plugins/gutenberg/).
- [Composer](https://getcomposer.org) and [Node.js](https://nodejs.org) for dependency management.


## Development

1. Clone the plugin repository.

2. Setup the development environment and tools using [Node.js](https://nodejs.org) and [Composer](https://getcomposer.org):

	   npm install


### Scripts

We use `npm` as the canonical task runner for the project. Some of the PHP related scripts are defined in `composer.json`.

- `npm run build` to build the plugin JS and CSS assets. Use `npm run dev` to watch and re-build as you work.

- `npm run lint:js` to lint JavaScript files with [eslint](https://eslint.org/).

- `npm run lint:php` to lint PHP files with [phpcs](https://github.com/squizlabs/PHP_CodeSniffer).

- `npm run test:php:no-coverage` to run PHPUnit tests without checking the coverage.
