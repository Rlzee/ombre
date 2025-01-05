# Change Log

All notable changes to the "ombre" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

### Added

- Initial release with a dark theme ("ombre") for VSCode.
- Added support for various token color customizations:
  - **Comments**: Italicized and given a soft color (#6C8692).
  - **Variables**: Light cyan (#EEFFFF) for better visibility.
  - **Keywords and Storage**: Pink (#FF69B4) for keywords and storage types.
  - **Functions and Special Methods**: Light pink (#FF8FA3) for better distinction.
  - **Operators and Miscellaneous**: Cyan-blue (#89DDFF) for operators.
  - **HTML Attributes**: Italic and yellow (#FFCB6B) for HTML attribute names.
  - **Class and Support Types**: Soft yellow (#FFCB6B) for classes and support types.

### Changed

- **Enhanced contrast between similar token types**:
  - Adjusted color tones for better differentiation between functions and keywords (from close pink tones to more distinct shades).
  - Improved color contrast for constants and variable names to avoid visual fatigue.
  - Optimized highlight colors for string literals and constants to make them more readable without being too flashy.
  - Reduced the saturation of string delimiters to keep focus on content.
  - Improved visibility of HTML tags and attributes by using a brighter color for attributes.

### Fixed

- Minor fixes to color assignment for specific tokens like `meta.block` and `support.type.sys-types`.

## [1.0.0] - 2025-01-05

- First release with the complete Ombre theme.
