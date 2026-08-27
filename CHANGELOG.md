# Changelog

## OpenBRF Enhanced — August 2026

### Added

- Added a search bar to the resource selector.
- Added bulk export of selected animations to separate SMD files.

### Fixed

- Fixed the SMD export scale issue where exported animation/model data could be 10× larger than expected in external tools.
- Added explicit SMD scale metadata for new OpenBRF exports while preserving compatibility with legacy OpenBRF SMD files.

### Packaging

- Removed local build output and Qt Creator `.pro.user` files from the source repository package.
