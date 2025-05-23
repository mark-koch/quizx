# Changelog

This is the changelog for the `quizx` rust library.
For the changelog of the `quizx` python library, see the separate [`CHANGELOG.md`](https://github.com/zxcalc/quizx/blob/master/pybindings/CHANGELOG.md) file.


## [0.3.0](https://github.com/mark-koch/quizx/compare/quizx@v0.2.0...quizx@v0.3.0) - 2025-05-23

### Bug Fixes

- bug in pack() not setting boundary names

### New Features

- added method to pack VecGraph vertices, removing holes ([#126](https://github.com/mark-koch/quizx/pull/126))
- [**breaking**] Generator for surface code circuits ([#128](https://github.com/mark-koch/quizx/pull/128))
- [**breaking**] converting a circuit to a graph while performing Clifford simplifications ([#133](https://github.com/mark-koch/quizx/pull/133))
- [**breaking**] better equality checker ([#136](https://github.com/mark-koch/quizx/pull/136))

## [0.2.0](https://github.com/zxcalc/quizx/compare/quizx@v0.1.0...quizx@v0.2.0) - 2025-05-12

### Documentation

- *(rs)* Add crate documentation ([#122](https://github.com/zxcalc/quizx/pull/122))

### New Features

- Simplification-Based Equality Checker ([#110](https://github.com/zxcalc/quizx/pull/110))
- [**breaking**] Support for boolean variables on spiders and scalars ([#125](https://github.com/zxcalc/quizx/pull/125))

## [0.1.0](https://github.com/zxcalc/quizx/releases/tag/quizx@v0.1.0) - 2025-05-04

First crate release
