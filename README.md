# @hutechwebsite/laboriosam-repudiandae-debitis-animi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does the current environment have `import()` support?

At the time of this writing, node v12.17+, v13.2+ and v14.0+ has support for dynamic [`import()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import#dynamic_imports); the syntax is supported in node v10+.

The former can be checked in the package‘s main export, which is an `async function` that returns a boolean indicating if the current environment fully supports dynamic import. Note that in node v12.17 - v12.19 and v13.4 - v13.13, an ExperimentalWarning will be logged.

The latter can be checked with `'@hutechwebsite/laboriosam-repudiandae-debitis-animi/syntax'`, which is a function that returns a boolean indicating if the current environment supports parsing the syntax of dynamic import.

## Tests

Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hutechwebsite/laboriosam-repudiandae-debitis-animi
[npm-version-svg]: https://versionbadg.es/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi.svg
[deps-svg]: https://david-dm.org/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi.svg
[deps-url]: https://david-dm.org/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi
[dev-deps-svg]: https://david-dm.org/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hutechwebsite/laboriosam-repudiandae-debitis-animi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hutechwebsite/laboriosam-repudiandae-debitis-animi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hutechwebsite/laboriosam-repudiandae-debitis-animi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hutechwebsite/laboriosam-repudiandae-debitis-animi
[codecov-image]: https://codecov.io/gh/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@hutechwebsite/laboriosam-repudiandae-debitis-animi
[actions-url]: https://github.com/hutechwebsite/laboriosam-repudiandae-debitis-animi/actions
