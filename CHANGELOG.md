# Change Log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org).

## 5.0.3 - 2018-01-16

* Chore: minimum required `cosmiconfig` version is now `^4.0.0`.

## 5.0.2 - 2017-12-12

* Chore: minimum required `node-fs` version is now `^5.0.0`.

## 5.0.1 - 2017-11-28

* Chore: minimum required `meow` version is now `^4.0.0`.

## 5.0.0 - 2017-11-15

* Changed: use `[cosmiconfig](https://github.com/davidtheclark/cosmiconfig) for
  loading configuration.
* Feature: in CLI if the parent directory does not exist when you write
  `robots.txt`, it's created.

## 4.0.4 - 2017-10-09

* Chore: update deps.

## 4.0.3 - 2017-03-13

* Fixed: `is-absolute-url` package semver.

## 4.0.2 - 2016-12-30

* Fixed: `host` options is now processed based `URL`.
* Fixed: thrown error if the `host` option being IP address.
* Fixed: clarified error message on multiple and not string the `userAgent`
  option.
* Fixed: `Host` directive is now not containing `80` port.
* Fixed: thrown error if the `cleanParam` not string or array and if string not
  more than 500 characters.
* Fixed: supported unicode characters in a `Allow` and a `Disallow` directives.
* Fixed: thrown error if the `sitemap` option not an array or a string and not
  an absolute URL.

## 4.0.1 - 2016-10-27

* Chore: added CI test on `node.js` version `7`.
* Documentation: improve `README.md` and fix typos.

## 4.0.0

* Added: `crawlDelay` to each `police` item.
* Added: `cleanParam` to each `police` item (used only Yandex bot).
* Chore: used `remark-preset-lint-itgalaxy` preset.
* Chore: updated `devDependencies`.
* Chore: updated copyright year in `LICENSE`.
* Chore: improved tests.
* Fixed: strict order directives for each `User-agent`.
* Fixed: added newline after each `User-agent`.
* Removed: `crawlDelay` from `options`.
* Removed: `cleanParam` from `options`.
