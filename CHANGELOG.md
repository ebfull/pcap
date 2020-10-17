# Changelog

## [Unreleased]

### Added

- Add `Derive(Clone)` to `Device` struct (#100).
- Build-time `libpcap` version detection.
- Add support for immediate mode.

### Changed

- Opt into Rust 2018.
- Now minimum supported rustc version is 1.40.0.
- Updated dependency from deprecated `tokio-core` to `tokio` 0.2.
- Updated dependency `futures` from version 0.1 to 0.3.
- Feature `tokio` renamed to `capture-stream` because Cargo does not allow
  features and dependencies to have the same name.
- `PCAP_LIBDIR` renamed to `LIBPCAP_LIBDIR` to distinguish the `pcap` crate
  from the `libpcap` library.

### Removed

- Feature flags `pcap-savefile-append`, `pcap-fopen-offline-precision`
  (replaced by build-time `libpcap` version detection)

## [0.7.0] - 2017-08-04

No Changelog entries for <= 0.7.0
