# Change Log

All notable changes to the "syux-language" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.7.1] - 2025-04-20

### Fixed
- Fixed dtor syntax (removed parameters requirement)
- Fixed class fields not requiring initialization values
- Fixed method calls on static libraries (crypto, sys, data, etc.)
- Fixed self reference in constructors and methods
- Fixed variable renaming for library aliases (crypto -> syxcrypto, etc.)

### Added
- Better error messages for class parsing

## [0.7.0] - 2025-04-20

### Added
- Version bump for release

### Added
- New libraries: `data`, `crypto`, `sys`, `thread`
- Array STL methods: `.len`, `.first`, `.last`, `.sum`, `.max`, `.min`, `.avg`, `.map`, `.filter`, `.reduce`, `.sort`, `.join`, `.includes`
- Standard library documentation in README
- Updated compiler version to v0.6.0

### Fixed
- Crypto library linking on Windows
- std::sqrt not declared for data library

## [Unreleased]

- Initial release