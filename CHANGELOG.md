# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/).

---

## [0.3.5] - 2026-02-06

### Added

- User can now delete wanted project from workspace

## [0.3.2] - 2026-02-02

### Added

- Refetch project action on endpoint view
- Update display name

## [0.3.0] - 2026-02-01

### Added

- Authentication form validation before submission
- Add required indicator to authication tab and input field

## [0.2.0] - 2026-01-30

### Fixed

- Fixed an issue where open panels remained active after switching projects, causing panels with undefined or stale data to stay open.
- Improved panel lifecycle handling to automatically close views whose main data becomes unavailable when the active project changes.

---

## [0.1.2] - 2026-01-29

### Added

- Initial public release of **Spaghetti**.
- Sidebar views for managing projects and requests.
- Ability to load OpenAPI specifications from local JSON/YAML files or URLs.
- Render OpenAPI documentation directly inside VS Code.
- Webview-based UI for endpoint details and API exploration.

---

## [Unreleased]

### Planned

- Environment and variable management
- Improved request execution and response previews
- Better error reporting for invalid OpenAPI specs
- Performance optimizations for large API documents
