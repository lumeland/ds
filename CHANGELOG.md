# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this
project adheres to [Semantic Versioning](http://semver.org/).

## [0.7.2] - Unreleased
### Fixed
- `--color-highlight` in dark mode should be a bit darker.
- Inline `code` styles are too strong.

## [0.5.1] - 2024-03-20
### Added
- New `.markdown-alert` styles.

### Changed
- Remove `ui-normalize` dependency.

### Fixed
- Added `text-wrap:balance` to all headers of `.body`.
- Default font-weight of headers.

## [0.5.0] - 2024-03-20
### Added
- New `icon` component to add icons (with emojis).

### Changed
- Update Inter font to v4, using the variable format and InterDisplay for
  headings.
- Improved code highlight colors.
- Improved font sizes and colors.
- Use `[data-theme]` attribute instead of media queries to detect light/dark
  mode. This allows to change the theme dynamically.
- Use font weight `600` instead of `bold` (which is `700`).

### Fixed
- Fixed the layout of the pagination component.

## [0.4.0] - 2024-01-02
### Added
- New `blockquote` component [#2].

## [0.3.3] - 2023-12-13
### Fixed
- Break long links: https://github.com/lumeland/theme-simple-blog/issues/19

## [0.3.2] - 2023-11-15
### Changed
- Removed Epilogue as the font for display.

## [0.3.1] - 2023-09-21
### Changed
- Reduce the font size of the body to `18px`.

### Fixed
- Remove ligatures of the code.

## [0.3.0] - 2023-08-01
### Added
- New `footnotes` component.

## [0.2.4] - 2023-07-19
### Fixed
- code selection not showed due to CSS bug [#1].

## [0.2.3] - 2023-07-19
### Added
- The `src` folder with the original CSS code.

## [0.2.2] - 2023-03-12
### Fixed
- Updated the `ds.css` dist file.

## [0.2.1] - 2023-03-12
### Fixed
- Clear button must be always visible.

## [0.2.0] - 2023-03-12
### Changed
- Use `grid` instead of `flex` in the pagination.

### Fixed
- Clear button in the `search` component.

## [0.1.1] - 2023-02-14
### Fixed
- Removed `flex-wrap: wrap` in pagination and fixed the text alignment.
- The bottom line of the `h2` in the body was too close.

## [0.1.0] - 2023-01-28
First version

[#1]: https://github.com/lumeland/ds/issues/1
[#2]: https://github.com/lumeland/ds/issues/2

[0.7.2]: https://github.com/lumeland/ds/compare/v0.5.1...HEAD
[0.5.1]: https://github.com/lumeland/ds/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/lumeland/ds/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/lumeland/ds/compare/v0.3.3...v0.4.0
[0.3.3]: https://github.com/lumeland/ds/compare/v0.3.2...v0.3.3
[0.3.2]: https://github.com/lumeland/ds/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/lumeland/ds/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/lumeland/ds/compare/v0.2.4...v0.3.0
[0.2.4]: https://github.com/lumeland/ds/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/lumeland/ds/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/lumeland/ds/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/lumeland/ds/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/lumeland/ds/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/lumeland/ds/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/lumeland/ds/releases/tag/v0.1.0
