# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [v0.2.3] - 2017-07-10
### Added
- Start of CHANGELOG [#1]

### Changed
- `hmmac._hash` & `hmmac._hmac` default to utf8 to mimic node v6+ behaviour [#1]
- `hmmac._hash` & `hmmac._hmac` accept an `inputEncoding` to override utf8 [#1]
- scheme plain's `sign` now takes an additional parameter of object with input/output encodings [#1]
- `hmmac.sign` & `hmmac._sign` take an optional additional parameter of input/output encodings [#1]

[#1]: https://github.com/virtru/hmmac/pull/1
