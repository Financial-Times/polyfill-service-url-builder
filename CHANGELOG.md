## [2.0.4](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v2.0.3...v2.0.4) (2020-03-13)


### Bug Fixes

* use the new result.message property instead of old message ([af14923](https://github.com/JakeChampion/polyfill-service-url-builder/commit/af14923ff68821600882db26cec1a94636fffaf6))

## [2.0.3](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v2.0.2...v2.0.3) (2020-03-03)


### Bug Fixes

* inform user when a error (but not a SyntaxError) occurs ([3874a85](https://github.com/JakeChampion/polyfill-service-url-builder/commit/3874a852b69cfdffeae2080e5ffa26315dbc16dc))

## [2.0.2](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v2.0.1...v2.0.2) (2020-03-03)


### Bug Fixes

* allow browserslist 'all' range to work ([c969e95](https://github.com/JakeChampion/polyfill-service-url-builder/commit/c969e95f2aa562004767a4be0a2ac62cefc97654))

## [2.0.1](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v2.0.0...v2.0.1) (2020-03-01)


### Bug Fixes

* write non-url output to stderr ([c39cac3](https://github.com/JakeChampion/polyfill-service-url-builder/commit/c39cac3225a4d060ce50d60504ee99fb351204f5))

# [2.0.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.6.0...v2.0.0) (2020-01-13)


### Features

* added browserslist support ([5366d66](https://github.com/JakeChampion/polyfill-service-url-builder/commit/5366d66)), closes [#10](https://github.com/JakeChampion/polyfill-service-url-builder/issues/10)


### BREAKING CHANGES

* If your project makes use of browserslist, you need to now check that you are happy
with your polyfill.io url being based on that config.

# [1.6.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.5.0...v1.6.0) (2019-07-29)


### Features

* sort features query parameter value alphabetically ([2d5c892](https://github.com/JakeChampion/polyfill-service-url-builder/commit/2d5c892))

# [1.5.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.4.2...v1.5.0) (2019-07-29)


### Features

* adds the constructor of a feature to the features querystring if the specific feature does not exist from within polyfill-library ([246c342](https://github.com/JakeChampion/polyfill-service-url-builder/commit/246c342))

## [1.4.2](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.4.1...v1.4.2) (2019-07-24)


### Bug Fixes

* make it work with npx ([330ec29](https://github.com/JakeChampion/polyfill-service-url-builder/commit/330ec29))

## [1.4.1](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.4.0...v1.4.1) (2019-07-24)


### Bug Fixes

* add current working directory to the given file path ([9590f71](https://github.com/JakeChampion/polyfill-service-url-builder/commit/9590f71))

# [1.4.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.3.0...v1.4.0) (2019-07-24)


### Features

* add a package description ([ef7ce5a](https://github.com/JakeChampion/polyfill-service-url-builder/commit/ef7ce5a))

# [1.3.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.2.0...v1.3.0) (2019-07-24)


### Features

* publish to npm and rename cli to package name ([37c1bf1](https://github.com/JakeChampion/polyfill-service-url-builder/commit/37c1bf1))

# [1.2.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.1.0...v1.2.0) (2019-07-24)


### Features

* rename project and add command line interface ([bc96efa](https://github.com/JakeChampion/polyfill-service-url-builder/commit/bc96efa))

# [1.1.0](https://github.com/JakeChampion/polyfill-service-url-builder/compare/v1.0.0...v1.1.0) (2019-07-24)


### Features

* add function which generates polyfill.io urls from an array of features ([e7462cb](https://github.com/JakeChampion/polyfill-service-url-builder/commit/e7462cb))

# 1.0.0 (2019-07-24)


### Features

* begin the project ([a628158](https://github.com/JakeChampion/polyfill-service-url-builder/commit/a628158))
