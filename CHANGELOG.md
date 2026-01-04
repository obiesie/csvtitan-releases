# Changelog

All notable changes to CSV Titan will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2026-01-04

### Fixed
- Fixed "failed to determine supertype" error during file conversion fallback
- Fixed Bad Row Badge layout to prevent text wrapping
- Fixed Progress Bar regression where progress could appear to go backward

## [0.1.0] - 2025-12-28


### Fixed
- Fixed MSI installer build error
- Fixed blank data display issue in table views
- Fixed file switching not triggering conversion
- Fixed broken row counts for certain malformed CSV files
- Removed debug `console.log` statements

## [0.1.0-alpha.1] - 2025-12-27

### Added

- Initial alpha release
- CSV file loading with memory-mapped I/O for fast performance
- Virtual scrolling grid for smooth navigation through large datasets
- Column statistics panel (min, max, null count, unique estimate)
- Type detection for numeric columns
- Filtering with contains, equals, greater than, less than operators
- Export to CSV and Excel formats
- 5-day trial with license key activation
- Cross-platform support (macOS, Windows, Linux)
- Update notification banner (checks GitHub releases)

### Known Issues

- No auto-update yet (manual download required)
- Unsigned binaries cause OS security warnings
- Performance may degrade with 100+ columns
