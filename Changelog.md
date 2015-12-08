# SimpleTest - Change Log

## [Unreleased]
### Changes
* fixed several acceptance tests and enabled PHP server to serve the examples
* fix [SF#192](http://sourceforge.net/p/simpletest/bugs/192/) PUT request fails to encode body parameters
* added Changelog
* added .php_cs fixer configuration to keep cs consistent
* fixed code-style and phpdoc issues through codebase
* BC break: CodeCoverage Extension uses PHP extension "sqlite3" now
  - dropped PEAR DB dependency
* fixed #17 - Access to original constructor in mocks (@mal)
* fixed return "exit code" of true/1, when tests are passing
* fixed #14 - Add support for mocking variadic methods (@36degrees)

## [1.1.7] - 2015-09-21
### Changes
* issue #12 - fix double constructor
* issue #11 - fix reference expectation

[Unreleased]: https://github.com/simpletest/simpletest/compare/v1.1.7...HEAD
[1.1.7]: https://github.com/simpletest/simpletest/compare/v1.1.7...v1.1.6