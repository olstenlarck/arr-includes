# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.0.3"></a>
## [2.0.3](https://github.com/tunnckocore/arr-includes/compare/v2.0.2...v2.0.3) (2017-03-11)


### Bug Fixes

* **coverage:** force nyc to 100% ([e99a093](https://github.com/tunnckocore/arr-includes/commit/e99a093))
* **deps:** update deps ([8691d38](https://github.com/tunnckocore/arr-includes/commit/8691d38))



<a name="2.0.2"></a>
## [2.0.2](https://github.com/tunnckocore/arr-includes/compare/v2.0.1...v2.0.2) (2016-10-29)


### Bug Fixes

* **docs:** params before examples ([0ed25c5](https://github.com/tunnckocore/arr-includes/commit/0ed25c5))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/tunnckocore/arr-includes/compare/v2.0.0...v2.0.1) (2016-10-27)


### Bug Fixes

* **version:** fix version collistions, huh.. fast fingers ([546a68d](https://github.com/tunnckocore/arr-includes/commit/546a68d))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/tunnckocore/arr-includes/compare/v1.0.2...v2.0.0) (2016-10-26)


### Features

* **index:** returns the index of the match, true if index is 0 ([9c7a075](https://github.com/tunnckocore/arr-includes/commit/9c7a075))


### BREAKING CHANGES

* index: returns an index instead of true; it returns false only if found index is 0; always

returns positive value





## 1.0.2 - 2016-09-21
- Release v1.0.2 / npm@v1.0.2
- add missing `coveralls` to devDeps, closes #3

## 1.0.1 - 2016-09-20
- Release v1.0.1 / npm@v1.0.1
- use `lazy-cache`, closes #2
- update package.json: npm scripts
- update travis.yml
- update gitignore
- add `standard@8` and `nyc` to devDeps
- switch to use `mukla` instead of `assertit`

## 1.0.0 - 2016-03-18
- Release v1.0.0 / npm@v1.0.0
- fix "duplicate" issues reported by @codeclimate, arrrgghh!
- implement :cat2:

## 0.0.0 - 2016-03-18
- Initial commit