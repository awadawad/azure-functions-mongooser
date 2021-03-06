# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.6.7"></a>
## [1.6.7](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.6...v1.6.7) (2018-05-15)


* **build:** update deps



<a name="1.6.6"></a>
## [1.6.6](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.5...v1.6.6) (2018-05-15)


* **build:** update deps



<a name="1.6.5"></a>
## [1.6.5](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.4...v1.6.5) (2018-01-25)


### Bug Fixes

* **afm:** fix tslint ([#59](https://github.com/azure-seed/azure-functions-mongooser/issues/59)) ([412ff2a](https://github.com/azure-seed/azure-functions-mongooser/commit/412ff2a))


### Performance Improvements

* **afm:** use bluebird for underlying connections ([#60](https://github.com/azure-seed/azure-functions-mongooser/issues/60)) ([c5c474c](https://github.com/azure-seed/azure-functions-mongooser/commit/c5c474c))



<a name="1.6.4"></a>
## [1.6.4](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.3...v1.6.4) (2017-12-21)


* **afm**: update query parser ([#49](https://github.com/azure-seed/azure-functions-mongooser/pull/49))



<a name="1.6.3"></a>
## [1.6.3](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.2...v1.6.3) (2017-12-06)


### Bug Fixes

* **afm:** remove bluebird dependencies ([#42](https://github.com/azure-seed/azure-functions-mongooser/issues/42)) ([814740f](https://github.com/azure-seed/azure-functions-mongooser/commit/814740f))



<a name="1.6.2"></a>
## [1.6.2](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.1...v1.6.2) (2017-12-05)


### Performance Improvements

* **afm:** add bluebird ([#41](https://github.com/azure-seed/azure-functions-mongooser/issues/41)) ([b5b79aa](https://github.com/azure-seed/azure-functions-mongooser/commit/b5b79aa))



<a name="1.6.1"></a>
## [1.6.1](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.6.0...v1.6.1) (2017-12-01)


### Bug Fixes

* **afm:** fix query parsing ([#37](https://github.com/azure-seed/azure-functions-mongooser/issues/37)) ([eae113f](https://github.com/azure-seed/azure-functions-mongooser/commit/eae113f))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.5.1...v1.6.0) (2017-12-01)


### Bug Fixes

* **afm:** fix pagination ([#36](https://github.com/azure-seed/azure-functions-mongooser/issues/36)) ([3133931](https://github.com/azure-seed/azure-functions-mongooser/commit/3133931))


### Features

* **afm:** add filtering, sorting and pagination ([#35](https://github.com/azure-seed/azure-functions-mongooser/issues/35)) ([51c451d](https://github.com/azure-seed/azure-functions-mongooser/commit/51c451d))



<a name="1.5.1"></a>
## [1.5.1](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.5.0...v1.5.1) (2017-10-17)


### Bug Fixes

* **afm:** fix connect promise resolution ([#26](https://github.com/azure-seed/azure-functions-mongooser/issues/26)) ([4777c7f](https://github.com/azure-seed/azure-functions-mongooser/commit/4777c7f))


### Performance Improvements

* **afm:** reduce connect timeout to 250ms ([#27](https://github.com/azure-seed/azure-functions-mongooser/issues/27)) ([f527998](https://github.com/azure-seed/azure-functions-mongooser/commit/f527998))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.4.0...v1.5.0) (2017-10-17)


### Bug Fixes

* **afm:** add limit to recursive connection retries ([#25](https://github.com/azure-seed/azure-functions-mongooser/issues/25)) ([12ee51d](https://github.com/azure-seed/azure-functions-mongooser/commit/12ee51d))
* **afm:** reconnect after first failure ([#23](https://github.com/azure-seed/azure-functions-mongooser/issues/23)) ([88885e5](https://github.com/azure-seed/azure-functions-mongooser/commit/88885e5)), closes [#22](https://github.com/azure-seed/azure-functions-mongooser/issues/22)


### Features

* **afm:** import error type from ts-essentials ([#24](https://github.com/azure-seed/azure-functions-mongooser/issues/24)) ([a7799f3](https://github.com/azure-seed/azure-functions-mongooser/commit/a7799f3))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.3.0...v1.4.0) (2017-10-11)


### Features

* **afm:** add bulk insert ([#21](https://github.com/azure-seed/azure-functions-mongooser/issues/21)) ([4737b63](https://github.com/azure-seed/azure-functions-mongooser/commit/4737b63))
* **afm:** remove object name ([#20](https://github.com/azure-seed/azure-functions-mongooser/issues/20)) ([b13c426](https://github.com/azure-seed/azure-functions-mongooser/commit/b13c426))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.2.0...v1.3.0) (2017-10-11)


### Bug Fixes

* **afm:** remove url from response body ([#9](https://github.com/azure-seed/azure-functions-mongooser/issues/9)) ([6ea96bc](https://github.com/azure-seed/azure-functions-mongooser/commit/6ea96bc))
* **afm:** return pure json ([#12](https://github.com/azure-seed/azure-functions-mongooser/issues/12)) ([9276702](https://github.com/azure-seed/azure-functions-mongooser/commit/9276702))


### Features

* **afm:** add field population by query value ([#17](https://github.com/azure-seed/azure-functions-mongooser/issues/17)) ([a0439e9](https://github.com/azure-seed/azure-functions-mongooser/commit/a0439e9))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.1.0...v1.2.0) (2017-10-09)


### Features

* **afm:** add error types ([#7](https://github.com/azure-seed/azure-functions-mongooser/issues/7)) ([6493933](https://github.com/azure-seed/azure-functions-mongooser/commit/6493933))
* **afm:** accept request body as application/json ([#8](https://github.com/azure-seed/azure-functions-mongooser/issues/8)) ([417c505](https://github.com/azure-seed/azure-functions-mongooser/commit/417c505))
* **afm:** add clear collection method ([#4](https://github.com/azure-seed/azure-functions-mongooser/issues/4)) ([9bc9dd3](https://github.com/azure-seed/azure-functions-mongooser/commit/9bc9dd3))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/azure-seed/azure-functions-mongooser/compare/v1.0.0...v1.1.0) (2017-10-07)


### Features

* **afm:** return error details ([#5](https://github.com/azure-seed/azure-functions-mongooser/issues/5)) ([72631c8](https://github.com/azure-seed/azure-functions-mongooser/commit/72631c8))
* **afm:** add clear collection method ([#4](https://github.com/azure-seed/azure-functions-mongooser/issues/4)) ([9bc9dd3](https://github.com/azure-seed/azure-functions-mongooser/commit/9bc9dd3))



<a name="1.0.0"></a>
# 1.0.0 (2017-10-05)
