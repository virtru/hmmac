# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Start of CHANGELOG

### Changed
- `hmmac._hash` & `hmmac._hmac` default to utf8 to mimic node v6+ behaviour
- `hmmac._hash` & `hmmac._hmac` accept an `inputEncoding` to override utf8
- scheme plain's `sign` now takes an additional parameter of object with input/output encodings
- `hmmac.sign` & `hmmac._sign` take an optional additional parameter of input/output encodings
