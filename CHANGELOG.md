# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Add team label in resources.

### Changed

- Configure `gsoci.azurecr.io` as the default container image registry.

## [0.1.0] - 2023-10-17

### Changed

- Make App compliant with PSS policies:
  - Set seccompProfile to `RuntimeDefault`.
  - Set `runAsNonRoot` as true.
  - Drop ALL capabilities.
- Enable PSP installation with global value.
- Do not install PodSecurityPolicy if api not available.

## [0.0.1] - 2021-05-21

[Unreleased]: https://github.com/giantswarm/flamethrower-app/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/giantswarm/flamethrower-app/compare/v0.0.1...v0.1.0
[0.0.1]: https://github.com/giantswarm/flamethrower-app/releases/tag/v0.0.1
