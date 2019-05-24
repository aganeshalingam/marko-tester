## [9.6.4](https://github.com/oxala/marko-tester/compare/v9.6.3...v9.6.4) (2019-05-24)


### Bug Fixes

* fixed marko resolver for Windows ([#27](https://github.com/oxala/marko-tester/issues/27)) ([35c6c17](https://github.com/oxala/marko-tester/commit/35c6c17))

## [9.6.3](https://github.com/oxala/marko-tester/compare/v9.6.2...v9.6.3) (2019-05-17)


### Bug Fixes

* passed source to Marko compiler ([#26](https://github.com/oxala/marko-tester/issues/26)) ([9bdec73](https://github.com/oxala/marko-tester/commit/9bdec73))

## [9.6.2](https://github.com/oxala/marko-tester/compare/v9.6.1...v9.6.2) (2018-10-21)


### Bug Fixes

* added render-ability of specific taglibs for marko3 ([08541f9](https://github.com/oxala/marko-tester/commit/08541f9))

## [9.6.1](https://github.com/oxala/marko-tester/compare/v9.6.0...v9.6.1) (2018-10-17)


### Bug Fixes

* reverted to just-clone for renderBody ([9832386](https://github.com/oxala/marko-tester/commit/9832386))

# [9.6.0](https://github.com/oxala/marko-tester/compare/v9.5.3...v9.6.0) (2018-10-17)


### Features

* added ability to render specified taglibs ([7d8b9f0](https://github.com/oxala/marko-tester/commit/7d8b9f0))

## [9.5.3](https://github.com/oxala/marko-tester/compare/v9.5.2...v9.5.3) (2018-10-06)


### Bug Fixes

* removed just-clone dependency ([4113d26](https://github.com/oxala/marko-tester/commit/4113d26))

## [9.5.2](https://github.com/oxala/marko-tester/compare/v9.5.1...v9.5.2) (2018-10-04)


### Bug Fixes

* improved createEvent helper ([d0f6c9a](https://github.com/oxala/marko-tester/commit/d0f6c9a))

## [9.5.1](https://github.com/oxala/marko-tester/compare/v9.5.0...v9.5.1) (2018-09-28)


### Bug Fixes

* fixed marko 3 components without widgets ([c755035](https://github.com/oxala/marko-tester/commit/c755035))

# [9.5.0](https://github.com/oxala/marko-tester/compare/v9.4.2...v9.5.0) (2018-09-27)


### Features

* adjusted code to work with marko@3 and marko-widgets@6 ([5810050](https://github.com/oxala/marko-tester/commit/5810050))

## [9.4.2](https://github.com/oxala/marko-tester/compare/v9.4.1...v9.4.2) (2018-09-27)


### Bug Fixes

* updated package.json for new browser-map ([c41e4cf](https://github.com/oxala/marko-tester/commit/c41e4cf))

## [9.4.1](https://github.com/oxala/marko-tester/compare/v9.4.0...v9.4.1) (2018-09-26)


### Bug Fixes

* change some code styling ([10d8324](https://github.com/oxala/marko-tester/commit/10d8324))

# [9.4.0](https://github.com/oxala/marko-tester/compare/v9.3.0...v9.4.0) (2018-09-25)


### Bug Fixes

* set marko's isDebug to always be true ([ae7c7b6](https://github.com/oxala/marko-tester/commit/ae7c7b6))
* treated `test` environment as debug for marko ([e553045](https://github.com/oxala/marko-tester/commit/e553045))


### Features

* enviromental differentiation between install and run ([84911c9](https://github.com/oxala/marko-tester/commit/84911c9))

## [9.3.1](https://github.com/oxala/marko-tester/compare/v9.3.0...v9.3.1) (2018-09-25)


### Bug Fixes

* treated `test` environment as debug for marko ([e553045](https://github.com/oxala/marko-tester/commit/e553045))

# [9.3.0](https://github.com/oxala/marko-tester/compare/v9.2.0...v9.3.0) (2018-09-24)


### Bug Fixes

* worked around the issue for legacy component rerenders ([208b34f](https://github.com/oxala/marko-tester/commit/208b34f))


### Features

* added feature to run snapshot test selectively ([182bc5e](https://github.com/oxala/marko-tester/commit/182bc5e))
* added helpers for defer and custom event ([ea7bf50](https://github.com/oxala/marko-tester/commit/ea7bf50))

# [9.2.0](https://github.com/oxala/marko-tester/compare/v9.1.0...v9.2.0) (2018-09-23)


### Features

* added support for <await/> tags ([5c13acc](https://github.com/oxala/marko-tester/commit/5c13acc))

# [9.1.0](https://github.com/oxala/marko-tester/compare/v9.0.5...v9.1.0) (2018-09-22)


### Features

* removed fixture folder configuration, defaulted to __snapshots__ ([e64f314](https://github.com/oxala/marko-tester/commit/e64f314))

## [9.0.5](https://github.com/oxala/marko-tester/compare/v9.0.4...v9.0.5) (2018-09-22)


### Bug Fixes

* fixed path to node_modules for marko map generation ([dbe0bd6](https://github.com/oxala/marko-tester/commit/dbe0bd6))

## [9.0.4](https://github.com/oxala/marko-tester/compare/v9.0.3...v9.0.4) (2018-09-22)


### Bug Fixes

* fixed search of fixtures without snapshot test run ([553e51e](https://github.com/oxala/marko-tester/commit/553e51e))

## [9.0.3](https://github.com/oxala/marko-tester/compare/v9.0.2...v9.0.3) (2018-09-22)


### Bug Fixes

* exposed marko-tester as a function ([f41aae7](https://github.com/oxala/marko-tester/commit/f41aae7))

## [9.0.2](https://github.com/oxala/marko-tester/compare/v9.0.1...v9.0.2) (2018-09-22)


### Bug Fixes

* added npm publish for semantic-release ([1cebddb](https://github.com/oxala/marko-tester/commit/1cebddb))

## [9.0.1](https://github.com/oxala/marko-tester/compare/v9.0.0...v9.0.1) (2018-09-22)


### Bug Fixes

* fixed publish tag ([e3cb721](https://github.com/oxala/marko-tester/commit/e3cb721))

# [9.0.0](https://github.com/oxala/marko-tester/compare/v8.5.1...v9.0.0) (2018-09-22)


### Bug Fixes

* preserved empty fixture folder in git for tests ([4608624](https://github.com/oxala/marko-tester/commit/4608624))


### Features

* replaced mocha with jest ([3e30509](https://github.com/oxala/marko-tester/commit/3e30509))


### BREAKING CHANGES

* whole interface is different, refer to README.
