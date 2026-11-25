# Changelog

All notable changes to Weheat Control are listed here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project uses
[semantic versioning](https://semver.org/). Each version's section becomes the
notes of its GitHub release, which HACS shows when offering the update.

## [Unreleased]

## [0.2.0] - 2026-11-25

### Added

- Hot-water boost buttons for 90 and 120 minutes.
- Manual hot-water schedule editing and a three-way hot-water mode select.
- The Weheat Intelligence hot-water plan as a timeline, showing "Not yet
  published" until Weheat publishes the day's plan.

### Changed

- Hot-water Weheat Intelligence comfort maps to the app's Normal/Eco choice.
- Setup instructions explain how to copy the `weheat://auth` callback URL from
  the browser's developer tools, with tips when login seems to do nothing.
- The project is now maintained at
  [lektriek/ha-weheat-control](https://github.com/lektriek/ha-weheat-control).
  If you added the old repository to HACS, add this one instead.

### Removed

- The Hot-water Weheat Intelligence switch; use the hot-water mode select.

## [0.1.0] - 2026-11-05

First version, by Tim Feskens at
[timfeskens/weheat-control](https://github.com/timfeskens/weheat-control).

[Unreleased]: https://github.com/lektriek/ha-weheat-control/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/lektriek/ha-weheat-control/compare/a82f4fb...v0.2.0
[0.1.0]: https://github.com/timfeskens/weheat-control/tree/a82f4fb
