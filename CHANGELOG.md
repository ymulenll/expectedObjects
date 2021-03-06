# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.3.3"></a>
## [2.3.3](https://github.com/derekgreer/expectedObjects/compare/v2.3.2...v2.3.3) (2017-10-25)


### Bug Fixes

* Correct issue with custom comparisons and missing elements where comparison was always true. ([9a59a39](https://github.com/derekgreer/expectedObjects/commit/9a59a39))



<a name="2.3.2"></a>
## [2.3.2](https://github.com/derekgreer/expectedObjects/compare/v2.3.1...v2.3.2) (2017-10-02)


### Bug Fixes

* Correct exception when comparing types with overloaded indexes ([422bdf1](https://github.com/derekgreer/expectedObjects/commit/422bdf1))



<a name="2.3.1"></a>
## [2.3.1](https://github.com/derekgreer/expectedObjects/compare/v2.3.0...v2.3.1) (2017-09-24)


### Bug Fixes

* Correct reporting issue when null object is displayed. ([8178f7c](https://github.com/derekgreer/expectedObjects/commit/8178f7c))
* Correct reporting issue with recursive instances. ([4702d50](https://github.com/derekgreer/expectedObjects/commit/4702d50))



<a name="2.3.0"></a>
# [2.3.0](https://github.com/derekgreer/expectedObjects/compare/v2.2.0...v2.3.0) (2017-09-22)


### Bug Fixes

* Fix parallel test output ([a3ed69e](https://github.com/derekgreer/expectedObjects/commit/a3ed69e))


### Features

* Added Expect.Default<T>() and Expect.NotDefault<T>() custom comparisons. ([2a5b1bc](https://github.com/derekgreer/expectedObjects/commit/2a5b1bc))



<a name="2.2.0"></a>
# [2.2.0](https://github.com/derekgreer/expectedObjects/compare/v2.1.1...v2.2.0) (2017-09-13)


### Features

* Add ability to configure custom comparsions for specific members. ([abab048](https://github.com/derekgreer/expectedObjects/commit/abab048))



<a name="2.1.1"></a>
## [2.1.1](https://github.com/derekgreer/expectedObjects/compare/v2.1.0...v2.1.1) (2017-09-04)


### Bug Fixes

* typo corrections ([e978c39](https://github.com/derekgreer/expectedObjects/commit/e978c39))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/derekgreer/expectedObjects/compare/v2.0.0...v2.1.0) (2017-08-29)


### Features

* Add configuration to enable ordinal comparisons. ([2b26e25](https://github.com/derekgreer/expectedObjects/commit/2b26e25))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/derekgreer/expectedObjects/compare/v1.3.1...v2.0.0) (2017-08-29)


### Features

* Redesign test output to display approximation of expected and actual values ([1454dc2](https://github.com/derekgreer/expectedObjects/commit/1454dc2))


### BREAKING CHANGES

* Add ability to ignore the order when comparing instances of IEnumerable ([1454dc2](https://github.com/derekgreer/expectedObjects/commit/1454dc2))
* Replace ExpectedObject.Configure() method with ExpectedObjectBuilder ([1454dc2](https://github.com/derekgreer/expectedObjects/commit/1454dc2))
* Replace the IgnoreTypes() method with ExpectedObject extension methods: Matches(), DoesNotMatch() ([1454dc2](https://github.com/derekgreer/expectedObjects/commit/1454dc2))


### Chores

* chore(build): Add build support for packing and publishing pre-releases ([1454dc2](https://github.com/derekgreer/expectedObjects/commit/1454dc2))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/derekgreer/expectedObjects/compare/v1.3.0...v1.3.1) (2017-08-26)


### Bug Fixes

* Prevent infinite recursive comparisions ([837ea19](https://github.com/derekgreer/expectedObjects/commit/837ea19))



<a name="1.3.0"></a>
# 1.3.0 (2017-05-09)


### Features

* Added support for .Net Standard 1.3 ([60e65e3](https://github.com/derekgreer/expectedObjects/commit/60e65e3))
