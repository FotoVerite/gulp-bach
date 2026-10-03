# Changelog

## 1.0.0 (2026-10-03)


### ⚠ BREAKING CHANGES

* Rework extension helper to get options
* Normalize repository, dropping node <10.13 support ([#34](https://github.com/FotoVerite/gulp-bach/issues/34))
* change flatten to Array.prototype.slice.apply

### Features

* Reflect concurrency option in documentation ([2c47259](https://github.com/FotoVerite/gulp-bach/commit/2c47259f650e52eb0410713c3766e6b1eda1bcdc))
* Remove ES5 utility dependencies ([1c631cb](https://github.com/FotoVerite/gulp-bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Remove node assert usage ([a1ba61d](https://github.com/FotoVerite/gulp-bach/commit/a1ba61d965477de8d2b748f5ed5d5dce343e4182))


### Bug Fixes

* Allow an array of functions as argument ([0fdef52](https://github.com/FotoVerite/gulp-bach/commit/0fdef521beb77592fe6cc9264bb6a2e76585b127))
* Handle non-functions passed as callback ([cc8bff5](https://github.com/FotoVerite/gulp-bach/commit/cc8bff56249ca7d69c514e920a83dfdfa460305b))
* Improve verifyArguments error assertions ([4932102](https://github.com/FotoVerite/gulp-bach/commit/493210251dd87b2d91eb87b339e1a962b47bf39d))
* Verify arguments to series/parallel functions (fixes [#4](https://github.com/FotoVerite/gulp-bach/issues/4)) ([ca32513](https://github.com/FotoVerite/gulp-bach/commit/ca32513beb9f1a59b68d8da61dfadb5fda5ac071))


### Miscellaneous Chores

* change flatten to Array.prototype.slice.apply ([1c631cb](https://github.com/FotoVerite/gulp-bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Normalize repository, dropping node &lt;10.13 support ([#34](https://github.com/FotoVerite/gulp-bach/issues/34)) ([1c631cb](https://github.com/FotoVerite/gulp-bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Rework extension helper to get options ([89857b6](https://github.com/FotoVerite/gulp-bach/commit/89857b6f3bbf165ca9f437663ee1de28af9de223))

### [2.0.1](https://www.github.com/gulpjs/bach/compare/v2.0.0...v2.0.1) (2022-08-29)


### Bug Fixes

* Allow an array of functions as argument ([0fdef52](https://www.github.com/gulpjs/bach/commit/0fdef521beb77592fe6cc9264bb6a2e76585b127))

## [2.0.0](https://www.github.com/gulpjs/bach/compare/v1.2.0...v2.0.0) (2022-08-25)


### ⚠ BREAKING CHANGES

* Rework extension helper to get options
* change flatten to Array.prototype.slice.apply
* Normalize repository, dropping node <10.13 support (#34)

### Features

* Reflect concurrency option in documentation ([2c47259](https://www.github.com/gulpjs/bach/commit/2c47259f650e52eb0410713c3766e6b1eda1bcdc))
* Remove ES5 utility dependencies ([1c631cb](https://www.github.com/gulpjs/bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Remove node assert usage ([a1ba61d](https://www.github.com/gulpjs/bach/commit/a1ba61d965477de8d2b748f5ed5d5dce343e4182))


### Miscellaneous Chores

* change flatten to Array.prototype.slice.apply ([1c631cb](https://www.github.com/gulpjs/bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Normalize repository, dropping node <10.13 support ([#34](https://www.github.com/gulpjs/bach/issues/34)) ([1c631cb](https://www.github.com/gulpjs/bach/commit/1c631cb014cddfea87a29e0e874a1cd85b6a1751))
* Rework extension helper to get options ([89857b6](https://www.github.com/gulpjs/bach/commit/89857b6f3bbf165ca9f437663ee1de28af9de223))
