# Changelog

All notable changes to this project will be documented in this file.  
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### BREAKING CHANGES

- Add new import order to be more strictly

## v3.0.0 - 2020-03-14

### Added

- Add support for ECMAScript 2020 syntax

### Changed

- Update eslint 6.1.0 -> 6.8.0
- Update minimum version of eslint as peerDependency to 6.8.0

### Removed

- Dropped support for Node 8

## v2.0.1 - 2019-07-03

### Added

- Add compatibility to newer version of eslint as peer-dependency

### Changed

- Change `no-confusing-arrow` to keep its value between eslint 5 and 6

## v2.0.0 - 2019-05-22

### Added

- Add no-async-promise-executor rule
- Add no-await-in-loop rule
- Add no-misleading-character-class rule
- Add require-atomic-updates rule
- Add no-else-return rule
- Add no-octal-escape rule
- Add strict rule
- Add camelcase rule for functions
- Add prefer-object-spread rule as a warning

### Changed

- Change no-extra-parens rule for check only functions calls
- Change no-shadow rule for allowing `fastify`, and `next` variables to
  be shadowed and disallow the builtin globals one
- Change no-use-before-define rule for allowing functions to be used before
  declaration
- Change func-name rule to be `as-needed`
- Change id-length rule to ignore properties and allow `i`, `j`, `x`,
  `y`, `z` names
- Change max-depth rule to be max 4
- Change max-len rule for ignoring trailing comments
- Change max-nested-callbacks rule to be max 4
- Change max-statements rule to be max 25 and ignoring the top level functions
- Change max-statements-per-line rule to be max 2
- Change no-undescore-dangle rule to allow the use for after `this`, `super` and
  for `_s`, `_p`, `_q`, `_l`, `_sk`, `_st` and `__STATE__` variables for internal use
- Change quote-props rule for ignoring unnecessary quotes
- Change quote-props rule for always allow template literals

### Removed

- Removed require-await rule
- Removed no-process-env rule
- Removed new-cap rule
- Removed no-inline-comments rule
- Disable some rules for the *.test.js files

## v2.0.0-rc.2 - 2019-05-07

### Added

- Add `_s`, `_p`, `_q`, `_l`, `_sk`, `_st` and `__STATE__` to allowed
  values to the no-underscore-dangle rule for internal usage

## v2.0.0-rc.1 - 2019-05-06

### Changed

- Fix id-length rule to ignore properties and allow `i`, `j`, `x`,
  `y`, `z` names

## v2.0.0-rc.0 - 2019-05-06

### Added

- Add no-async-promise-executor rule
- Add no-await-in-loop rule
- Add no-misleading-character-class rule
- Add require-atomic-updates rule
- Add no-else-return rule
- Add no-octal-escape rule
- Add strict rule
- Add camelcase rule for functions
- Add prefer-object-spread rule as a warning

### Changed

- Update to ecmaVersion 2019 and enable jsx feature
- Change no-extra-parens rule for check only functions calls
- Change no-shadow rule for allowing `fastify`, and `next` variables to
  be shadowed and disallow the builtin globals one
- Change no-use-before-define rule for allowing functions to be used before
  declaration
- Change func-name rule to be `as-needed`
- Change id-length rule to ignore properties and allow `i`, `j`, `x`,
  `y`, `z` names
- Change max-depth rule to be max 4
- Change max-len rule for ignoring trailing comments
- Change max-nested-callbacks rule to be max 4
- Change max-statements rule to be max 25 and ignoring the top level functions
- Change max-statements-per-line rule to be max 2
- Change no-undescore-dangle rule to allow the use for after `this` and `super`
- Change quote-props rule for ignoring unnecessary quotes
- Change quote-props rule for always allow template literals

### Removed

- Removed require-await rule
- Removed no-process-env rule
- Removed new-cap rule
- Removed no-inline-comments rule
- Disable some rules for the *.test.js files

## v1.7.9 - 2018-08-06

### Removed

- Removed no-magic-numbers rule

## v1.7.8 - 2018-01-04

### Removed

- Removed complexity rule
- Removed camelcase rule
- Removed strict rule

## v1.7.7 - 2017-11-15

### Added

- Add spread operator support

## v1.7.6 - 2017-10-13

### Removed

- removed arrow-body-style rule

## v1.7.5 - 2017-10-13

### Removed

- removed arrow-parens rule

## v1.7.4 - 2017-10-10

### Changed

- allow `_id` for no-undescore-dangle

## v1.7.3 - 2017-10-02

### Changed

- no-sync changed to warning

## v1.7.2 - 2017-09-22

### Removed

- remove options to no-param-reassign

## v1.7.1 - 2017-09-22

### Changed

- relax no-param-reassign

## v1.7.0 - 2017-09-22

### Changed

- Add `0` and `1` to the allowed magic numbers

## v1.6.0 - 2017-09-18

### Changed

- relax some rules

## v1.5.0 - 2017-09-07

### Changed

- enable 2017 ecma

## v1.4.0 - 2017-09-05

### Added

- `;` are errors

## v1.3.0 - 2017-08-11

### Changed

- Change org name from makeitapp to mia-platform
- no-magic-number is an error
- no spaces around `[]`
- tweak to some rules

## v1.2.0 - 2017-08-05

### Added

- Add the bulk of rules to the linter

## v1.1.0 - 2017-08-02

### Added

- Add missing package information

## v1.0.0 - 2017-08-02

- Initial Release
