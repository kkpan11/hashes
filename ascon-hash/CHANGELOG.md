# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.3.0 (UNRELEASED)
### Changed
- Edition changed to 2024 and MSRV bumped to 1.85 ([#652])
- Relax MSRV policy and allow MSRV bumps in patch releases
- Update to `digest` v0.11
- Replace type aliases with newtypes [#678]
- Adopt to changes from NIST draft
  - Remove `AsconAHash` and `AsconAXof`
  - Rename `AsonHash` to `AsconHAsh256`
  - Rename `AsconXof` to `AsconXof128`

[#652]: https://github.com/RustCrypto/hashes/pull/652
[#678]: https://github.com/RustCrypto/hashes/pull/678

## 0.2.0 (2023-03-21)
### Changed
- Drop MSRV back to 1.56 and keep it in sync with `ascon` ([#459])
- Relicense as Apache-2.0 or MIT ([#459])
- Renamed public types to follow UpperCamelCase naming convention ([#459])
  - `AsconXOF` -> `AsconXof`
  - `AsconXOFReader` -> `AsconXofReader`
  - `AsconAXOF` -> `AsconAXof`
  - `ASconAXOFReader`-> `AsconAXofReader`

[#459]: https://github.com/RustCrypto/hashes/pull/459

## 0.1.1 (2023-03-17)

* Use `aead` instead of `aead-core`.
* Bump MSRV to 1.60.
* Add benchmarks.

## 0.1 (2022-06-03)

* Initial release.
