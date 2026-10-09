# Changelog

All notable changes to Aurora Midnight are documented in this file.

This project follows a version-based release history.

## [Unreleased]

### Planned
- Refine the color palette based on user feedback.
- Improve syntax highlighting consistency across supported languages.
- Review accessibility and contrast across common editor states.
- Improve documentation and add additional theme screenshots when available.

## [0.1.0] - Initial Preview Release

### Added
- Initial release of Aurora Midnight, a dark theme for Visual Studio Code.
- Midnight navy and charcoal surfaces for a focused coding environment.
- Electric blue primary accents with violet and cyan secondary accents.
- Coordinated theme colors for supported workbench components.
- TextMate token colors for syntax highlighting.
- Semantic token colors for languages and extensions that support semantic highlighting.
- Styling for supported editor, sidebar, tabs, panels, menus, terminal elements, and diagnostics.
- A README with installation instructions, recommended settings, design philosophy, and troubleshooting guidance.
- A license file and initial release documentation.

### Changed
- Established a consistent dark palette across supported interface elements.
- Aligned core syntax-highlighting roles with familiar VS Code Dark+ conventions.
- Reduced green-hued accents in the workbench UI while retaining familiar syntax colors where appropriate.

### Documentation
- Documented local VSIX installation and theme activation.
- Added optional editor typography recommendations.
- Explained the limitations of the VS Code color theme API.
- Documented accessibility considerations and troubleshooting steps.

### Known Limitations
- A color theme cannot independently redesign the native VS Code workbench layout.
- Custom wallpaper and arbitrary rounded-corner styling are not available through the standard color theme API alone.
- Syntax highlighting may vary depending on the programming language, installed extensions, and semantic highlighting support.
- Optional editor fonts must be installed and configured separately.

---

## Versioning

- **Patch release** (`0.1.1`): Small fixes and corrections.
- **Minor release** (`0.2.0`): New theme improvements or additional color mappings.
- **Major release** (`1.0.0`): A stable release milestone with a finalized initial feature set.

## Release Notes

Release dates should reflect the actual publication date. Update this file whenever a new version of Aurora Midnight is released.